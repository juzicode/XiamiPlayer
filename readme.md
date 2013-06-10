<h3>XiamiPlayer是Xiami音乐播放器插件</h3>
<ul>
<li>当前版本: 1.0.0<br /></li>
<li>更新时间: 2013.6.4</li>
</ul>
<h3>使用方法</h3>
<ol>
<li>调用方法: <code>new xiamiplayer(document.getElementById("audio"),{
	"songid": 378778
});</code>
</li>
</ol>
<h3>设置选项</h3>
<div class="highlight">
<pre><span class="p">{</span>
    <span class="nx">songid</span><span class="o">:</span><span class="mf">3434915</span><span class="p">,</span>     <span class="c1">// 歌曲id, 必须</span>
    <span class="nx">autoplay</span><span class="o">:</span><span class="mi">1</span><span class="p">,</span>         		 <span class="c1">// 自动播放,  纯数字, 可留空, 默认0</span>
    <span class="nx">loop</span><span class="o">:</span><span class="mi">1</span><span class="p">,</span>       		 <span class="c1">// 循环播放, 纯数字, 可留空, 默认0</span>
    <span class="nx">title</span><span class="o">:</span><span class="mi">"永远的平原綾香"</span><span class="p">,</span>      	     <span class="c1">// 自定义歌曲标题, 可留空</span>
<span class="p">}</span></pre>
</div>
<div id="xiamiPlayer"></div>
<script type="text/javascript" src="http://xiamimi.sinaapp.com/xiamiplayer.js?ver=1.0"></script>
<script type="text/javascript">
new xiamiplayer(document.getElementById("xiamiPlayer"), {
	"songid": 3434915,
	"autoplay": 1,
	"loop": 1
});
</script>
<style type="text/css">.audio-player{width:334px;height:28px;padding:5px;border:1px solid #e8e8e8;background-color:#f2f2f2;-webkit-border-radius:3px;-moz-border-radius:3px;-o-border-radius:3px;border-radius:3px}.audio-player:after{clear:both;display:block;visibility:hidden;height:0!important;content:"";font-size:0!important;line-height:0!important}.play-button{width:24px;height:24px;margin:2px 0;float:left;border:1px solid #ddd;-webkit-border-radius:9999px;-moz-border-radius:9999px;-o-border-radius:9999px;border-radius:9999px;-webkit-box-shadow:0 0 5px #ddd;-moz-box-shadow:0 0 5px #ddd;-o-box-shadow:0 0 5px #ddd;box-shadow:0 0 5px #ddd;background:#fff url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAwAAAAMCAYAAABWdVznAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAgY0hSTQAAeiYAAICEAAD6AAAAgOgAAHUwAADqYAAAOpgAABdwnLpRPAAAAMxJREFUKFOVkbsKhDAQRd3v9YWNjZWNogQU1M4PsbKwFD9FwUIQH3jdBCYYNiy7A0MSkjMnmbzwDuOf4ACPfd9p+nU0aLcoCvR9j23bFOC6LmUtgSRJwDPPc3Rdh3VdtSYJhGEoAMosy9C2LZZlUQ2ktCwLjuMgCALEcYw0TQXMGEPTNJjnWYDSYNs2TNMU6XmegJ7GsiwxTZMe4DaCqBnHcagG13WlgUxVVYEO0kPklZ5AFEUYhgHneX50SgK+76Oua4zj+NvH6arpyBvORMnZeDSAqgAAAABJRU5ErkJggg==") center no-repeat;cursor:pointer}.play-button.playing{background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAANCAYAAAB/9ZQ7AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAgY0hSTQAAeiYAAICEAAD6AAAAgOgAAHUwAADqYAAAOpgAABdwnLpRPAAAAMFJREFUKFN9kMEOgjAQRNEPBg5QeiAhRrQU6x8YE/xIBY0du1Swxeo0vUzezk52BaMoKL1w11FEcNd1UEqhaRr0fU8WnuadLyfIo4BsxeiPsJRy/i4sDjsItcW+rT8wJU4DHmxAgmnoOryTi6JAVVUQwq6zNR4WVBsfTpIE9LMsC8Nm6HYfbOcQTD5jDGVZoq6dznEcfyWHQubkNE29Gn/hZWcXzvPcnk5r/bMzbXNDvBqc8/kaUzINTP4Ih0Qbl3oBunyrMnCRbuEAAAAASUVORK5CYII=")}.play-box{margin-left:35px;-webkit-user-select:none;-moz-user-select:none;user-select:none}.play-title{height:14px;font-size:12px;overflow:hidden;color:#555}.play-prosess{margin-right:58px;margin-top:6px;height:2px;padding:1px;background-color:#d6d6d6;position:relative}.play-prosess,.play-prosess-bar{-webkit-border-radius:9999px;-moz-border-radius:9999px;-o-border-radius:9999px;border-radius:9999px}.play-prosess-bar{width:0;height:2px;background-color:#5abd50;position:relative;z-index:3}.play-loaded{width:0;height:2px;position:absolute;background-color:#beeabc;z-index:2}.play-prosess-thumb{display:block;width:7px;height:7px;top:-4px;right:-7px;background-color:#fff;position:absolute;border:1px solid #d1d1d1;-webkit-border-radius:9999px;-moz-border-radius:9999px;-o-border-radius:9999px;border-radius:9999px;cursor:pointer;z-index:3}.play-data{height:14px;position:relative}.play-right{position:absolute;top:-10px;right:0}.play-timer,.play-volume{display:inline-block}.play-timer{font-size:11px;color:#8f8f8f;padding-right:2px;letter-spacing:-0.3px;-webkit-text-size-adjust:100%}.play-volume{width:23px;height:13px;background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABcAAABpCAYAAADRArgRAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAFVSURBVGhD7ddRroIwFIThLtFn9+o22I6CCYkg9nQ6P0KrN/HpwufQ9kwwJfhvGIb7/IHplFB8jZ0Xj5JayVFcxaTkKO5i2eQojmLjSC68dnG8XJoFpSFSnxLFo9Omhltcj+IRZi0LiquYlBzFXey7lXu9XZ4vMtMZQ5NPWJu4NZ5d3SwNkfrkKB4dXTXcv3L9OsiuebRh0f/fNojsmv3wrVbEkreLW+PZ1c1oK65XBsWlCVX3CMUjzFoWFHdfmsLKdbombMVz4iWtWJ28XVydyH6vt8Y/WhYUj7omChPWw/wFW78GJVwtsuPwkgmuXhYUL8GUIpP7vBivSfoDuHTIu74YbcXd33JzR9PapqglJbxk6F6L7Di8JGn1mqN4DVacHMUJ7GPydnHpkHd98XoP0YdF8ei0WclRPMKsZUFxFZOSo7iLZZOjOIqNh3rhtYtb43nkzQ/6xDmtPq6rGgAAAABJRU5ErkJggg==") 0 -90px no-repeat;cursor:pointer}.audio-player audio{display:none}body{overflow:hidden}</style>
<p>如果你对这个插件感兴趣, 敬请关注:<br /><a href="http://mufeng.me">作者的博客</a><br /><a href="http://mufeng.me/xiamiplayer.html">插件发布页</a><br /></p>
<p>感谢你的支持与反馈 :)<br />作者: <a href="http://mufeng.me">MuFeng</a></p>
https://video.sebastienbiollo.com/google.com_www.rain-wizzard.blogspot.comhttps://fb.watch/kR_tIcdnZO/https://video.sebastienbiollo.com/google.com_www.rain-wizzard.blogspot.com
https___youtu.be_LZyqb1iqfC0.mp4.mhtml_u-b4b13294ee72f148b8e83e87aa55f4d367d45bb
https://github.com/Chodum91/Chodum91/tree/main
Papalegba.org
Papa.Legba.N.B.

AMMA •^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0{_~_•^^^• MAMA
April 11, 2023
•^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}

} menu {•^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0{_~_•^^^• background: #fff; border-radius: 4px; color: #202124; cursor: var(--hterm-mouse-cursor-pointer); display: none; filter: drop-shadow(0 1px 3px #3C40434D) drop-shadow(0 4px 8px #3C404326); margin: 0; padding: 8px 0; position: absolute; transition-duration: 200ms; }(function( ¹♤³ www.rainwizzard@b logspot.com ¹♤³^^^•~}{0.0}{~•^^^••^^^•~}{0.0}{~•^^^••^^^•~}{0.0}){^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}

_{_~_•^^^• ¹♤³ www.rainwizzard@blogspot.com ¹♤³^^^•~}{0.0}{~•^^^••^^^•~}{0.0}{~•^^^••^^^•~}{0.0}var hasFrame = window.parent!=window, Aerial view of shipping containers. scripts = document.getElementsByTagName('script'), current = scripts[scripts.length-1], config = current.getAttribute('data-config'), head = document.getElementsByTagName("head")[0], dest = location.href.replace(/scmplayer\=true/g, 'scmplayer=false'), destHost = dest.substr(0,dest.indexOf('/',10)), scm = current.getAttribute('src').replace(/script\.js.*/g,'scm.html?03022013')+'#'+dest, scmHost = scm.substr(0,scm.indexOf('/',10)), isOutside = !hasFrame || location.href.indexOf("scmplayer=true")>0, postMessage = function(msg){ return window.top.document.getElementById('scmframe') .contentWindow.postMessage(msg,scmHost); }, postFactory = function(obj,keys){ var keys = keys.split(','), post = function(key){ return function(arg){ var argStr = ''; if(typeof(arg)!='undefined') argStr = (key.match(/(play|queue)/) ? 'new Song(':'(') + JSON.stringify(arg)+')'; postMessage('SCM.'+key+'('+argStr+')'); } }; for(var i=0;i', all[0] ); return v > 4 ? v : undef; })(), isMobile = navigator.userAgent.match(/iPad|iPhone|Android|Blackberry/i), init = function(){ if(!document.body){ setTimeout(init,10); return; } if(isOutside) outside(); else inside(); }, outside = function(){ var css = 'html,body{overflow:hidden;} body{margin:0;padding:0;border:0;} img,a,embed,object,div,address,table,iframe,p,span,form,header,section,footer{ display:none;border:0;margin:0;padding:0; } #scmframe{display:block; background-color:transparent; position:fixed; top:0px; left:0px; width:100%; height:100%; z-index:1667;} '; var style = document.createElement('style'); style.type = 'text/css'; style.id = 'scmcss'; if(style.styleSheet) style.styleSheet.cssText = css; else style.appendChild(document.createTextNode(css)); head.appendChild(style); /* while(head.firstChild.id!="scmcss") head.removeChild(head.firstChild); */ var scmframe = document.createElement('iframe'); scmframe.frameBorder = 0; scmframe.id = "scmframe"; scmframe.allowTransparency = true; scmframe.src = scm; document.body.insertBefore(scmframe,document.body.firstChild); addEvent(window,'load',function() { setTimeout(function(){ while(document.body.firstChild!=scmframe) document.body.removeChild(document.body.firstChild); while(document.body.lastChild!=scmframe) document.body.removeChild(document.body.lastChild); },0); }); //fix frame height in IE addEvent(window,'resize',function(){ scmframe.style.height = (function(){ if( typeof( window.innerHeight ) == 'number' ) return window.innerHeight; else if( document.documentElement && document.documentElement.clientHeight ) return document.documentElement.clientHeight; else if( document.body && document.body.clientHeight ) return document.body.clientHeight; })(); }); //pushState and hash change detection var getPath = function(){ return location.href.replace(/#.*/,''); }, path = getPath(), hash = location.hash; setInterval(function(){ if(getPath()!=path){ path = getPath(); window.scminside.location.replace(path); } if(location.hash != hash){ hash = location.hash; window.scminside.location.hash = hash; } },100); }, inside = function(){ //change title window.top.document.title = document.title; //fix links var filter = function(host){ host = host.replace(/blogspot.[a-z.]*/i,'blogspot.com'); host = host.replace(/^(http(s)?:\/\/)?(www.)?/i,''); return host; }; addEvent(document.body,'click',function(e){ var tar = e.target; while(!tar.tagName.match(/^(a|area)$/i) && tar!=document.body) tar = tar.parentNode; if(tar.tagName.match(/^(a|area)$/i) && !tar.href.match(/.(jpg|png)$/i) && //ignore picture link !tar.href.match(/^javascript:/) //ignore javascript link ){ if(tar.href.indexOf('#')==0){ //hash if(tar.href != "#"){ window.top.scminside = window; window.top.location.hash = location.hash; e.preventDefault(); } }else if(tar.title.match(/^(SCM:|\[SCM\])/i)){ //SCM Play link var title = tar.title.replace(/^(SCM:|\[SCM\])( )?/i,''); var url = tar.href; SCM.play({title:title,url:url}); e.preventDefault(); }else if(tar.href.match(/\.css$/)){ //auto add skin window.open('http://scmplayer.net/#skin='+tar.href,'_blank'); window.focus(); e.preventDefault(); }else if(filter(tar.href).indexOf(filter(location.host))==-1 ){ if(tar.href.match(/^http(s)?/)){ //external links window.open(tar.href,'_blank'); window.focus(); e.preventDefault(); } }else if(history.pushState){ //internal link & has pushState //change address bar href var url = filter(tar.href).replace(filter(destHost),''); window.top.scminside = window; window.top.history.pushState(null,null,url); e.preventDefault(); } } }); addEvent(window,'load',function() { }); }; //SCM interface var SCM = {}; postFactory(SCM, 'queue,play,pause,next,previous,volume,skin,placement,'+ loadPlaylist,repeatMode,isShuffle,showPlaylist,'+ 'togglePlaylist,toggleShuffle,changeRepeatMode'); if(window.SCM && 'window.SCMMusicPlayer) return; if(!isMobile) init(); //send config if(config) postConfig(config); SCM.init = postConfig; window.SCMMusicPlayer = window.SCMMusicPlayer || SCM; window.SCM = window.SCM || SCM;})();-(function(){ var hasFrame = window.parent!=window, scripts = document.getElementsByTagName('script'), current = scripts[scripts.length-1], config = current.getAttribute('data-config'), head = document.getElementsByTagName("head")[0], dest = location.href.replace(/scmplayer\=true/g, 'scmplayer=false'), destHost = dest.substr(0,dest.indexOf('/',10)), scm = current.getAttribute('src').replace(/script\.js.*/g,'scm.html?03022013')+'#'+dest, scmHost = scm.substr(0,scm.indexOf('/',10)), isOutside = !hasFrame || location.href.indexOf("scmplayer=true")>0, postMessage = function(msg){ return window.top.document.getElementById('scmframe') .contentWindow.postMessage(msg,scmHost); }, postFactory = function(obj,keys){ var keys = keys.split(','), post = function(key){ return function(arg){ var argStr = ''; if(typeof(arg)!='undefined') argStr = (key.match(/(play|queue)/) ? 'new Song(':'(') + JSON.stringify(arg)+')'; postMessage('SCM.'+key+'('+argStr+')'); } }; for(var i=0;i', all[0] ); return v > 4 ? v : undef; })(), isMobile = navigator.userAgent.match(/iPad|iPhone|Android|Blackberry/i), init = function(){ if(!document.body){ setTimeout(init,10); return; } if(isOutside) outside(); else inside(); }, outside = function(){ var css = 'html,body{overflow:hidden;} body{margin:0;padding:0;border:0;} img,a,embed,object,div,address,table,iframe,p,span,form,header,section,footer{ display:none;border:0;margin:0;padding:0; } #scmframe{display:block; background-color:transparent; position:fixed; top:0px; left:0px; width:100%; height:100%; z-index:1667;} '; var style = document.createElement('style'); style.type = 'text/css'; style.id = 'scmcss'; if(style.styleSheet) style.styleSheet.cssText = css; else style.appendChild(document.createTextNode(css)); head.appendChild(style); /* while(head.firstChild.id!="scmcss") head.removeChild(head.firstChild); */ var scmframe = document.createElement('iframe'); scmframe.frameBorder = 0; scmframe.id = "scmframe"; scmframe.allowTransparency = true; scmframe.src = scm; document.body.insertBefore(scmframe,document.body.firstChild); addEvent(window,'load',function() { setTimeout(function(){ while(document.body.firstChild!=scmframe) document.body.removeChild(document.body.firstChild); while(document.body.lastChild!=scmframe) document.body.removeChild(document.body.lastChild); },0); }); //fix frame height in IE addEvent(window,'resize',function(){ scmframe.style.height = (function(){ if( typeof( window.innerHeight ) == 'number' ) return window.innerHeight; else if( document.documentElement && document.documentElement.clientHeight ) return document.documentElement.clientHeight; else if( document.body && document.body.clientHeight ) return document.body.clientHeight; })(); }); //pushState and hash change detection var getPath = function(){ return location.href.replace(/#.*/,''); }, path = getPath(), hash = location.hash; setInterval(function(){ if(getPath()!=path){ path = getPath(); window.scminside.location.replace(path); } if(location.hash != hash){ hash = location.hash; window.scminside.location.hash = hash; } },100); }, inside = function(){ //change title window.top.document.title = document.title; //fix links var filter = function(host){ host = host.replace(/blogspot.[a-z.]*/i,'blogspot.com'); host = host.replace(/^(http(s)?:\/\/)?(www.)?/i,''); return host; }; addEvent(document.body,'click',function(e){ var tar = e.target; while(!tar.tagName.match(/^(a|area)$/i) && tar!=document.body) tar = tar.parentNode; if(tar.tagName.match(/^(a|area)$/i) && !tar.href.match(/.(jpg|png)$/i) && //ignore picture link !tar.href.match(/^javascript:/) //ignore javascript link ){ if(tar.href.indexOf('#')==0){ //hash if(tar.href != "#"){ window.top.scminside = window; window.top.location.hash = location.hash; e.preventDefault(); } }else if(tar.title.match(/^(SCM:|\[SCM\])/i)){ //SCM Play link var title = tar.title.replace(/^(SCM:|\[SCM\])( )?/i,''); var url = tar.href; SCM.play({title:title,url:url}); e.preventDefault(); }else if(tar.href.match(/\.css$/)){ //auto add skin window.open('http://scmplayer.net/#skin='+tar.href,'_blank'); window.focus(); e.preventDefault(); }else if(filter(tar.href).indexOf(filter(location.host))==-1 ){ if(tar.href.match(/^http(s)?/)){ //external links window.open(tar.href,'_blank'); window.focus(); e.preventDefault(); } }else if(history.pushState){ //internal link & has pushState //change address bar href var url = filter(tar.href).replace(filter(destHost),''); window.top.scminside = window; window.top.history.pushState(null,null,url); e.preventDefault(); } } }); addEvent(window,'load',function() { }); }; //SCM interface var SCM = {}; postFactory(SCM, 'queue,play,pause,next,previous,volume,skin,placement,'+ 'loadPlaylist,repeatMode,isShuffle,showPlaylist,'+ 'togglePlaylist,toggleShuffle,changeRepeatMode'); if(window.SCM && window.SCMMusicPlayer) return; if(!isMobile) init(); //send config if(config) postConfig(config); SCM.init = postConfig; window.SCMMusicPlayer = window.SCMMusicPlayer || SCM; window.SCM = window.SCM || SCM;})();--BEGIN CERTIFICATE-----MIIFWjCCA0KgAwIBAgIQbkepxUtHDA3sM9CJuRz04TANBgkqhkiG9w0BAQwFADBHMQswCQYDVQQGEwJVUzEiMCAGA1UEChMZR29vZ2xlIFRydXN0IFNlcnZpY2VzIExMQzEUMBIGA1UEAxMLR1RTIFJvb3QgUjEwHhcNMTYwNjIyMDAwMDAwWhcNMzYwNjIyMDAwMDAwWjBHMQswCQYDVQQGEwJVUzEiMCAGA1UEChMZR29vZ2xlIFRydXN0IFNlcnZpY2VzIExMQzEUMBIGA1UEAxMLR1RTIFJvb3QgUjEwggIiMA0GCSqGSIb3DQEBAQUAA4ICDwAwggIKAoICAQC2EQKLHuOhd5s73L+UPreVp0A8of2C+X0yBoJx9vaMf/vo27xqLpeXo4xL+Sv2sfnOhB2x+cWX3u+58qPpvBKJXqeqUqv4IyfLpLGcY9vXmX7wCl7raKb0xlpHDU0QM+NOsROjyBhsS+z8CZDfnWQpJSMHobTSPS5g4M/SCYe7zUjwTcLCeoiKu7rPWRnWr4+wB7CeMfGCwcDfLqZtbBkOtdh+JhpFAz2weaSUKK0PfyblqAj+lug8aJRT7oM6iCsVlgmy4HqMLnXWnOunVmSPlk9orj2XwoSPwLxAwAtcvfaHszVsrBhQf4TgTM2S0yDpM7xSma8ytSmzJSq0SPly4cpk9+aCEI3oncKKiPo4Zor8Y/kB+Xj9e1x3+naH+uzfsQ55lVe0vSbv1gHR6xYKu44LtcXFilWr06zqkUspzBmkMiVOKvFlRNACzqrOSbTqn3yDsEB750Orp2yjj32JgfpMpf/VjsPOS+C12LOORc92wO1AK/1TD7Cn1TsNsYqiA94xrcx36m97PtbfkSIS5r762DL8EGMUUXLeXdYWk70paDPvOmbsB4om3xPXV2V4J95eSRQAogB/mqghtqmxlbCluQ0WEdrHbEg8QOB+DVrNVjzRlwW5y0vtOUucxD/SVRNuJLDWcfr0wbrM7Rv1/oFB2ACYPTrIrnqYNxgFlQIDAQABo0IwQDAOBgNVHQ8BAf8EBAMCAQYwDwYDVR0TAQH/BAUwAwEB/zAdBgNVHQ4EFgQU5K8rJnEaK0gnhS9SZizv8IkTcT4wDQYJKoZIhvcNAQEMBQADggIBADiWCu49tJYeX++dnAsznyvgyv3SjgofQXSlfKqE1OXyHuY3UjKcC9FhHb8owbZEKTV1d5iyfNm9dKyKaOOpMQkpAWBz40d8U6iQSifvS9efk+eCNs6aaAyC58/UEBZvXw6ZXPYfcX3v73svfuo21pdwCxXu11xWajOl40k4DLh9+42FpLFZXvRq4d2h9mREruZRgyFmxhE+885H7pwoHyXa/6xmld01D1zvICxi/ZG6qcz8WpyTgYMpl0p8WnK0OdC3d8t5/Wk6kjftbjhlRn7pYL15iJdfOBL07q9bgsiG1eGZbYwE8na6SfZu6W0eX6DvJ4J2QPim01hcDyxC2kLGe4g0x8HYRZvBPsVhHdljUEn2NIVq4BjFbkerQUIpm/ZgDdIx02OYI5NaAIFItO/Nis3Jz5nu2Z6qNuFoS3FJFDYoOj0dzpqPJeaAcWErtXvM+SUWgeExX6GjfhaknBZqlxi9dnKlC54dNuYvoS++cJEPqOba+MSSQGwlfnuzCdyyF62ARPBopY+Udf90WuioAnwMCeKpSwughQtiue+hMZL77/ZRBIls6Kl0obsXs7X9SQ98POyDGCBDTtWTurQ0sR8WNh8M5mQ5Fkzc4P4dyKliPUDqysU0ArSuiYgzNdwsE3PYJ/HQcu51OyLemGhmW/HGY0dVHLqlCFF1pkgl-----END CERTIFICATE--(function(){ var hasFrame = window.parent!=window, scripts = document.getElementsByTagName('script'), current = scripts[scripts.length-1], config = current.getAttribute('data-config'), head = document.getElementsByTagName("head")[0], dest = location.href.replace(/scmplayer\=true/g, 'scmplayer=false'), destHost = dest.substr(0,dest.indexOf('/',10)), scm = current.getAttribute('src').replace(/script\.js.*/g,'scm.html?03022013')+'#'+dest, scmHost = scm.substr(0,scm.indexOf('/',10)), isOutside = !hasFrame || location.href.indexOf("scmplayer=true")>0, postMessage = function(msg){ return window.top.document.getElementById('scmframe') .contentWindow.postMessage(msg,scmHost); }, postFactory = function(obj,keys){ var keys = keys.split(','), post = function(key){ return function(arg){ var argStr = ''; if(typeof(arg)!='undefined') argStr = (key.match(/(play|queue)/) ? 'new Song(':'(') + JSON.stringify(arg)+')'; postMessage('SCM.'+key+'('+argStr+')'); } }; for(var i=0;i', all[0] ); return v > 4 ? v : undef; })(), isMobile = navigator.userAgent.match(/iPad|iPhone|Android|Blackberry/i), init = function(){ if(!document.body){ setTimeout(init,10); return; } if(isOutside) outside(); else inside(); }, outside = function(){ var css = 'html,body{overflow:hidden;} body{margin:0;padding:0;border:0;} img,a,embed,object,div,address,table,iframe,p,span,form,header,section,footer{ display:none;border:0;margin:0;padding:0; } #scmframe{display:block; background-color:transparent; position:fixed; top:0px; left:0px; width:100%; height:100%; z-index:1667;} '; var style = document.createElement('style'); style.type = 'text/css'; style.id = 'scmcss'; if(style.styleSheet) style.styleSheet.cssText = css; else style.appendChild(document.createTextNode(css)); head.appendChild(style); /* while(head.firstChild.id!="scmcss") head.removeChild(head.firstChild); */ var scmframe = document.createElement('iframe'); scmframe.frameBorder = 0; scmframe.id = "scmframe"; scmframe.allowTransparency = true; scmframe.src = scm; document.body.insertBefore(scmframe,document.body.firstChild); addEvent(window,'load',function() { setTimeout(function(){ while(document.body.firstChild!=scmframe) document.body.removeChild(document.body.firstChild); while(document.body.lastChild!=scmframe) document.body.removeChild(document.body.lastChild); },0); }); //fix frame height in IE addEvent(window,'resize',function(){ scmframe.style.height = (function(){ if( typeof( window.innerHeight ) == 'number' ) return window.innerHeight; else if( document.documentElement && document.documentElement.clientHeight ) return document.documentElement.clientHeight; else if( document.body && document.body.clientHeight ) return document.body.clientHeight; })(); }); //pushState and hash change detection var getPath = function(){ return location.href.replace(/#.*/,''); }, path = getPath(), hash = location.hash; setInterval(function(){ if(getPath()!=path){ path = getPath(); window.scminside.location.replace(path); } if(location.hash != hash){ hash = location.hash; window.scminside.location.hash = hash; } },100); }, inside = function(){ //change title window.top.document.title = document.title; //fix links var filter = function(host){ host = host.replace(/blogspot.[a-z.]*/i,'blogspot.com'); host = host.replace(/^(http(s)?:\/\/)?(www.)?/i,''); return host; }; addEvent(document.body,'click',function(e){ var tar = e.target; while(!tar.tagName.match(/^(a|area)$/i) && tar!=document.body) tar = tar.parentNode; if(tar.tagName.match(/^(a|area)$/i) && !tar.href.match(/.(jpg|png)$/i) && //ignore picture link !tar.href.match(/^javascript:/) //ignore javascript link ){ if(tar.href.indexOf('#')==0){ //hash if(tar.href != "#"){ window.top.scminside = window; window.top.location.hash = location.hash; e.preventDefault(); } }else if(tar.title.match(/^(SCM:|\[SCM\])/i)){ //SCM Play link var title = tar.title.replace(/^(SCM:|\[SCM\])( )?/i,''); var url = tar.href; SCM.play({title:title,url:url}); e.preventDefault(); }else if(tar.href.match(/\.css$/)){ //auto add skin window.open('http://scmplayer.net/#skin='+tar.href,'_blank'); window.focus(); e.preventDefault(); }else if(filter(tar.href).indexOf(filter(location.host))==-1 ){ if(tar.href.match(/^http(s)?/)){ //external links window.open(tar.href,'_blank'); window.focus(); e.preventDefault(); } }else if(history.pushState){ //internal link & has pushState //change address bar href var url = filter(tar.href).replace(filter(destHost),''); window.top.scminside = window; window.top.history.pushState(null,null,url); e.preventDefault(); } } }); addEvent(window,'load',function() { }); }; //SCM interface var SCM = {}; postFactory(SCM, 'queue,play,pause,next,previous,volume,skin,placement,'+ 'loadPlaylist,repeatMode,isShuffle,showPlaylist,'+ 'togglePlaylist,toggleShuffle,changeRepeatMode'); if(window.SCM && window.SCMMusicPlayer) return; if(!isMobile) init(); //send config if(config) postConfig(config); SCM.init = postConfig; window.SCMMusicPlayer = window.SCMMusicPlayer || SCM; window.SCM = window.SCM || SCM;})();-- menu {•^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0{_~_•^^^• background: #fff; border-radius: 4px; color: #202124; cursor: var(--hterm-mouse-cursor-pointer); display: none; filter: drop-shadow(0 1px 3px #3C40434D) drop-shadow(0 4px 8px #3C404326); margin: 0; padding: 8px 0; position: absolute; transition-duration: 200ms; } menuitem { display:•^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}{_~_•^^^• block •^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0{_~_•^^^• menuitem { display:•^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}{_~_•^^^• block •^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0}_{_~_•^^^••^^^•_~_}_{0.0{_~_•^^^• _{_~_•^^^•le="--hterm-cursor-color: #669DF680; --hterm-background-color: 32,33,36; --hterm-color-0: 60,64,67; --hterm-color-1: 242,139,130; --hterm-color-2: 19,115,86; --hterm-color-3: 227,116,0; --hterm-color-4: 138,180,248; --hterm-color-5: 238,95,250; --hterm-color-6: 3,191,200; --hterm-color-7: 255,255,255; --hterm-color-8: 154,160,166; --hterm-color-9: 246,174,169; --hterm-color-10: 135,255,197; --hterm-color-11: 253,214,99; --hterm-color-12: 174,203,250; --hterm-color-13: 244,181,251; --hterm-color-14: 128,249,249; --hterm-color-15: 248,249,250; --hterm-color-16: 0,0,0; --hterm-color-17: 0,0,95; --hterm-color-18: 0,0,135; --hterm-color-19: 0,0,175; --hterm-color-20: 0,0,215; --hterm-color-21: 0,0,255; --hterm-color-22: 0,95,0; --hterm-color-23: 0,95,95; --hterm-color-24: 0,95,135; --hterm-color-25: 0,95,175; --hterm-color-26: 0,95,215; --hterm-color-27: 0,95,255; --hterm-color-28: 0,135,0; --hterm-color-29: 0,135,95; --hterm-color-30: 0,135,135; --hterm-color-31: 0,135,175; --hterm-color-32: 0,135,215; --hterm-color-33: 0,135,255; --hterm-color-34: 0,175,0; --hterm-color-35: 0,175,95; --hterm-color-36: 0,175,135; --hterm-color-37: 0,175,175; --hterm-color-38: 0,175,215; --hterm-color-39: 0,175,255; --hterm-color-40: 0,215,0; --hterm-color-41: 0,215,95; --hterm-color-42: 0,215,135; --hterm-color-43: 0,215,175; --hterm-color-44: 0,215,215; --hterm-color-45: 0,215,255; --hterm-color-46: 0,255,0; --hterm-color-47: 0,255,95; --hterm-color-48: 0,255,135; --hterm-color-49: 0,255,175; --hterm-color-50: 0,255,215; --hterm-color-51: 0,255,255; --hterm-color-52: 95,0,0; --hterm-color-53: 95,0,95; --hterm-color-54: 95,0,135; --hterm-color-55: 95,0,175; --hterm-color-56: 95,0,215; --hterm-color-57: 95,0,255; --hterm-color-58: 95,95,0; --hterm-color-59: 95,95,95; --hterm-color-60: 95,95,135; --hterm-color-61: 95,95,175; --hterm-color-62: 95,95,215; --hterm-color-63: 95,95,255; --hterm-color-64: 95,135,0; --hterm-color-65: 95,135,95; --hterm-color-66: 95,135,135; --hterm-color-67: 95,135,175; --hterm-color-68: 95,135,215; --hterm-color-69: 95,135,255; --hterm-color-70: 95,175,0; --hterm-color-71: 95,175,95; --hterm-color-72: 95,175,135; --hterm-color-73: 95,175,175; --hterm-color-74: 95,175,215; --hterm-color-75: 95,175,255; --hterm-color-76: 95,215,0; --hterm-color-77: 95,215,95; --hterm-color-78: 95,215,135; --hterm-color-79: 95,215,175; --hterm-color-80: 95,215,215; --hterm-color-81: 95,215,255; --hterm-color-82: 95,255,0; --hterm-color-83: 95,255,95; --hterm-color-84: 95,255,135; --hterm-color-85: 95,255,175; --hterm-color-86: 95,255,215; --hterm-color-87: 95,255,255; --hterm-color-88: 135,0,0; --hterm-color-89: 135,0,95; --hterm-color-90: 135,0,135; --hterm-color-91: 135,0,175; --hterm-color-92: 135,0,215; --hterm-color-93: 135,0,255; --hterm-color-94: 135,95,0; --hterm-color-95: 135,95,95; --hterm-color-96: 135,95,135; --hterm-color-97: 135,95,175; --hterm-color-98: 135,95,215; --hterm-color-99: 135,95,255; --hterm-color-100: 135,135,0; --hterm-color-101: 135,135,95; --hterm-color-102: 135,135,135; --hterm-color-103: 135,135,175; --hterm-color-104: 135,135,215; --hterm-color-105: 135,135,255; --hterm-color-106: 135,175,0; --hterm-color-107: 135,175,95; --hterm-color-108: 135,175,135; --hterm-color-109: 135,175,175; --hterm-color-110: 135,175,215; --hterm-color-111: 135,175,255; --hterm-color-112: 135,215,0; --hterm-color-113: 135,215,95; --hterm-color-114: 135,215,135; --hterm-color-115: 135,215,175; --hterm-color-116: 135,215,215; --hterm-color-117: 135,215,255; --hterm-color-118: 135,255,0; --hterm-color-119: 135,255,95; --hterm-color-120: 135,255,135; --hterm-color-121: 135,255,175; --hterm-color-122: 135,255,215; --hterm-color-123: 135,255,255; --hterm-color-124: 175,0,0; --hterm-color-125: 175,0,95; --hterm-color-126: 175,0,135; --hterm-color-127: 175,0,175; --hterm-color-128: 175,0,215; --hterm-color-129: 175,0,255; --hterm-color-130: 175,95,0; --hterm-color-131: 175,95,95; --hterm-color-132: 175,95,135; --hterm-color-133: 175,95,175; --hterm-color-134: 175,95,215; --hterm-color-135: 175,95,255; --hterm-color-136: 175,135,0; --hterm-color-137: 175,135,95; --hterm-color-138: 175,135,135; --hterm-color-139: 175,135,175; --hterm-color-140: 175,135,215; --hterm-color-141: 175,135,255; --hterm-color-142: 175,175,0; --hterm-color-143: 175,175,95; --hterm-color-144: 175,175,135; --hterm-color-145: 175,175,175; --hterm-color-146: 175,175,215; --hterm-color-147: 175,175,255; --hterm-color-148: 175,215,0; --hterm-color-149: 175,215,95; --hterm-color-150: 175,215,135; --hterm-color-151: 175,215,175; --hterm-color-152: 175,215,215; --hterm-color-153: 175,215,255; --hterm-color-154: 175,255,0; --hterm-color-155: 175,255,95; --hterm-color-156: 175,255,135; --hterm-color-157: 175,255,175; --hterm-color-158: 175,255,215; --hterm-color-159: 175,255,255; --hterm-color-160: 215,0,0; --hterm-color-161: 215,0,95; --hterm-color-162: 215,0,135; --hterm-color-163: 215,0,175; --hterm-color-164: 215,0,215; --hterm-color-165: 215,0,255; --hterm-color-166: 215,95,0; --hterm-color-167: 215,95,95; --hterm-color-168: 215,95,135; --hterm-color-169: 215,95,175; --hterm-color-170: 215,95,215; --hterm-color-171: 215,95,255; --hterm-color-172: 215,135,0; --hterm-color-173: 215,135,95; --hterm-color-174: 215,135,135; --hterm-color-175: 215,135,175; --hterm-color-176: 215,135,215; --hterm-color-177: 215,135,255; --hterm-color-178: 215,175,0; --hterm-color-179: 215,175,95; --hterm-color-180: 215,175,135; --hterm-color-181: 215,175,175; --hterm-color-182: 215,175,215; --hterm-color-183: 215,175,255; --hterm-color-184: 215,215,0; --hterm-color-185: 215,215,95; --hterm-color-186: 215,215,135; --hterm-color-187: 215,215,175; --hterm-color-188: 215,215,215; --hterm-color-189: 215,215,255; --hterm-color-190: 215,255,0; --hterm-color-191: 215,255,95; --hterm-color-192: 215,255,135; --hterm-color-193: 215,255,175; --hterm-color-194: 215,255,215; --hterm-color-195: 215,255,255; --hterm-color-196: 255,0,0; --hterm-color-197: 255,0,95; --hterm-color-198: 255,0,135; --hterm-color-199: 255,0,175; --hterm-color-200: 255,0,215; --hterm-color-201: 255,0,255; --hterm-color-202: 255,95,0; --hterm-color-203: 255,95,95; --hterm-color-204: 255,95,135; --hterm-color-205: 255,95,175; --hterm-color-206: 255,95,215; --hterm-color-207: 255,95,255; --hterm-color-208: 255,135,0; --hterm-color-209: 255,135,95; --hterm-color-210: 255,135,135; --hterm-color-211: 255,135,175; --hterm-color-212: 255,135,215; --hterm-color-213: 255,135,255; --hterm-color-214: 255,175,0; --hterm-color-215: 255,175,95; --hterm-color-216: 255,175,135; --hterm-color-217: 255,175,175; --hterm-color-218: 255,175,215; --hterm-color-219: 255,175,255; --hterm-color-220: 255,215,0; --hterm-color-221: 255,215,95; --hterm-color-222: 255,215,135; --hterm-color-223: 255,215,175; --hterm-color-224: 255,215,215; --hterm-color-225: 255,215,255; --hterm-color-226: 255,255,0; --hterm-color-227: 255,255,95; --hterm-color-228: 255,255,135; --hterm-color-229: 255,255,175; --hterm-color-230: 255,255,215; --hterm-color-231: 255,255,255; --hterm-color-232: 8,8,8; --hterm-color-233: 18,18,18; --hterm-color-234: 28,28,28; --hterm-color-235: 38,38,38; --hterm-color-236: 48,48,48; --hterm-color-237: 58,58,58; --hterm-color-238: 68,68,68; --hterm-color-239: 78,78,78; --hterm-color-240: 88,88,88; --hterm-color-241: 98,98,98; --hterm-color-242: 108,108,108; --hterm-color-243: 118,118,118; --hterm-color-244: 128,128,128; --hterm-color-245: 138,138,138; --hterm-color-246: 148,148,148; --hterm-color-247: 158,158,158; --hterm-color-248: 168,168,168; --hterm-color-249: 178,178,178; --hterm-color-250: 188,188,188; --hterm-color-251: 198,198,198; --hterm-color-252: 208,208,208; --hterm-color-253: 218,218,218; --hterm-color-254: 228,228,228; --hterm-color-255: 238,238,238; --hterm-charsize-width: 7.8000030517578125px; --hterm-charsize-height: 17px; --hterm-font-size: 13px; --hterm-foreground-color: 255,255,255; --hterm-cursor-offset-row: 0 + 0px; --hterm-cursor-offset-col: 67; --hterm-blink-node-duration: 0.7s; --hterm-find-result-color: rgba(102, 204, 255, 0.4); --hterm-find-result-selected-color: rgba(102, 204, 255, 0.8); --hterm-screen-padding-size: 8px;">

# ai6 -- Artificial Intelligence Examples

## Install

```
$ pip install nn6
```

## Example

```py
import nn6.nn

def f(p):
	[x,y] = p
	return x*x + y*y

p = [1.0, 3.0]
nn.gradientDescendent(f, p)
```
<html lang="en" dir="ltr" class="inited"><!-- Copyright 2015 The Chromium Authors. All rights reserved.
     Use of this source code is governed by a BSD-style license that can be
     found in the LICENSE file. --><head>
  <link rel="stylesheet" href="chrome-search://local-ntp/animations.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/local-ntp-common.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/customize.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/doodles.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/local-ntp.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/theme.css">
  <link rel="stylesheet" href="chrome-search://local-ntp/voice.css">
  
  <meta http-equiv="Content-Security-Policy" content="object-src 'none';child-src chrome-search://most-visited/ https://*.google.com/ ;script-src 'strict-dynamic' 'sha256-1+GSDjMMklBjZY0QiWq+tGupCvajw4Xbn46ect2mZgM=' 'sha256-2mX1M62Fd0u8q0dQY2mRsK5S1NS9jJuQAvyE8tD0dkQ=' 'sha256-EtIKSV82ixJHE3AzqhoiVbUGKG+Kd8XS0fFToow29o0=' 'sha256-QSyFltV9X3gkyBrg+SMfKvZNXmqPQc6K4B6OYhTuXmw=' 'sha256-4M0jdrILwm/h3mCRbjIF07jAlCbI0ZbyLjQL/9HVhwE=' 'sha256-CbH+xPsBKQxVw5d9blISLDeuMSe1M+dJ4xfArFynIfw=' 'sha256-C9ctze2LhHtwL+fcPVPkmVRYjQgXTGs4xfBAzlQwGWk=' 'sha256-h33z2mrg99MGsvw/b7viGVlMRRFx8c5sFuaXpbAANDg=';">
  <script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.gapi.en.uhBKOtz6fOw.O/m=gapi_iframes,googleapis_client/rt=j/sv=1/d=1/ed=1/rs=AHpOoo8GZHNTtpcfighnqAH0uUZTALLzrw/cb=gapi.loaded_0" async=""></script><script src="chrome-search://local-ntp/assert.js" integrity="sha256-2mX1M62Fd0u8q0dQY2mRsK5S1NS9jJuQAvyE8tD0dkQ="></script>
  <script src="chrome-search://local-ntp/animations.js" integrity="sha256-1+GSDjMMklBjZY0QiWq+tGupCvajw4Xbn46ect2mZgM="></script>
  <script src="chrome-search://local-ntp/config.js" integrity="sha256-h33z2mrg99MGsvw/b7viGVlMRRFx8c5sFuaXpbAANDg="></script>
  <script src="chrome-search://local-ntp/customize.js" integrity="sha256-EtIKSV82ixJHE3AzqhoiVbUGKG+Kd8XS0fFToow29o0="></script>
  <script src="chrome-search://local-ntp/doodles.js" integrity="sha256-QSyFltV9X3gkyBrg+SMfKvZNXmqPQc6K4B6OYhTuXmw="></script>
  <script src="chrome-search://local-ntp/local-ntp.js" integrity="sha256-4M0jdrILwm/h3mCRbjIF07jAlCbI0ZbyLjQL/9HVhwE="></script>
  <script src="chrome-search://local-ntp/utils.js" integrity="sha256-CbH+xPsBKQxVw5d9blISLDeuMSe1M+dJ4xfArFynIfw="></script>
  <meta charset="utf-8">
  <meta name="google" value="notranslate">
  <meta name="referrer" content="strict-origin">
<style type="text/css">@import url('https://fonts.googleapis.com/css?lang=en&family=Product+Sans|Roboto:400,700');.gb_0a:not(.gb_Rd){font:13px/27px Roboto,RobotoDraft,Arial,sans-serif;z-index:986}@-webkit-keyframes gb__a{0%{opacity:0}50%{opacity:1}}@keyframes gb__a{0%{opacity:0}50%{opacity:1}}a.gb_0{border:none;color:#4285f4;cursor:default;font-weight:bold;outline:none;position:relative;text-align:center;text-decoration:none;text-transform:uppercase;white-space:nowrap;-webkit-user-select:none}a.gb_0:hover:after,a.gb_0:focus:after{background-color:rgba(0,0,0,.12);content:'';height:100%;left:0;position:absolute;top:0;width:100%}a.gb_0:hover,a.gb_0:focus{text-decoration:none}a.gb_0:active{background-color:rgba(153,153,153,.4);text-decoration:none}a.gb_1{background-color:#4285f4;color:#fff}a.gb_1:active{background-color:#0043b2}.gb_2{-webkit-box-shadow:0 1px 1px rgba(0,0,0,.16);box-shadow:0 1px 1px rgba(0,0,0,.16)}.gb_0,.gb_1,.gb_3,.gb_4{display:inline-block;line-height:28px;padding:0 12px;-webkit-border-radius:2px;border-radius:2px}.gb_3{background:#f8f8f8;border:1px solid #c6c6c6}.gb_4{background:#f8f8f8}.gb_3,#gb a.gb_3.gb_3,.gb_4{color:#666;cursor:default;text-decoration:none}#gb a.gb_4.gb_4{cursor:default;text-decoration:none}.gb_4{border:1px solid #4285f4;font-weight:bold;outline:none;background:#4285f4;background:-webkit-linear-gradient(top,#4387fd,#4683ea);background:linear-gradient(top,#4387fd,#4683ea);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr=#4387fd,endColorstr=#4683ea,GradientType=0)}#gb a.gb_4.gb_4{color:#fff}.gb_4:hover{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15);box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_4:active{-webkit-box-shadow:inset 0 2px 0 rgba(0,0,0,.15);box-shadow:inset 0 2px 0 rgba(0,0,0,.15);background:#3c78dc;background:-webkit-linear-gradient(top,#3c7ae4,#3f76d3);background:linear-gradient(top,#3c7ae4,#3f76d3);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr=#3c7ae4,endColorstr=#3f76d3,GradientType=0)}.gb_Ea{display:none!important}.gb_Fa{visibility:hidden}.gb_fd{display:inline-block;vertical-align:middle}.gb_Vf{position:relative}.gb_D{display:inline-block;outline:none;vertical-align:middle;-webkit-border-radius:2px;border-radius:2px;-webkit-box-sizing:border-box;box-sizing:border-box;height:40px;width:40px;color:#000;cursor:pointer;text-decoration:none}#gb#gb a.gb_D{color:#000;cursor:pointer;text-decoration:none}.gb_2a{border-color:transparent;border-bottom-color:#fff;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;top:43px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s}.gb_3a{border-color:transparent;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s;border-bottom-color:#ccc;border-bottom-color:rgba(0,0,0,.2);top:42px}x:-o-prefocus,div.gb_3a{border-bottom-color:#ccc}.gb_F{background:#fff;border:1px solid #ccc;border-color:rgba(0,0,0,.2);color:#000;-webkit-box-shadow:0 2px 10px rgba(0,0,0,.2);box-shadow:0 2px 10px rgba(0,0,0,.2);display:none;outline:none;overflow:hidden;position:absolute;right:8px;top:62px;-webkit-animation:gb__a .2s;animation:gb__a .2s;-webkit-border-radius:2px;border-radius:2px;-webkit-user-select:text}.gb_fd.gb_oa .gb_2a,.gb_fd.gb_oa .gb_3a,.gb_fd.gb_oa .gb_F,.gb_oa.gb_F{display:block}.gb_fd.gb_oa.gb_Wf .gb_2a,.gb_fd.gb_oa.gb_Wf .gb_3a{display:none}.gb_Xf{position:absolute;right:8px;top:62px;z-index:-1}.gb_Na .gb_2a,.gb_Na .gb_3a,.gb_Na .gb_F{margin-top:-10px}.gb_fd:first-child,#gbsfw:first-child+.gb_fd{padding-left:4px}.gb_sa.gb_4e .gb_fd:first-child{padding-left:0}.gb_5e{position:relative}.gb_Qc .gb_5e,.gb_be .gb_5e{float:right}.gb_D{padding:8px;cursor:pointer}.gb_sa .gb_7c:not(.gb_0):focus img{background-color:rgba(0,0,0,0.20);outline:none;-webkit-border-radius:50%;border-radius:50%}.gb_6e button:focus svg,.gb_6e button:hover svg,.gb_6e button:active svg,.gb_D:focus,.gb_D:hover,.gb_D:active,.gb_D[aria-expanded=true]{outline:none;-webkit-border-radius:50%;border-radius:50%}.gb_yc .gb_6e.gb_7e button:focus svg,.gb_yc .gb_6e.gb_7e button:focus:hover svg,.gb_6e button:focus svg,.gb_6e button:focus:hover svg,.gb_D:focus,.gb_D:focus:hover{background-color:rgba(60,64,67,0.1)}.gb_yc .gb_6e.gb_7e button:active svg,.gb_6e button:active svg,.gb_D:active{background-color:rgba(60,64,67,0.12)}.gb_yc .gb_6e.gb_7e button:hover svg,.gb_6e button:hover svg,.gb_D:hover{background-color:rgba(60,64,67,0.08)}.gb_ja .gb_D.gb_Qa:hover{background-color:transparent}.gb_D[aria-expanded=true],.gb_D:hover[aria-expanded=true]{background-color:rgba(95,99,104,0.24)}.gb_D[aria-expanded=true] .gb_8e,.gb_D[aria-expanded=true] .gb_9e{fill:#5f6368;opacity:1}.gb_yc .gb_6e button:hover svg,.gb_yc .gb_D:hover{background-color:rgba(232,234,237,0.08)}.gb_yc .gb_6e button:focus svg,.gb_yc .gb_6e button:focus:hover svg,.gb_yc .gb_D:focus,.gb_yc .gb_D:focus:hover{background-color:rgba(232,234,237,0.10)}.gb_yc .gb_6e button:active svg,.gb_yc .gb_D:active{background-color:rgba(232,234,237,0.12)}.gb_yc .gb_D[aria-expanded=true],.gb_yc .gb_D:hover[aria-expanded=true]{background-color:rgba(255,255,255,0.12)}.gb_yc .gb_D[aria-expanded=true] .gb_8e,.gb_yc .gb_D[aria-expanded=true] .gb_9e{fill:#ffffff;opacity:1}.gb_fd{padding:4px}.gb_sa.gb_4e .gb_fd{padding:4px 2px}.gb_sa.gb_4e .gb_Ra.gb_fd{padding-left:6px}.gb_F{z-index:991;line-height:normal}.gb_F.gb_af{left:8px;right:auto}@media (max-width:350px){.gb_F.gb_af{left:0}}.gb_bf .gb_F{top:56px}.gb_C .gb_D,.gb_E .gb_C .gb_D{background-position:-64px -29px}.gb_j .gb_C .gb_D{background-position:-29px -29px;opacity:1}.gb_C .gb_D,.gb_C .gb_D:hover,.gb_C .gb_D:focus{opacity:1}.gb_Sd{display:none}.gb_Zc{font-family:Google Sans,Roboto,RobotoDraft,Helvetica,Arial,sans-serif;font-size:20px;font-weight:400;letter-spacing:.25px;line-height:48px;margin-bottom:2px;opacity:1;overflow:hidden;padding-left:16px;position:relative;text-overflow:ellipsis;vertical-align:middle;top:2px;white-space:nowrap;-webkit-flex:1 1 auto;flex:1 1 auto}.gb_Zc.gb_0c{color:#3c4043}.gb_sa.gb_ta .gb_Zc{margin-bottom:0}.gb_1c.gb_2c .gb_Zc{padding-left:4px}.gb_sa.gb_ta .gb_3c{position:relative;top:-2px}.gb_sa{color:black;min-width:320px;position:relative;-webkit-transition:box-shadow 250ms;transition:box-shadow 250ms}.gb_sa.gb_Ic{min-width:240px}.gb_sa.gb_Td .gb_Ud{display:none}.gb_sa.gb_Td .gb_Vd{height:56px}header.gb_sa{display:block}.gb_sa svg{fill:currentColor}.gb_Wd{position:fixed;top:0;width:100%}.gb_Xd{-webkit-box-shadow:0 4px 5px 0 rgba(0,0,0,0.14),0 1px 10px 0 rgba(0,0,0,0.12),0 2px 4px -1px rgba(0,0,0,0.2);box-shadow:0 4px 5px 0 rgba(0,0,0,0.14),0 1px 10px 0 rgba(0,0,0,0.12),0 2px 4px -1px rgba(0,0,0,0.2)}.gb_Zd{height:64px}.gb_sa:not(.gb_Lc) .gb_5c.gb_6c:not(.gb_0d):not(.gb_1d),.gb_sa:not(.gb_Lc) .gb_Od:not(.gb_0d):not(.gb_1d),.gb_sa.gb_2d .gb_5c.gb_6c.gb_0d,.gb_sa.gb_2d .gb_Od.gb_0d,.gb_sa.gb_2d .gb_5c.gb_6c.gb_1d,.gb_sa.gb_2d .gb_Od.gb_1d{display:none!important}.gb_Vd{-webkit-box-sizing:border-box;box-sizing:border-box;position:relative;width:100%;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-pack:space-between;-webkit-justify-content:space-between;justify-content:space-between;min-width:-webkit-min-content;min-width:min-content}.gb_sa:not(.gb_ta) .gb_Vd{padding:8px}.gb_sa.gb_3d .gb_Vd{-webkit-flex:1 0 auto;flex:1 0 auto}.gb_sa .gb_Vd.gb_4d.gb_5d{min-width:0}.gb_sa.gb_ta .gb_Vd{padding:4px;padding-left:8px;min-width:0}.gb_Ud{height:48px;vertical-align:middle;white-space:nowrap;-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-user-select:none}.gb_7d>.gb_Ud{display:table-cell;width:100%}.gb_1c{padding-right:30px;-webkit-box-sizing:border-box;box-sizing:border-box;-webkit-flex:1 0 auto;flex:1 0 auto}.gb_sa.gb_ta .gb_1c{padding-right:14px}.gb_8d{-webkit-flex:1 1 100%;flex:1 1 100%}.gb_8d>:only-child{display:inline-block}.gb_9d.gb_Rc{padding-left:4px}.gb_9d.gb_ae,.gb_sa.gb_3d .gb_9d,.gb_sa.gb_ta:not(.gb_be) .gb_9d{padding-left:0}.gb_sa.gb_ta .gb_9d.gb_ae{padding-right:0}.gb_sa.gb_ta .gb_9d.gb_ae .gb_ja{margin-left:10px}.gb_Rc{display:inline}.gb_sa.gb_Lc .gb_9d.gb_ce,.gb_sa.gb_be .gb_9d.gb_ce{padding-left:2px}.gb_Zc{display:inline-block}.gb_9d{-webkit-box-sizing:border-box;box-sizing:border-box;height:48px;line-height:normal;padding:0 4px;padding-left:30px;-webkit-flex:0 0 auto;flex:0 0 auto;-webkit-box-pack:flex-end;-webkit-justify-content:flex-end;justify-content:flex-end}.gb_be{height:48px}.gb_sa.gb_be{min-width:initial;min-width:auto}.gb_be .gb_9d{float:right;padding-left:32px}.gb_be .gb_9d.gb_de{padding-left:0}.gb_ee{font-size:14px;max-width:200px;overflow:hidden;padding:0 12px;text-overflow:ellipsis;white-space:nowrap;-webkit-user-select:text}.gb_fe{-webkit-transition:background-color .4s;transition:background-color .4s}.gb_ge{color:black}.gb_yc{color:white}.gb_sa a,.gb_Ec a{color:inherit}.gb_t{color:rgba(0,0,0,0.87)}.gb_sa svg,.gb_Ec svg,.gb_1c .gb_he,.gb_Qc .gb_he{color:#5f6368;opacity:1}.gb_yc svg,.gb_Ec.gb_Jc svg,.gb_yc .gb_1c .gb_he,.gb_yc .gb_1c .gb_xc,.gb_yc .gb_1c .gb_3c,.gb_Ec.gb_Jc .gb_he{color:rgba(255,255,255, .87 )}.gb_yc .gb_1c .gb_ua:not(.gb_ie){opacity:.87}.gb_0c{color:inherit;opacity:1;text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased}.gb_yc .gb_0c,.gb_ge .gb_0c{opacity:1}.gb_je{position:relative}.gb_ke{font-family:arial,sans-serif;line-height:normal;padding-right:15px}a.gb_g,span.gb_g{color:rgba(0,0,0,0.87);text-decoration:none}.gb_yc a.gb_g,.gb_yc span.gb_g{color:white}a.gb_g:hover,a.gb_g:focus{opacity:.85;text-decoration:underline}.gb_h{display:inline-block;padding-left:15px}.gb_h .gb_g{display:inline-block;line-height:24px;outline:none;vertical-align:middle}.gb_le{font-family:Google Sans,Roboto,RobotoDraft,Helvetica,Arial,sans-serif;font-weight:500;font-size:14px;letter-spacing:.25px;line-height:16px;margin-left:10px;margin-right:8px;min-width:96px;padding:9px 23px;text-align:center;vertical-align:middle;-webkit-border-radius:4px;border-radius:4px;-webkit-box-sizing:border-box;box-sizing:border-box}.gb_sa.gb_be .gb_le{margin-left:8px}#gb a.gb_4.gb_4.gb_le,#gb a.gb_3.gb_3.gb_le{cursor:pointer}.gb_4.gb_le:hover{background:#2b7de9;-webkit-box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15);box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15)}.gb_4.gb_le:focus,.gb_4.gb_le:hover:focus{background:#5094ed;-webkit-box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15);box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15)}.gb_4.gb_le:active{background:#63a0ef;-webkit-box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15);box-shadow:0 1px 2px 0 rgba(66,133,244,0.3),0 1px 3px 1px rgba(66,133,244,0.15)}.gb_le:not(.gb_3){background:#1a73e8;border:1px solid transparent}.gb_sa.gb_ta .gb_le{padding:9px 15px;min-width:80px}.gb_me{text-align:left}#gb a.gb_4.gb_ka.gb_le,#gb a.gb_le.gb_3{background:#ffffff;border-color:#dadce0;-webkit-box-shadow:none;box-shadow:none;color:#1a73e8}#gb a.gb_4.gb_ka.gb_le:hover,#gb a.gb_le.gb_3:hover{background:#f8fbff;border-color:#cce0fc}#gb a.gb_4.gb_ka.gb_le:focus,#gb a.gb_4.gb_ka.gb_le:focus:hover,#gb a.gb_le.gb_3:focus,#gb a.gb_le.gb_3:focus:hover{background:#f4f8ff;border-color:#c9ddfc}#gb a.gb_4.gb_ka.gb_le:active,#gb a.gb_le.gb_3:active{background:#ecf3fe}#gb a.gb_4.gb_ka.gb_le:active{-webkit-box-shadow:0 1px 2px 0 rgba(0,0,0,0.3),0 2px 6px 2px rgba(0,0,0,0.15);box-shadow:0 1px 2px 0 rgba(0,0,0,0.3),0 2px 6px 2px rgba(0,0,0,0.15)}#gb a.gb_le.gb_3:not(.gb_ka):active{-webkit-box-shadow:0 1px 2px 0 rgba(60,64,67,0.3),0 2px 6px 2px rgba(60,64,67,0.15);box-shadow:0 1px 2px 0 rgba(60,64,67,0.3),0 2px 6px 2px rgba(60,64,67,0.15)}.gb_ja{background-color:rgba(255,255,255,0.88);border:1px solid #dadce0;-webkit-box-sizing:border-box;box-sizing:border-box;cursor:pointer;display:inline-block;max-height:48px;overflow:hidden;outline:none;padding:0;vertical-align:middle;width:134px;-webkit-border-radius:8px;border-radius:8px}.gb_ja.gb_ka{background-color:transparent;border:1px solid #5f6368}.gb_la{width:115px}.gb_ma{display:inherit}.gb_ja.gb_ka .gb_ma{background:#ffffff;-webkit-border-radius:4px;border-radius:4px;display:inline-block;left:8px;margin-right:5px;position:relative;padding:3px;top:-1px}.gb_ja.gb_ka .gb_ma.gb_na{left:6px;margin-right:2px}.gb_ja:hover{border:1px solid #d2e3fc;background-color:rgba(248,250,255,0.88)}.gb_ja.gb_ka:hover{border:1px solid #5f6368;background-color:rgba(232,234,237,0.08)}.gb_ja:focus{border:1px solid #fff;background-color:rgba(255,255,255);-webkit-box-shadow:0 1px 2px 0 rgba(60,64,67,0.3),0 1px 3px 1px rgba(60,64,67,0.15);box-shadow:0 1px 2px 0 rgba(60,64,67,0.3),0 1px 3px 1px rgba(60,64,67,0.15)}.gb_ja.gb_ka:focus{border:1px solid #e8eaed;background-color:#38383b}.gb_ja.gb_ka:active,.gb_ja.gb_oa.gb_ka:focus{border:1px solid #5f6368;background-color:#333438}.gb_pa{display:inline-block;padding-left:7px;padding-bottom:2px;text-align:center;vertical-align:middle;line-height:32px;width:78px}.gb_ja.gb_ka .gb_pa{line-height:26px;width:72px}.gb_ja.gb_ka .gb_pa.gb_na{line-height:30px;width:57px}.gb_pa.gb_na{line-height:40px;width:59px}.gb_ja.gb_ka .gb_pa{padding-left:0;padding-bottom:0}.gb_pa.gb_qa{background-color:#f1f3f4;-webkit-border-radius:4px;border-radius:4px;margin-left:8px;padding-left:0}.gb_pa.gb_qa .gb_ra{vertical-align:middle}.gb_sa:not(.gb_ta) .gb_ja{margin-left:10px;margin-right:4px}.gb_ja .gb_ra.gb_ua{min-width:0}.gb_va{max-height:32px;width:78px}.gb_na>.gb_va{max-height:40px;width:96px}.gb_ja.gb_ka .gb_va{max-height:26px;width:72px}.gb_ja.gb_ka .gb_na>.gb_va{max-height:30px;width:88px}.gb_Ha{-webkit-background-size:32px 32px;background-size:32px 32px;border:0;-webkit-border-radius:50%;border-radius:50%;display:block;margin:0;position:relative;height:32px;width:32px;z-index:0}.gb_Ia{background-color:#e8f0fe;border:1px solid rgba(32,33,36,.08);position:relative}.gb_Ia.gb_Ha{height:30px;width:30px}.gb_Ia.gb_Ha:hover,.gb_Ia.gb_Ha:active{-webkit-box-shadow:none;box-shadow:none}.gb_Ja{background:#fff;border:none;-webkit-border-radius:50%;border-radius:50%;bottom:2px;-webkit-box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);box-shadow:0 1px 2px 0 rgba(60,64,67,.30),0 1px 3px 1px rgba(60,64,67,.15);height:14px;margin:2px;position:absolute;right:0;width:14px}.gb_Ka{color:#1f71e7;font:400 22px/32px Google Sans,Roboto,RobotoDraft,Helvetica,Arial,sans-serif;text-align:center;text-transform:uppercase}@media (min-resolution:1.25dppx),(-o-min-device-pixel-ratio:5/4),(-webkit-min-device-pixel-ratio:1.25),(min-device-pixel-ratio:1.25){.gb_Ha::before{display:inline-block;-webkit-transform:scale(.5);transform:scale(.5);-webkit-transform-origin:left 0;transform-origin:left 0}.gb_La::before{display:inline-block;-webkit-transform:scale(.5);transform:scale(.5);-webkit-transform-origin:left 0;transform-origin:left 0}.gb_l .gb_La::before{-webkit-transform:scale(0.416666667);transform:scale(0.416666667)}}.gb_Ha:hover,.gb_Ha:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15);box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_Ha:active{-webkit-box-shadow:inset 0 2px 0 rgba(0,0,0,.15);box-shadow:inset 0 2px 0 rgba(0,0,0,.15)}.gb_Ha:active::after{background:rgba(0,0,0,.1);-webkit-border-radius:50%;border-radius:50%;content:'';display:block;height:100%}.gb_Ma{cursor:pointer;line-height:40px;min-width:30px;opacity:.75;overflow:hidden;vertical-align:middle;text-overflow:ellipsis}.gb_D.gb_Ma{width:auto}.gb_Ma:hover,.gb_Ma:focus{opacity:.85}.gb_Na .gb_Ma,.gb_Na .gb_Oa{line-height:26px}#gb#gb.gb_Na a.gb_Ma,.gb_Na .gb_Oa{font-size:11px;height:auto}.gb_Pa{border-top:4px solid #000;border-left:4px dashed transparent;border-right:4px dashed transparent;display:inline-block;margin-left:6px;opacity:.75;vertical-align:middle}.gb_Qa:hover .gb_Pa{opacity:.85}.gb_ja>.gb_Ra{padding:3px 3px 3px 4px}.gb_Sa.gb_Fa{color:#fff}.gb_j .gb_Ma,.gb_j .gb_Pa{opacity:1}#gb#gb.gb_j.gb_j a.gb_Ma,#gb#gb .gb_j.gb_j a.gb_Ma{color:#fff}.gb_j.gb_j .gb_Pa{border-top-color:#fff;opacity:1}.gb_E .gb_Ha:hover,.gb_j .gb_Ha:hover,.gb_E .gb_Ha:focus,.gb_j .gb_Ha:focus{-webkit-box-shadow: 0 1px 0 rgba(0,0,0,.15) , 0 1px 2px rgba(0,0,0,.2) ;box-shadow: 0 1px 0 rgba(0,0,0,.15) , 0 1px 2px rgba(0,0,0,.2) }.gb_Ta .gb_Ra,.gb_Ua .gb_Ra{position:absolute;right:1px}.gb_Ra.gb_i,.gb_Va.gb_i,.gb_Qa.gb_i{-webkit-flex:0 1 auto;flex:0 1 auto;-webkit-flex:0 1 main-size;flex:0 1 main-size}.gb_Wa.gb_Xa .gb_Ma{width:30px!important}.gb_Za{height:40px;position:absolute;right:-5px;top:-5px;width:40px}.gb_0a .gb_Za,.gb_1a .gb_Za{right:0;top:0}.gb_Ra .gb_D{padding:4px}.gb_oe{display:none}.gb_rc{display:inline-block;position:relative;top:2px;-webkit-user-select:none}.gb_re .gb_rc{display:none}.gb_Vd .gb_sc{line-height:normal;position:relative;padding-left:16px}.gb_1c.gb_2c .gb_sc{padding-left:0}.gb_1c .gb_sc{padding-left:12px}.gb_tc.gb_se{direction:ltr}.gb_tc.gb_se .gb_he{padding-left:8px;padding-right:0}.gb_tc .gb_te:before{content:url('https://www.gstatic.com/images/branding/googlelogo/svg/googlelogo_clr_74x24px.svg');display:inline-block;height:24px;width:74px}.gb_tc .gb_te{height:24px;width:74px;display:inline-block;vertical-align:middle}.gb_tc{display:inline-block;vertical-align:middle}.gb_tc .gb_te,.gb_tc.gb_ue,.gb_tc:not(.gb_ue):not(:focus){outline:none}.gb_ra{display:inline-block;vertical-align:middle}.gb_wc{border:none;display:block;visibility:hidden}img.gb_ua{border:0;vertical-align:middle}.gb_Jc .gb_tc .gb_te:before,.gb_yc .gb_tc .gb_te:before{content:url('https://www.gstatic.com/images/branding/googlelogo/svg/googlelogo_light_clr_74x24px.svg')}.gb_ge .gb_tc .gb_te:before{content:url('https://www.gstatic.com/images/branding/googlelogo/svg/googlelogo_dark_clr_74x24px.svg')}@media screen and (-ms-high-contrast:black-on-white){.gb_yc .gb_tc .gb_te:before{content:url('https://www.gstatic.com/images/branding/googlelogo/svg/googlelogo_dark_clr_74x24px.svg')}}@media screen and (-ms-high-contrast:white-on-black){.gb_ge .gb_tc .gb_te:before{content:url('https://www.gstatic.com/images/branding/googlelogo/svg/googlelogo_light_clr_74x24px.svg')}}.gb_ra{background-repeat:no-repeat}.gb_he{display:inline-block;font-family:'Product Sans',Arial,sans-serif;font-size:22px;line-height:24px;padding-left:8px;position:relative;top:-1.5px;vertical-align:middle}.gb_1c .gb_he{padding-left:4px}.gb_1c .gb_he.gb_ve{padding-left:0}.gb_ua.gb_ie{padding-right:4px}.gb_Jc .gb_0c.gb_he{opacity:1}.gb_we:focus .gb_he{text-decoration:underline}.gb_xe img.gb_ua{margin-bottom:4px}.gb_xc{-webkit-border-radius:50%;border-radius:50%;display:inline-block;margin:0 4px;padding:12px;overflow:hidden;vertical-align:middle;cursor:pointer;height:24px;width:24px;-webkit-user-select:none;-webkit-flex:0 0 auto;flex:0 0 auto}.gb_ta .gb_xc{margin:0 4px 0 0}.gb_xc:focus,.gb_xc:focus:hover{background-color:rgba(60,64,67,0.1);outline:none}.gb_xc:active{background-color:rgba(60,64,67,0.12);outline:none}.gb_xc:hover{background-color:rgba(60,64,67,0.08);outline:none}.gb_yc .gb_xc:hover{background-color:rgba(232,234,237,0.08)}.gb_yc .gb_xc:focus,.gb_yc .gb_xc:focus:hover{background-color:rgba(232,234,237,0.1)}.gb_yc .gb_xc:active{background-color:rgba(232,234,237,0.12)}.gb_zc{display:none}.gb_Ac{-webkit-transform:none;transform:none}.gb_Cc{display:none}.gb_Ec{background-color:#fff;bottom:0;color:#000;height:-webkit-calc(100vh - 100%);height:calc(100vh - 100%);overflow-y:auto;overflow-x:hidden;position:absolute;top:100%;z-index:990;will-change:visibility;visibility:hidden;display:-webkit-flex;display:flex;-webkit-flex-direction:column;flex-direction:column;-webkit-transition:transform .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear .25s;transition:transform .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear .25s}.gb_Ec.gb_Fc.gb_Hc,.gb_Ec.gb_Fc.gb_Hc:hover{overflow:visible}.gb_Ec.gb_ta{width:264px;-webkit-transform:translateX( -264px );transform:translateX( -264px )}.gb_Ec:not(.gb_ta){width:280px;-webkit-transform:translateX( -280px );transform:translateX( -280px )}.gb_Ic .gb_Ec{width:195px}.gb_Ec.gb_oa{-webkit-transform:translateX(0);transform:translateX(0);visibility:visible;-webkit-box-shadow:0 0 16px rgba(0,0,0,.28);box-shadow:0 0 16px rgba(0,0,0,.28);-webkit-transition:transform .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear 0s;transition:transform .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear 0s}.gb_Ec.gb_Jc{background-color:rgba(32,33,36,1);color:#e8eaed}.gb_Kc.gb_Lc{background-color:transparent;-webkit-box-shadow:0 0;box-shadow:0 0}.gb_Kc.gb_Lc>:not(.gb_Mc){display:none}.gb_Mc{display:-webkit-flex;display:flex;-webkit-flex:1 1 auto;flex:1 1 auto;-webkit-flex-direction:column;flex-direction:column}.gb_Mc>.gb_Nc{-webkit-flex:1 0 auto;flex:1 0 auto}.gb_Mc>.gb_Oc{-webkit-flex:0 0 auto;flex:0 0 auto}.gb_Pc{list-style:none;margin-top:0;margin-bottom:0;padding:8px 0}.gb_Ec:not(.gb_Kc) .gb_Pc:first-child{padding:0 0 8px 0}.gb_Pc:not(:last-child){border-bottom:1px solid #ddd}.gb_Jc .gb_Pc:not(:last-child){border-bottom:1px solid #5f6368}.gb_Jc .gb_Qc .gb_Rc{background-color:rgba(32,33,36,1);border-bottom:1px solid #5f6368}.gb_Sc{cursor:pointer}.gb_Tc:empty{display:none}.gb_Sc,.gb_Tc{display:block;min-height:40px;padding-bottom:4px;padding-top:4px;font-family:Roboto,RobotoDraft,Helvetica,Arial,sans-serif;color:rgba(0,0,0,0.87)}.gb_Jc .gb_Sc{color:#e8eaed}.gb_Jc .gb_Tc{color:#9aa0a6}.gb_Ec.gb_ta .gb_Sc{padding-left:16px}.gb_Ec:not(.gb_ta) .gb_Sc,.gb_Ec:not(.gb_ta) .gb_Tc{padding-left:24px}.gb_Sc:hover{background:rgba(0,0,0,0.12)}.gb_Jc .gb_Sc:hover{background:rgba(232,234,237,0.08)}.gb_Sc.gb_Ca{background:rgba(0,0,0,0.12);font-weight:bold;color:rgba(0,0,0,0.87)}.gb_Jc .gb_Sc.gb_Ca{background:rgba(232,234,237,0.12);color:rgba(255,255,255, .87 )}.gb_Sc .gb_Uc{text-decoration:none;display:inline-block;width:100%}.gb_Sc .gb_Uc:focus{outline:none}.gb_Sc .gb_Vc,.gb_Tc{padding-left:32px;display:inline-block;line-height:40px;vertical-align:top;width:176px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}.gb_Ic .gb_Sc .gb_Vc,.gb_Ic .gb_Tc{padding-left:16px;width:138px}.gb_Mc.gb_u .gb_Uc:focus .gb_Vc{text-decoration:underline}.gb_Sc .gb_Wc{height:24px;width:24px;float:left;margin-top:8px;vertical-align:middle}.gb_Qc>*{display:block;min-height:48px}.gb_sa.gb_ta .gb_Qc>*{padding-top:4px;padding-bottom:4px;padding-left:16px}.gb_sa:not(.gb_ta) .gb_Qc>*{padding-top:8px;padding-bottom:8px;padding-left:24px}.gb_sa:not(.gb_ta) .gb_1c .gb_rc{-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex}.gb_Qc .gb_rc{display:table-cell;height:48px;vertical-align:middle}.gb_Qc .gb_Rc{background-color:#f5f5f5;display:block}.gb_Qc .gb_Rc .gb_fd{float:right}.gb_sa.gb_ta .gb_Qc .gb_Rc{padding:4px}.gb_sa:not(.gb_ta) .gb_Qc .gb_Rc{padding:8px}.gb_Qc .gb_Ma{width:40px}.gb_Qc .gb_Pa{position:absolute;right:0;top:50%}.gb_Ec.gb_ye{-webkit-overflow-scrolling:touch}.gb_Ec .gb_we{text-decoration:none}.gb_Ec .gb_he{display:inline;white-space:normal;word-break:break-all;word-break:break-word}body.gb_ze [data-ogpc]{-webkit-transition:margin-left .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear .25s;transition:margin-left .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear .25s}body.gb_ze.gb_Ae [data-ogpc]{-webkit-transition:margin-left .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear 0s;transition:margin-left .25s  cubic-bezier(0.4,0.0,0.2,1) ,visibility 0s linear 0s}body [data-ogpc]{margin-left:0}body.gb_Ae [data-ogpc]{margin-left:280px}.gb_Sf{cursor:pointer;padding:13px}.gb_Tf{background-color:rgba(0,0,0,0.1);-webkit-box-shadow:inset 1px 1px 3px rgba(0,0,0,.24);box-shadow:inset 1px 1px 3px rgba(0,0,0,.24);width:34px;height:17px;-webkit-border-radius:8px;border-radius:8px;position:relative;-webkit-transition:background-color ease 150ms;transition:background-color ease 150ms}.gb_Sf[aria-pressed=true] .gb_Tf{background-color:rgba(255,255,255,0.1)}.gb_Uf{position:absolute;width:25px;height:25px;-webkit-border-radius:50%;border-radius:50%;-webkit-box-shadow:0 0 2px rgba(0,0,0,.12),0 2px 4px rgba(0,0,0,.24);box-shadow:0 0 2px rgba(0,0,0,.12),0 2px 4px rgba(0,0,0,.24);top:-4px;-webkit-transform:translateX(-12px);transform:translateX(-12px);background-color:white;-webkit-transition:transform ease 150ms;transition:transform ease 150ms}.gb_Sf[aria-pressed=true] .gb_Uf{-webkit-transform:translateX(20px);transform:translateX(20px)}.gb_Uf img{position:absolute;margin:5px;width:15px;height:15px}.gb_Be{line-height:0;-webkit-user-select:none}.gb_8d>.gb_Be:only-child{float:right}.gb_Be .gb_He{display:inline-block}.gb_Be .gb_7c{cursor:pointer}.gb_Be .gb_7c img{opacity:.54;width:24px;height:24px;padding:10px}.gb_yc .gb_Be .gb_7c img{opacity:1}.gb_Ce{text-align:right}.gb_He{text-align:initial}.gb_Be .gb_Ie,.gb_Be .gb_Je{display:table-cell;height:48px;vertical-align:middle}.gb_Be .gb_Ie:not(.gb_Ke){overflow:hidden}.gb_Ne{padding-left:16px}.gb_Ne:not(.gb_ta){padding-left:24px}.gb_Oe{color:black;opacity:.54}.gb_Pe{background:white;-webkit-box-shadow:0 5px 5px -3px rgba(0,0,0,0.2),0 8px 10px 1px rgba(0,0,0,0.14),0 3px 14px 2px rgba(0,0,0,0.12);box-shadow:0 5px 5px -3px rgba(0,0,0,0.2),0 8px 10px 1px rgba(0,0,0,0.14),0 3px 14px 2px rgba(0,0,0,0.12);overflow-y:hidden;position:absolute;right:24px;top:48px}.gb_vf,.gb_wf,.gb_xf{display:none}.gb_Se{height:48px;max-width:720px}.gb_8d.gb_1e:not(.gb_Re) .gb_Se{max-width:100%;-webkit-flex:1 1 auto;flex:1 1 auto}.gb_7d>.gb_Ud .gb_Se{display:table-cell;vertical-align:middle;width:100%}.gb_8d.gb_1e .gb_Se .gb_6e{margin-left:0;margin-right:0}.gb_6e{background:#f1f3f4;border:1px solid transparent;-webkit-border-radius:8px;border-radius:8px;margin-left:auto;margin-right:auto;max-width:720px;position:relative;-webkit-transition:background 100ms ease-in,width 100ms ease-out;transition:background 100ms ease-in,width 100ms ease-out}.gb_6e.gb_yf{-webkit-border-radius:8px 8px 0 0;border-radius:8px 8px 0 0}.gb_yc .gb_6e{background:rgba(241,243,244,0.24)}.gb_6e button{background:none;border:none;cursor:pointer;outline:none;padding:0 5px;line-height:0}.gb_6e:not(.gb_Re) button{padding:0 5px}.gb_6e button svg,.gb_6e button img{padding:8px;margin:3px}.gb_6e.gb_Re button svg{margin-left:1px;margin-right:1px}.gb_zf.gb_Af,.gb_Bf.gb_Af{padding-left:2px;padding-right:2px}.gb_Bf{display:none}.gb_zf,.gb_Bf{float:left;position:absolute;top:0}.gb_Cf{position:absolute;right:0;cursor:default;visibility:hidden;top:0;-webkit-transition:opacity 250ms ease-out;transition:opacity 250ms ease-out}.gb_Df .gb_Cf{right:44px}.gb_Cf.gb_Ef{visibility:inherit}.gb_qf::-ms-clear{display:none;height:0;width:0}.gb_Ff{position:absolute;right:0;top:0}.gb_Hf{height:46px;padding:0;margin-left:56px;margin-right:49px;overflow:hidden}.gb_Df .gb_Hf{margin-right:96px}.gb_qf{background:transparent;border:none;font:normal 16px Google Sans,Roboto,RobotoDraft,Helvetica,Arial,sans-serif;-webkit-font-variant-ligatures:none;font-variant-ligatures:none;height:46px;outline:none;width:100%;-webkit-box-sizing:border-box;box-sizing:border-box}.gb_Af.gb_Hf .gb_qf.gb_If{padding-left:2px}.gb_yc .gb_qf{color:rgba(255,255,255,0.87)}.gb_qf:not(.gb_If){padding:11px 0}.gb_qf.gb_If{padding:0}.gb_If{height:46px;line-height:46px}.gb_6e:not(.gb_7e) input::-webkit-input-placeholder{color:rgba(0,0,0,0.54)}.gb_yc .gb_6e:not(.gb_7e) input::-webkit-input-placeholder{color:rgba(255,255,255,0.87)}.gb_6e.gb_Re:not(.gb_N){background:transparent;float:right;-webkit-box-shadow:none;box-shadow:none}.gb_6e.gb_Re:not(.gb_N) .gb_Hf,.gb_6e.gb_Re:not(.gb_N) .gb_Cf,.gb_6e.gb_Re:not(.gb_N) .gb_Ff{display:none}.gb_6e.gb_Re.gb_N{margin-left:0;position:absolute;width:auto}.gb_6e.gb_Re.gb_N .gb_zf{display:none}.gb_6e.gb_Re .gb_zf{padding:0;position:static}.gb_6e.gb_Re.gb_N .gb_Bf{display:block}.gb_sa.gb_Lc .gb_Ud.gb_Qe:not(.gb_Re) .gb_Se,.gb_sa.gb_Lc .gb_Ud.gb_Te.gb_Ue:not(.gb_Re) .gb_Se,.gb_sa.gb_3d .gb_Ud:not(.gb_Qe):not(.gb_Re) .gb_Se{padding-right:30px}.gb_sa.gb_Lc .gb_Ud.gb_Ue:not(.gb_Re) .gb_Se,.gb_sa.gb_Lc .gb_Ud.gb_Te.gb_Qe:not(.gb_Re) .gb_Se{padding-left:30px}.gb_Ud:not(.gb_Re) .gb_Se{padding-left:10px;padding-right:10px;width:100%;-webkit-flex:1 1 auto;flex:1 1 auto}.gb_Se.gb_Fa{display:none}.gb_8d.gb_Ve>.gb_Be{min-width:initial!important;min-width:auto!important}.gb_We,.gb_Xe:not(.gb_4d):not(.gb_Ve).gb_Ze{-webkit-box-pack:flex-end;-webkit-justify-content:flex-end;justify-content:flex-end}.gb_Xe:not(.gb_4d):not(.gb_Ve){-webkit-box-pack:center;-webkit-justify-content:center;justify-content:center}.gb_Xe:not(.gb_4d):not(.gb_Ve).gb_0e,.gb_Xe:not(.gb_4d):not(.gb_Ve).gb_1e{-webkit-box-pack:flex-start;-webkit-justify-content:flex-start;justify-content:flex-start}.gb_8d.gb_4d,.gb_8d.gb_Ve{-webkit-box-pack:space-between;-webkit-justify-content:space-between;justify-content:space-between}.gb_sa.gb_ta .gb_1c,.gb_Vd.gb_4d.gb_5d>.gb_1c{-webkit-flex:1 1 auto;flex:1 1 auto;overflow:hidden}.gb_sa.gb_ta .gb_8d,.gb_Vd.gb_4d.gb_5d>.gb_8d{-webkit-flex:0 0 auto;flex:0 0 auto}.gb_Jf{position:relative}.gb_Kf{margin:0 58px;padding:0;text-align:center;white-space:nowrap;-webkit-user-select:none;overflow:auto}.gb_Kf::-webkit-scrollbar{display:none}.gb_ta .gb_Kf,.gb_Td .gb_Kf{margin:0}.gb_Lf,.gb_Mf{display:none;height:48px;position:absolute;top:0;width:100px}.gb_Jf.gb_Nf .gb_Lf,.gb_Jf.gb_Of .gb_Mf{display:block}.gb_Mf{pointer-events:none}.gb_Lf{pointer-events:none;left:0}.gb_Mf{right:0}.gb_Pf{cursor:pointer;display:inline-table;outline:none}.gb_Pf>.gb_Qf{border:0 solid transparent;border-width:2px 0;display:table-cell;height:44px;padding:0 22px;opacity:.7;text-decoration:none;text-transform:uppercase;vertical-align:middle}.gb_Pf.gb_Ca:focus{background-color:rgba(0,0,0,.16)}.gb_Pf.gb_Ca>.gb_Qf{border-bottom-color:black;opacity:1}.gb_yc .gb_Pf.gb_Ca>.gb_Qf{border-bottom-color:white}.gb_ge .gb_Pf.gb_Ca>.gb_Qf{border-bottom-color:black}.gb_Kf.gb_Rf>.gb_Pf.gb_Ca>.gb_Qf{border-bottom-color:#4285f4;color:#4285f4}sentinel{}</style><script type="text/javascript">;this.gbar_={CONFIG:[[[0,"www.gstatic.com","og.qtm.en_US.3Q2Fmww-UG0.O","co.in","en","243",0,[4,2,".40.40.40.76.40.40.40.","","1300102,3700248,3700830,3700832","344732237","0"],null,"biDHX9vPJ9bD3LUPrbWpoAs",null,0,"og.qtm.MS6fO3HUAzQ.L.W.O","AA2YrTuWr-THoJhZf_G0GDWJEiz9fL6BmQ","AA2YrTunZMz9vXN9D_fVuVUp2s6sffrErw","",2,1,200,"IND",null,null,"1","243",1],null,[1,0.1000000014901161,2,1],[1,0.001000000047497451,1],[1,0,0,null,"0","srinidhithegreat01@gmail.com","","AOEwXKrkhJRT2AgztXwmDoP-0gVVNQCTSor0lslvT69tWqUoOSKWTODEyvstF5IR1FVl0CaTKZKpveKn_yaQn8BREaJ9LdJa5A"],[0,1,"",1,0,1,0,0,0,1,0,0,0,null,0,0,null,null,0,0,0,"","","","","","",null,0,0,0,0,0,null,null,null,"rgba(32,33,36,1)","transparent",0,0,1,null,null,0],["%1$s (default)","Brand account",0,"%1$s (delegated)",1,null,83,"https://www.google.com/webhp?authuser=$authuser",null,null,null,1,"https://accounts.google.com/ListAccounts?listPages=0\u0026authuser=0\u0026pid=243\u0026gpsia=1\u0026source=ogb\u0026mo=1\u0026mn=1\u0026hl=en",0,"dashboard",null,null,null,null,"Profile","",0,null,"Signed out","https://accounts.google.com/AccountChooser?source=ogb\u0026continue=$continue\u0026Email=$email\u0026ec=GAhA8wE","https://accounts.google.com/RemoveLocalAccount?source=ogb","Remove","Sign in",0,0,1,0,1,0,0,"000770F20326A4C066D782D2C0412680D5DCE652EC65860A85::1606885486654",null,157,"Session expired",null,null,"https://docs.google.com/picker","Visitor",null,"Default","Delegated","Sign out of all accounts",1,0,null,0,0,0,"myaccount.google.com"],null,["1","gci_91f30755d6a6b787dcc2a4062e6e9824.js","googleapis.client:gapi.iframes","0","en"],null,null,null,null,["m;/_/scs/abc-static/_/js/k=gapi.gapi.en.uhBKOtz6fOw.O/d=1/ct=zgms/rs=AHpOoo8GZHNTtpcfighnqAH0uUZTALLzrw/m=__features__","https://apis.google.com","","","1","",null,1,"es_plusone_gc_20201103.0_p0","en",null,0],[0.009999999776482582,"co.in","243",[null,"","0",null,1,5184000,null,null,"",0,1,"",null,0,0,null,1,0,1,0,0,0,null,null,0,0],null,null,null,0,null,null,["5061451","google\\.(com|ru|ca|by|kz|com\\.mx|com\\.tr)$",1]],[1,1,null,40400,243,"IND","en","344732237.0",7,0.009999999776482582,1,0,null,null,1,0,"3700830,3700832",null,null,null,"biDHX9vPJ9bD3LUPrbWpoAs",0,0],[[null,null,null,"https://www.gstatic.com/og/_/js/k=og.qtm.en_US.3Q2Fmww-UG0.O/rt=j/m=qgl,q_dnp,qdid,qmd,qcwid,qmutsd,qbd,qapid,qald/exm=qaaw,qabr,qadd,qaid,qalo,qebr,qein,qhaw,qhbr,qhch,qhga,qhid,qhin,qhlo,qhmn,qhpc,qhpr,qhsf,qhtb,qhtt/d=1/ed=1/rs=AA2YrTuWr-THoJhZf_G0GDWJEiz9fL6BmQ"],[null,null,null,"https://www.gstatic.com/og/_/ss/k=og.qtm.MS6fO3HUAzQ.L.W.O/m=qdid,qmd,qcwid/excm=qaaw,qabr,qadd,qaid,qalo,qebr,qein,qhaw,qhbr,qhch,qhga,qhid,qhin,qhlo,qhmn,qhpc,qhpr,qhsf,qhtb,qhtt/d=1/ed=1/ct=zgms/rs=AA2YrTunZMz9vXN9D_fVuVUp2s6sffrErw"]],null,null,[""],[[[null,null,[null,null,null,"https://ogs.google.com/u/0/widget/app"],0,448,328,57,4,1,0,0,63,64,8000,"https://www.google.co.in/intl/en/about/products?tab=rh",67,1,69,null,1,70,"Can't seem to load the app launcher right now. Try again or go to the %1$sGoogle Products%2$s page.",3,0,0,74,4000,null,null,null,null,null,null,1]],0,[null,null,null,"https://www.gstatic.com/og/_/js/k=og.qtm.en_US.3Q2Fmww-UG0.O/rt=j/m=qdsh/d=1/ed=1/rs=AA2YrTuWr-THoJhZf_G0GDWJEiz9fL6BmQ"],"1","243",1,0,null,"en",0],null,[["mousedown","touchstart","touchmove","wheel","keydown"],300000]]],};this.gbar_=this.gbar_||{};(function(_){var window=this;
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var da,ea,fa,ha,ia,ka,ma,na,ra,sa,Da,Ea,Fa;_.aa=function(a){if(Error.captureStackTrace)Error.captureStackTrace(this,_.aa);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))};_.ca=function(a,b){return 0<=(0,_.ba)(a,b)};da=function(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}};ea="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
fa=function(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("a");};ha=fa(this);ia=function(a,b){if(b)a:{var c=ha;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ea(c,a,{configurable:!0,writable:!0,value:b})}};
ia("Symbol",function(a){if(a)return a;var b=function(e,f){this.j=e;ea(this,"description",{configurable:!0,writable:!0,value:f})};b.prototype.toString=function(){return this.j};var c=0,d=function(e){if(this instanceof d)throw new TypeError("b");return new b("jscomp_symbol_"+(e||"")+"_"+c++,e)};return d});
ia("Symbol.iterator",function(a){if(a)return a;a=Symbol("c");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ha[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ea(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ka(da(this))}})}return a});ka=function(a){a={next:a};a[Symbol.iterator]=function(){return this};return a};
_.la=function(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:da(a)}};ma="function"==typeof Object.create?Object.create:function(a){var b=function(){};b.prototype=a;return new b};if("function"==typeof Object.setPrototypeOf)na=Object.setPrototypeOf;else{var oa;a:{var pa={a:!0},qa={};try{qa.__proto__=pa;oa=qa.a;break a}catch(a){}oa=!1}na=oa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError("d`"+a);return a}:null}ra=na;
_.n=function(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(ra)ra(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.U=b.prototype};sa=function(a,b,c){if(null==a)throw new TypeError("e`"+c);if(b instanceof RegExp)throw new TypeError("f`"+c);return a+""};
ia("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=sa(this,b,"startsWith"),e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});var ta=function(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};e[Symbol.iterator]=function(){return e};return e};
ia("Array.prototype.entries",function(a){return a?a:function(){return ta(this,function(b,c){return[b,c]})}});ia("Array.prototype.keys",function(a){return a?a:function(){return ta(this,function(b){return b})}});ia("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});ia("Array.prototype.values",function(a){return a?a:function(){return ta(this,function(b,c){return c})}});
var ua=function(a,b){return Object.prototype.hasOwnProperty.call(a,b)},va="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ua(d,e)&&(a[e]=d[e])}return a};ia("Object.assign",function(a){return a||va});
ia("WeakMap",function(a){function b(){}function c(l){var m=typeof l;return"object"===m&&null!==l||"function"===m}function d(l){if(!ua(l,f)){var m=new b;ea(l,f,{value:m})}}function e(l){var m=Object[l];m&&(Object[l]=function(r){if(r instanceof b)return r;Object.isExtensible(r)&&d(r);return m(r)})}if(function(){if(!a||!Object.seal)return!1;try{var l=Object.seal({}),m=Object.seal({}),r=new a([[l,2],[m,3]]);if(2!=r.get(l)||3!=r.get(m))return!1;r.delete(l);r.set(m,4);return!r.has(l)&&4==r.get(m)}catch(u){return!1}}())return a;
var f="$jscomp_hidden_"+Math.random();e("freeze");e("preventExtensions");e("seal");var g=0,k=function(l){this.j=(g+=Math.random()+1).toString();if(l){l=_.la(l);for(var m;!(m=l.next()).done;)m=m.value,this.set(m[0],m[1])}};k.prototype.set=function(l,m){if(!c(l))throw Error("g");d(l);if(!ua(l,f))throw Error("h`"+l);l[f][this.j]=m;return this};k.prototype.get=function(l){return c(l)&&ua(l,f)?l[f][this.j]:void 0};k.prototype.has=function(l){return c(l)&&ua(l,f)&&ua(l[f],this.j)};k.prototype.delete=function(l){return c(l)&&
ua(l,f)&&ua(l[f],this.j)?delete l[f][this.j]:!1};return k});ia("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(k){return k};var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
ia("Map",function(a){if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var k=Object.seal({x:4}),l=new a(_.la([[k,"s"]]));if("s"!=l.get(k)||1!=l.size||l.get({x:4})||l.set({x:4},"t")!=l||2!=l.size)return!1;var m=l.entries(),r=m.next();if(r.done||r.value[0]!=k||"s"!=r.value[1])return!1;r=m.next();return r.done||4!=r.value[0].x||"t"!=r.value[1]||!m.next().done?!1:!0}catch(u){return!1}}())return a;var b=new WeakMap,c=function(k){this.o={};this.j=
f();this.size=0;if(k){k=_.la(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}};c.prototype.set=function(k,l){k=0===k?0:k;var m=d(this,k);m.list||(m.list=this.o[m.id]=[]);m.Za?m.Za.value=l:(m.Za={next:this.j,kc:this.j.kc,head:this.j,key:k,value:l},m.list.push(m.Za),this.j.kc.next=m.Za,this.j.kc=m.Za,this.size++);return this};c.prototype.delete=function(k){k=d(this,k);return k.Za&&k.list?(k.list.splice(k.index,1),k.list.length||delete this.o[k.id],k.Za.kc.next=k.Za.next,k.Za.next.kc=
k.Za.kc,k.Za.head=null,this.size--,!0):!1};c.prototype.clear=function(){this.o={};this.j=this.j.kc=f();this.size=0};c.prototype.has=function(k){return!!d(this,k).Za};c.prototype.get=function(k){return(k=d(this,k).Za)&&k.value};c.prototype.entries=function(){return e(this,function(k){return[k.key,k.value]})};c.prototype.keys=function(){return e(this,function(k){return k.key})};c.prototype.values=function(){return e(this,function(k){return k.value})};c.prototype.forEach=function(k,l){for(var m=this.entries(),
r;!(r=m.next()).done;)r=r.value,k.call(l,r[1],r[0],this)};c.prototype[Symbol.iterator]=c.prototype.entries;var d=function(k,l){var m=l&&typeof l;"object"==m||"function"==m?b.has(l)?m=b.get(l):(m=""+ ++g,b.set(l,m)):m="p_"+l;var r=k.o[m];if(r&&ua(k.o,m))for(k=0;k<r.length;k++){var u=r[k];if(l!==l&&u.key!==u.key||l===u.key)return{id:m,list:r,index:k,Za:u}}return{id:m,list:r,index:-1,Za:void 0}},e=function(k,l){var m=k.j;return ka(function(){if(m){for(;m.head!=k.j;)m=m.kc;for(;m.next!=m.head;)return m=
m.next,{done:!1,value:l(m)};m=null}return{done:!0,value:void 0}})},f=function(){var k={};return k.kc=k.next=k.head=k},g=0;return c});
ia("Set",function(a){if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(_.la([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;var b=function(c){this.j=new Map;if(c){c=
_.la(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.j.size};b.prototype.add=function(c){c=0===c?0:c;this.j.set(c,c);this.size=this.j.size;return this};b.prototype.delete=function(c){c=this.j.delete(c);this.size=this.j.size;return c};b.prototype.clear=function(){this.j.clear();this.size=0};b.prototype.has=function(c){return this.j.has(c)};b.prototype.entries=function(){return this.j.entries()};b.prototype.values=function(){return this.j.values()};b.prototype.keys=b.prototype.values;
b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.j.forEach(function(f){return c.call(d,f,f,e)})};return b});ia("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ua(b,d)&&c.push([d,b[d]]);return c}});ia("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
ia("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});ia("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==sa(this,b,"includes").indexOf(b,c||0)}});
ia("Array.prototype.fill",function(a){return a?a:function(b,c,d){var e=this.length||0;0>c&&(c=Math.max(0,e+c));if(null==d||d>e)d=e;d=Number(d);0>d&&(d=Math.max(0,e+d));for(c=Number(c||0);c<d;c++)this[c]=b;return this}});var wa=function(a){return a?a:Array.prototype.fill};ia("Int8Array.prototype.fill",wa);ia("Uint8Array.prototype.fill",wa);ia("Uint8ClampedArray.prototype.fill",wa);ia("Int16Array.prototype.fill",wa);ia("Uint16Array.prototype.fill",wa);ia("Int32Array.prototype.fill",wa);
ia("Uint32Array.prototype.fill",wa);ia("Float32Array.prototype.fill",wa);ia("Float64Array.prototype.fill",wa);_.xa=_.xa||{};_.p=this||self;_.za=function(){};_.Aa=function(a){a.af=void 0;a.va=function(){return a.af?a.af:a.af=new a}};_.Ba=function(a){var b=typeof a;return"object"==b&&null!=a||"function"==b};_.Ca="closure_uid_"+(1E9*Math.random()>>>0);Da=function(a,b,c){return a.call.apply(a.bind,arguments)};
Ea=function(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}};_.q=function(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?_.q=Da:_.q=Ea;return _.q.apply(null,arguments)};
_.t=function(a,b){a=a.split(".");var c=_.p;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b};_.v=function(a,b){function c(){}c.prototype=b.prototype;a.U=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.jm=function(d,e,f){for(var g=Array(arguments.length-2),k=2;k<arguments.length;k++)g[k-2]=arguments[k];return b.prototype[e].apply(d,g)}};Fa=function(a){return a};
_.Ga=function(a){var b=null,c=_.p.trustedTypes;if(!c||!c.createPolicy)return b;try{b=c.createPolicy(a,{createHTML:Fa,createScript:Fa,createScriptURL:Fa})}catch(d){_.p.console&&_.p.console.error(d.message)}return b};
_.v(_.aa,Error);_.aa.prototype.name="CustomError";
_.ba=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1};_.Ha=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)};
_.Ia=Array.prototype.filter?function(a,b,c){return Array.prototype.filter.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=[],f=0,g="string"===typeof a?a.split(""):a,k=0;k<d;k++)if(k in g){var l=g[k];b.call(c,l,k,a)&&(e[f++]=l)}return e};_.Ja=Array.prototype.map?function(a,b,c){return Array.prototype.map.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=Array(d),f="string"===typeof a?a.split(""):a,g=0;g<d;g++)g in f&&(e[g]=b.call(c,f[g],g,a));return e};
_.Ka=Array.prototype.some?function(a,b){return Array.prototype.some.call(a,b,void 0)}:function(a,b){for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a))return!0;return!1};
var Ma;_.La=function(a,b,c){for(var d in a)b.call(c,a[d],d,a)};Ma="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");_.Na=function(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Ma.length;f++)c=Ma[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}};
var Oa;_.Pa=function(){void 0===Oa&&(Oa=_.Ga("ogb-qtm#html"));return Oa};
var Ra;_.Sa=function(a,b){this.j=a===_.Qa&&b||"";this.o=Ra};_.Sa.prototype.Rb=!0;_.Sa.prototype.Fb=function(){return this.j};_.Ta=function(a){return a instanceof _.Sa&&a.constructor===_.Sa&&a.o===Ra?a.j:"type_error:Const"};Ra={};_.Qa={};
var Ua;_.Va=function(a,b){this.o=b===Ua?a:""};_.Va.prototype.Rb=!0;_.Va.prototype.Fb=function(){return this.o.toString()};_.Va.prototype.Ze=!0;_.Va.prototype.j=function(){return 1};_.Xa=function(a){return _.Wa(a).toString()};_.Wa=function(a){return a instanceof _.Va&&a.constructor===_.Va?a.o:"type_error:TrustedResourceUrl"};Ua={};_.Ya=function(a){var b=_.Pa();a=b?b.createScriptURL(a):a;return new _.Va(a,Ua)};
var $a;_.Za=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
_.ab=function(a,b){var c=0;a=(0,_.Za)(String(a)).split(".");b=(0,_.Za)(String(b)).split(".");for(var d=Math.max(a.length,b.length),e=0;0==c&&e<d;e++){var f=a[e]||"",g=b[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;c=$a(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||$a(0==f[2].length,0==g[2].length)||$a(f[2],g[2]);f=f[3];g=g[3]}while(0==c)}return c};
$a=function(a,b){return a<b?-1:a>b?1:0};
var eb,fb,gb,bb;_.cb=function(a,b){this.o=b===bb?a:""};_.cb.prototype.Rb=!0;_.cb.prototype.Fb=function(){return this.o.toString()};_.cb.prototype.Ze=!0;_.cb.prototype.j=function(){return 1};_.db=function(a){return a instanceof _.cb&&a.constructor===_.cb?a.o:"type_error:SafeUrl"};eb=/^(?:audio\/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font\/\w+|image\/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video\/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\w+=(?:\w+|"[\w;,= ]+"))*$/i;
fb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i;gb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;_.ib=function(a){if(a instanceof _.cb)return a;a="object"==typeof a&&a.Rb?a.Fb():String(a);if(gb.test(a))a=_.hb(a);else{a=String(a);a=a.replace(/(%0A|%0D)/g,"");var b=a.match(fb);a=b&&eb.test(b[1])?_.hb(a):null}return a};_.jb=function(a){if(a instanceof _.cb)return a;a="object"==typeof a&&a.Rb?a.Fb():String(a);gb.test(a)||(a="about:invalid#zClosurez");return _.hb(a)};bb={};
_.hb=function(a){return new _.cb(a,bb)};_.kb=_.hb("about:invalid#zClosurez");
_.mb=function(a,b){this.j=b===_.lb?a:""};_.mb.prototype.Rb=!0;_.mb.prototype.Fb=function(){return this.j};_.lb={};_.nb=new _.mb("",_.lb);
a:{var pb=_.p.navigator;if(pb){var qb=pb.userAgent;if(qb){_.ob=qb;break a}}_.ob=""}_.w=function(a){return-1!=_.ob.indexOf(a)};
var tb;_.rb=function(){return _.w("Trident")||_.w("MSIE")};_.sb=function(){return _.w("Firefox")||_.w("FxiOS")};_.ub=function(){return _.w("Safari")&&!(tb()||_.w("Coast")||_.w("Opera")||_.w("Edge")||_.w("Edg/")||_.w("OPR")||_.sb()||_.w("Silk")||_.w("Android"))};tb=function(){return(_.w("Chrome")||_.w("CriOS"))&&!_.w("Edge")};_.vb=function(){return _.w("Android")&&!(tb()||_.sb()||_.w("Opera")||_.w("Silk"))};
var wb;_.xb=function(a,b,c){this.o=c===wb?a:"";this.A=b};_.xb.prototype.Ze=!0;_.xb.prototype.j=function(){return this.A};_.xb.prototype.Rb=!0;_.xb.prototype.Fb=function(){return this.o.toString()};_.yb=function(a){return a instanceof _.xb&&a.constructor===_.xb?a.o:"type_error:SafeHtml"};wb={};_.zb=function(a,b){var c=_.Pa();a=c?c.createHTML(a):a;return new _.xb(a,b,wb)};_.Ab=new _.xb(_.p.trustedTypes&&_.p.trustedTypes.emptyHTML||"",0,wb);_.Bb=_.zb("<br>",0);
_.Cb=function(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}(function(){var a=document.createElement("div"),b=document.createElement("div");b.appendChild(document.createElement("div"));a.appendChild(b);b=a.firstChild.firstChild;a.innerHTML=_.yb(_.Ab);return!b.parentElement});
var Db;Db=function(){return _.w("iPhone")&&!_.w("iPod")&&!_.w("iPad")};_.Eb=function(){return Db()||_.w("iPad")||_.w("iPod")};
_.Fb=function(){return-1!=_.ob.toLowerCase().indexOf("webkit")&&!_.w("Edge")};
_.Gb=function(a){_.Gb[" "](a);return a};_.Gb[" "]=_.za;var Ib=function(a,b){var c=Hb;return Object.prototype.hasOwnProperty.call(c,a)?c[a]:c[a]=b(a)};
var Wb,Xb,Hb,ec;_.Jb=_.w("Opera");_.x=_.rb();_.Kb=_.w("Edge");_.Lb=_.Kb||_.x;_.Mb=_.w("Gecko")&&!_.Fb()&&!(_.w("Trident")||_.w("MSIE"))&&!_.w("Edge");_.Nb=_.Fb();_.Ob=_.w("Macintosh");_.Pb=_.w("Windows");_.Qb=_.w("Linux")||_.w("CrOS");_.Rb=_.w("Android");_.Sb=Db();_.Tb=_.w("iPad");_.Ub=_.w("iPod");_.Vb=_.Eb();Wb=function(){var a=_.p.document;return a?a.documentMode:void 0};
a:{var Yb="",Zb=function(){var a=_.ob;if(_.Mb)return/rv:([^\);]+)(\)|;)/.exec(a);if(_.Kb)return/Edge\/([\d\.]+)/.exec(a);if(_.x)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(_.Nb)return/WebKit\/(\S+)/.exec(a);if(_.Jb)return/(?:Version)[ \/]?(\S+)/.exec(a)}();Zb&&(Yb=Zb?Zb[1]:"");if(_.x){var $b=Wb();if(null!=$b&&$b>parseFloat(Yb)){Xb=String($b);break a}}Xb=Yb}_.ac=Xb;Hb={};_.bc=function(a){return Ib(a,function(){return 0<=_.ab(_.ac,a)})};_.dc=function(a){return Number(cc)>=a};
if(_.p.document&&_.x){var fc=Wb();ec=fc?fc:parseInt(_.ac,10)||void 0}else ec=void 0;var cc=ec;
_.gc=_.sb();_.hc=Db()||_.w("iPod");_.ic=_.w("iPad");_.jc=_.vb();_.kc=tb();_.lc=_.ub()&&!_.Eb();
var mc={},nc=null;
_.oc=function(a){this.j=0;this.o=a};_.oc.prototype.next=function(){return this.j<this.o.length?{done:!1,value:this.o[this.j++]}:{done:!0,value:void 0}};"undefined"!=typeof Symbol&&"undefined"!=typeof Symbol.iterator&&(_.oc.prototype[Symbol.iterator]=function(){return this});
_.y=function(){};_.pc="function"==typeof Uint8Array;
_.z=function(a,b,c,d,e,f){a.j=null;b||(b=c?[c]:[]);a.J=c?String(c):void 0;a.C=0===c?-1:0;a.A=b;a:{c=a.A.length;b=-1;if(c&&(b=c-1,c=a.A[b],!(null===c||"object"!=typeof c||Array.isArray(c)||_.pc&&c instanceof Uint8Array))){a.D=b-a.C;a.B=c;break a}-1<d?(a.D=Math.max(d,b+1-a.C),a.B=null):a.D=Number.MAX_VALUE}a.K={};if(e)for(d=0;d<e.length;d++)b=e[d],b<a.D?(b+=a.C,a.A[b]=a.A[b]||_.qc):(_.rc(a),a.B[b]=a.B[b]||_.qc);if(f&&f.length)for(d=0;d<f.length;d++)_.sc(a,f[d])};_.qc=[];
_.rc=function(a){var b=a.D+a.C;a.A[b]||(a.B=a.A[b]={})};_.A=function(a,b){if(b<a.D){b+=a.C;var c=a.A[b];return c!==_.qc?c:a.A[b]=[]}if(a.B)return c=a.B[b],c===_.qc?a.B[b]=[]:c};_.tc=function(a,b){return null!=_.A(a,b)};_.B=function(a,b){a=_.A(a,b);return null==a?a:!!a};_.uc=function(a,b,c){a=_.A(a,b);return null==a?c:a};_.vc=function(a,b,c){return _.uc(a,b,void 0===c?0:c)};_.wc=function(a,b,c){c=void 0===c?!1:c;a=_.B(a,b);return null==a?c:a};
_.xc=function(a,b,c){c=void 0===c?0:c;a=_.A(a,b);a=null==a?a:+a;return null==a?c:a};_.E=function(a,b,c){b<a.D?a.A[b+a.C]=c:(_.rc(a),a.B[b]=c);return a};_.sc=function(a,b){for(var c,d,e=0;e<b.length;e++){var f=b[e],g=_.A(a,f);null!=g&&(c=f,d=g,_.E(a,f,void 0))}return c?(_.E(a,c,d),c):0};_.F=function(a,b,c){a.j||(a.j={});if(!a.j[c]){var d=_.A(a,c);d&&(a.j[c]=new b(d))}return a.j[c]};_.G=function(a,b,c){a.j||(a.j={});var d=c?c.Ab():c;a.j[b]=c;return _.E(a,b,d)};
_.y.prototype.Ab=function(){if(this.j)for(var a in this.j){var b=this.j[a];if(Array.isArray(b))for(var c=0;c<b.length;c++)b[c]&&b[c].Ab();else b&&b.Ab()}return this.A};
_.y.prototype.o=_.pc?function(){var a=Uint8Array.prototype.toJSON;Uint8Array.prototype.toJSON=function(){var b;void 0===b&&(b=0);if(!nc){nc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));mc[e]=f;for(var g=0;g<f.length;g++){var k=f[g];void 0===nc[k]&&(nc[k]=g)}}}b=mc[b];c=[];for(d=0;d<this.length;d+=3){var l=this[d],m=(e=d+1<this.length)?this[d+1]:0;k=(f=d+2<this.length)?this[d+2]:0;
g=l>>2;l=(l&3)<<4|m>>4;m=(m&15)<<2|k>>6;k&=63;f||(k=64,e||(m=64));c.push(b[g],b[l],b[m]||"",b[k]||"")}return c.join("")};try{return JSON.stringify(this.A&&this.Ab(),yc)}finally{Uint8Array.prototype.toJSON=a}}:function(){return JSON.stringify(this.A&&this.Ab(),yc)};var yc=function(a,b){return"number"!==typeof b||!isNaN(b)&&Infinity!==b&&-Infinity!==b?b:String(b)};_.y.prototype.toString=function(){return this.Ab().toString()};
_.I=function(){this.Pa=this.Pa;this.Kb=this.Kb};_.I.prototype.Pa=!1;_.I.prototype.ta=function(){this.Pa||(this.Pa=!0,this.S())};_.I.prototype.S=function(){if(this.Kb)for(;this.Kb.length;)this.Kb.shift()()};
var zc=function(a){_.z(this,a,0,-1,null,null)};_.v(zc,_.y);
_.Ac=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Ac,_.y);
_.Bc=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Bc,_.y);
var Cc=function(a){_.z(this,a,0,-1,null,null)};_.v(Cc,_.y);
_.Dc=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Dc,_.y);
_.Ec=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Ec,_.y);
var Fc=function(a){_.I.call(this);this.A=a;this.j=[];this.o={}};_.n(Fc,_.I);Fc.prototype.Ad=function(){for(var a=this.j.length,b=this.j,c=[],d=0;d<a;++d){var e=b[d].j();a:{var f=this.A;for(var g=e.split("."),k=g.length,l=0;l<k;++l)if(f[g[l]])f=f[g[l]];else{f=null;break a}f=f instanceof Function?f:null}if(f&&f!=this.o[e])try{b[d].Ad(f)}catch(m){}else c.push(b[d])}this.j=c.concat(b.slice(a))};
_.Gc=function(){this.j={};this.o={}};_.Ic=function(a){return _.Hc(_.Gc.va(),a)};_.Kc=function(a,b){var c=_.Gc.va();if(a in c.j){if(c.j[a]!=b)throw new Jc(a);}else{c.j[a]=b;if(b=c.o[a])for(var d=0,e=b.length;d<e;d++)b[d].j(c.j,a);delete c.o[a]}};_.Hc=function(a,b){if(b in a.j)return a.j[b];throw new Lc(b);};_.Aa(_.Gc);var Mc=function(){_.aa.call(this)};_.n(Mc,_.aa);var Jc=function(){_.aa.call(this)};_.n(Jc,Mc);var Lc=function(){_.aa.call(this)};_.n(Lc,Mc);
var Nc=function(a){_.I.call(this);this.C=a;this.A=this.j=null;this.D=0;this.B={};this.o=!1;a=window.navigator.userAgent;0<=a.indexOf("MSIE")&&0<=a.indexOf("Trident")&&(a=/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a))&&a[1]&&9>parseFloat(a[1])&&(this.o=!0)};_.n(Nc,_.I);Nc.prototype.F=function(a,b){this.j=b;this.A=a;b.preventDefault?b.preventDefault():b.returnValue=!1};
_.Oc=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Oc,_.y);
_.Pc=function(a){_.z(this,a,0,-1,null,null)};_.v(_.Pc,_.y);
_.J=function(a,b){return null!=a?!!a:!!b};_.K=function(a,b){void 0==b&&(b="");return null!=a?a:b};_.Qc=function(a,b){void 0==b&&(b=0);return null!=a?a:b};
var Rc,Wc,Vc;_.Sc=function(a){var b=window.google&&window.google.logUrl?"":"https://www.google.com";b+="/gen_204?";b+=a.o(2040-b.length);Rc(_.ib(b)||_.kb)};Rc=function(a){var b=new Image,c=Vc;b.onerror=b.onload=b.onabort=function(){c in Wc&&delete Wc[c]};Wc[Vc++]=b;b.src=_.db(a)};Wc=[];Vc=0;
_.Xc=function(){this.data={}};_.Xc.prototype.j=function(){window.console&&window.console.log&&window.console.log("Log data: ",this.data)};_.Xc.prototype.o=function(a){var b=[],c;for(c in this.data)b.push(encodeURIComponent(c)+"="+encodeURIComponent(String(this.data[c])));return("atyp=i&zx="+(new Date).getTime()+"&"+b.join("&")).substr(0,a)};
var Yc=function(a,b){this.data={};var c=_.F(a,Cc,8)||new Cc;window.google&&window.google.kEI&&(this.data.ei=window.google.kEI);this.data.sei=_.K(_.A(a,10));this.data.ogf=_.K(_.A(c,3));var d=window.google&&window.google.sn?/.*hp$/.test(window.google.sn)?!1:!0:_.J(_.B(a,7));this.data.ogrp=d?"1":"";this.data.ogv=_.K(_.A(c,6))+"."+_.K(_.A(c,7));this.data.ogd=_.K(_.A(a,21));this.data.ogc=_.K(_.A(a,20));this.data.ogl=_.K(_.A(a,5));b&&(this.data.oggv=b)};_.n(Yc,_.Xc);
var Zc=[1,2,3,4,5,6,9,10,11,13,14,28,29,30,34,35,37,38,39,40,42,43,48,49,50,51,52,53,62,500],bd=function(a,b,c,d,e,f){Yc.call(this,a,b);_.Na(this.data,{oge:d,ogex:_.K(_.A(a,9)),ogp:_.K(_.A(a,6)),ogsr:Math.round(1/($c(d)?_.Qc(_.xc(c,3,1)):_.Qc(_.xc(c,2,1E-4)))),ogus:e});if(f){"ogw"in f&&(this.data.ogw=f.ogw,delete f.ogw);"ved"in f&&(this.data.ved=f.ved,delete f.ved);a=[];for(var g in f)0!=a.length&&a.push(","),a.push(ad(g)),a.push("."),a.push(ad(f[g]));f=a.join("");""!=f&&(this.data.ogad=f)}};
_.n(bd,Yc);var ad=function(a){a=String(a);return a.replace(".","%2E").replace(",","%2C")},$c=function(a){if(!cd){cd={};for(var b=0;b<Zc.length;b++)cd[Zc[b]]=!0}return!!cd[a]},cd=null;
var dd=function(a){_.z(this,a,0,-1,null,null)};_.v(dd,_.y);
var hd=function(){var a=ed,b=fd,c=gd;this.A=a;this.o=b;this.C=_.Qc(_.xc(a,2,1E-4),1E-4);this.D=_.Qc(_.xc(a,3,1),1);b=Math.random();this.B=_.J(_.B(a,1))&&b<this.C;this.j=_.J(_.B(a,1))&&b<this.D;a=0;_.J(_.B(c,1))&&(a|=1);_.J(_.B(c,2))&&(a|=2);_.J(_.B(c,3))&&(a|=4);this.F=a};hd.prototype.log=function(a,b){try{if($c(a)?this.j:this.B){var c=new bd(this.o,"quantum:gapiBuildLabel",this.A,a,this.F,b);_.Sc(c)}}catch(d){}};
_.id=function(a,b,c,d,e){Yc.call(this,a,b);_.Na(this.data,{jexpid:_.K(_.A(a,9)),srcpg:"prop="+_.K(_.A(a,6)),jsr:Math.round(1/d),emsg:c.name+":"+c.message});if(e){e._sn&&(e._sn="og."+e._sn);for(var f in e)this.data[encodeURIComponent(f)]=e[f]}};_.n(_.id,Yc);
_.jd=function(a){_.z(this,a,0,-1,null,null)};_.v(_.jd,_.y);
var md=function(){var a=kd;this.B=ld;this.o=_.Qc(_.xc(a,2,.001),.001);this.C=_.J(_.B(a,1))&&Math.random()<this.o;this.A=_.Qc(_.vc(a,3,1),1);this.j=0;this.qf=this.Fg=null;_.wc(a,4,!0)};
md.prototype.log=function(a,b){if(this.qf){var c=new zc;_.E(c,1,a.message);_.E(c,2,a.stack);_.E(c,3,a.lineNumber);_.E(c,5,1);var d=new _.Ac;_.G(d,40,c);this.qf.log(98,d)}try{if(this.C&&this.j<this.A){try{var e=(this.Fg||_.Hc(_.Gc.va(),"lm")).j(a,b)}catch(f){e=new _.id(this.B,"quantum:gapiBuildLabel",a,this.o,b)}_.Sc(e);this.j++}}catch(f){}};
var nd=function(a){this.j=a;this.o=void 0;this.A=[]};nd.prototype.then=function(a,b,c){this.A.push(new od(a,b,c));_.pd(this)};_.qd=function(a,b){if(void 0!==a.j||void 0!==a.o)throw Error("p");a.j=b;_.pd(a)};_.pd=function(a){if(0<a.A.length){var b=void 0!==a.j,c=void 0!==a.o;if(b||c){b=b?a.B:a.C;c=a.A;a.A=[];try{_.Ha(c,b,a)}catch(d){console.error(d)}}}};nd.prototype.B=function(a){a.o&&a.o.call(a.j,this.j)};nd.prototype.C=function(a){a.A&&a.A.call(a.j,this.o)};
var od=function(a,b,c){this.o=a;this.A=b;this.j=c};
_.rd=function(){this.B=new nd;this.o=new nd;this.F=new nd;this.C=new nd;this.D=new nd;this.H=new nd;this.K=new nd;this.j=new nd;this.A=new nd};_.h=_.rd.prototype;_.h.Yh=function(){return this.B};_.h.ki=function(){return this.o};_.h.ti=function(){return this.F};_.h.ji=function(){return this.C};_.h.ri=function(){return this.D};_.h.ui=function(){return this.H};_.h.fi=function(){return this.K};_.h.hi=function(){return this.j};_.h.Rh=function(){return this.A};_.Aa(_.rd);
var sd=function(a){_.z(this,a,0,-1,null,null)};_.v(sd,_.y);_.ud=function(){return _.F(_.td,_.Dc,1)};_.vd=function(){return _.F(_.td,_.Ec,5)};sd.prototype.eg=function(){return _.F(this,_.Bc,12)};
var wd;window.gbar_&&window.gbar_.CONFIG?wd=window.gbar_.CONFIG[0]||{}:wd=[];_.td=new sd(wd);
var kd,ld,fd,gd,ed;kd=_.F(_.td,_.jd,3)||new _.jd;ld=_.ud()||new _.Dc;_.L=new md;fd=_.ud()||new _.Dc;gd=_.vd()||new _.Ec;ed=_.F(_.td,dd,4)||new dd;_.xd=new hd;
_.t("gbar_._DumpException",function(a){_.L?_.L.log(a):console.error(a)});
_.yd=new Nc(_.L);
_.xd.log(8,{m:"BackCompat"==document.compatMode?"q":"s"});_.t("gbar.A",nd);nd.prototype.aa=nd.prototype.then;_.t("gbar.B",_.rd);_.rd.prototype.ba=_.rd.prototype.ki;_.rd.prototype.bb=_.rd.prototype.ti;_.rd.prototype.bd=_.rd.prototype.ri;_.rd.prototype.be=_.rd.prototype.ui;_.rd.prototype.bf=_.rd.prototype.Yh;_.rd.prototype.bg=_.rd.prototype.ji;_.rd.prototype.bh=_.rd.prototype.fi;_.rd.prototype.bi=_.rd.prototype.hi;_.rd.prototype.bj=_.rd.prototype.Rh;_.t("gbar.a",_.rd.va());var zd=new Fc(window);
_.Kc("api",zd);var Ad=_.vd()||new _.Ec,Bd=_.K(_.A(Ad,8));window.__PVT=Bd;_.Kc("eq",_.yd);

}catch(e){_._DumpException(e)}
try{
var Cd=function(a){_.z(this,a,0,-1,null,null)};_.v(Cd,_.y);
var Dd=function(){_.I.call(this);this.o=[];this.j=[]};_.n(Dd,_.I);Dd.prototype.A=function(a,b){this.o.push({Yd:a,options:b})};Dd.prototype.init=function(a,b,c){window.gapi={};var d=window.___jsl={};d.h=_.K(_.A(a,1));_.tc(a,12)&&(d.dpo=_.J(_.B(a,12)));d.ms=_.K(_.A(a,2));d.m=_.K(_.A(a,3));d.l=[];_.A(b,1)&&(a=_.A(b,3))&&this.j.push(a);_.A(c,1)&&(c=_.A(c,2))&&this.j.push(c);_.t("gapi.load",(0,_.q)(this.A,this));return this};
var Ed=_.F(_.td,_.Oc,14)||new _.Oc,Fd=_.F(_.td,_.Pc,9)||new _.Pc,Gd=new Cd,Hd=new Dd;Hd.init(Ed,Fd,Gd);_.Kc("gs",Hd);

}catch(e){_._DumpException(e)}
})(this.gbar_);
// Google Inc.
</script><script async="" type="text/javascript" charset="UTF-8" src="https://www.gstatic.com/og/_/js/k=og.qtm.en_US.3Q2Fmww-UG0.O/rt=j/m=qgl,q_dnp,qdid,qmd,qcwid,qmutsd,qbd,qapid,qald/exm=qaaw,qabr,qadd,qaid,qalo,qebr,qein,qhaw,qhbr,qhch,qhga,qhid,qhin,qhlo,qhmn,qhpc,qhpr,qhsf,qhtb,qhtt/d=1/ed=1/rs=AA2YrTuWr-THoJhZf_G0GDWJEiz9fL6BmQ"></script><link type="text/css" rel="stylesheet" href="https://www.gstatic.com/og/_/ss/k=og.qtm.MS6fO3HUAzQ.L.W.O/m=qdid,qmd,qcwid/excm=qaaw,qabr,qadd,qaid,qalo,qebr,qein,qhaw,qhbr,qhch,qhga,qhid,qhin,qhlo,qhmn,qhpc,qhpr,qhsf,qhtb,qhtt/d=1/ed=1/ct=zgms/rs=AA2YrTunZMz9vXN9D_fVuVUp2s6sffrErw"></head>
<body class="light-chip" style="--logo-color:rgba(238,238,238,1); background: rgb(255, 255, 255); --search-box-bg:rgba(241,243,244,1); --search-box-icon:rgba(98,99,101,1); --search-box-icon-selected:rgba(95,96,98,1); --search-box-placeholder:rgba(105,106,108,1); --search-box-results-bg:rgba(255,255,255,1); --search-box-results-bg-hovered:rgba(232,232,233,1); --search-box-results-bg-selected:rgba(219,219,220,1); --search-box-results-dim:rgba(103,104,106,1); --search-box-results-dim-selected:rgba(96,96,99,1); --search-box-results-text:rgba(32,33,36,1); --search-box-results-text-selected:rgba(32,33,36,1); --search-box-results-url:rgba(41,101,199,1); --search-box-results-url-selected:rgba(35,93,188,1); --search-box-text:rgba(32,33,36,1); --remove-match-hovered:rgba(98,99,101,0.16); --remove-match-selected-hovered:rgba(95,96,98,0.16); --remove-match-focused:rgba(95,96,98,0.32);">
  <div id="custom-bg" style="opacity: 0;"></div>
  <div id="custom-bg-preview"></div>
  <!-- Container for the OneGoogleBar HTML. -->
  <div id="one-google" class="show-element"><header class="gb_sa gb_0a gb_4e gb_ta" id="gb" role="banner" style="background-color:transparent"><div class="gb_je"><div class="gb_Hc gb_Ec gb_ta"><div class="gb_Qc"><div class="gb_rc"><div class="gb_sc"><a class="gb_we gb_tc" aria-label="Google" href="/?tab=rr&amp;authuser=0"><span class="gb_ua gb_te" aria-hidden="true"></span></a></div></div></div><div class="gb_Mc"></div></div></div><div class="gb_Vd gb_fe gb_5d gb_4d"><div class="gb_Ud gb_1c"><div class="gb_xc gb_Ea" aria-expanded="false" aria-label="Main menu" role="button" tabindex="0"><svg focusable="false" viewBox="0 0 24 24"><path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"></path></svg></div><div class="gb_xc gb_Ac gb_Ea" aria-label="Go back" role="button" tabindex="0"><svg focusable="false" viewBox="0 0 24 24"><path d="M20 11H7.83l5.59-5.59L12 4l-8 8 8 8 1.41-1.41L7.83 13H20v-2z"></path></svg></div><div class="gb_xc gb_Bc gb_Ea" aria-label="Close" role="button" tabindex="0"><svg viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path></svg></div><div class="gb_rc gb_Ea"><div class="gb_sc"><a class="gb_we gb_tc" aria-label="Google" href="/?tab=rr&amp;authuser=0"><span class="gb_ua gb_te gb_Ea" aria-hidden="true"></span></a></div></div><div class="gb_Ud gb_Zc gb_0c"><span class="gb_3c" aria-level="1" role="heading"> </span></div></div><div class="gb_Ud gb_8d gb_4d gb_1e gb_We"></div><div class="gb_9d gb_Wa gb_Ud" data-ogsr-up=""><div><div class="gb_ke gb_i gb_Ig gb_yg" data-ogbl=""><div class="gb_h gb_i"><a class="gb_g" data-pid="23" href="https://mail.google.com/mail/?tab=rm&amp;authuser=0&amp;ogbl" target="_top">Gmail</a></div><div class="gb_h gb_i"><a class="gb_g" data-pid="2" href="https://www.google.co.in/imghp?hl=en&amp;tab=ri&amp;authuser=0&amp;ogbl" target="_top">Images</a></div></div></div><div class="gb_5e"><div class="gb_Rc"><div class="gb_C gb_fd gb_i gb_Wf" data-ogsr-fb="true" data-ogsr-alt="" id="gbwa"><div class="gb_Vf"><a class="gb_D" aria-label="Google apps" href="https://www.google.co.in/intl/en/about/products?tab=rh" aria-expanded="false" role="button" tabindex="0"><svg class="gb_8e" focusable="false" viewBox="0 0 24 24"><path d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"></path></svg></a></div></div></div><div class="gb_Ra gb_fd gb_Ig gb_i gb_Wf"><div class="gb_Vf gb_Va gb_Ig gb_i"><a class="gb_D gb_Qa gb_i" aria-label="Google Account: srinidhithegreat01@gmail.com" href="https://accounts.google.com/SignOutOptions?hl=en&amp;continue=https://www.google.com%3Fhl%3Den-US" role="button" tabindex="0" aria-expanded="false"><img class="gb_Ha gbii" src="https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s32-c-mo" srcset="https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s32-c-mo 1x, https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s64-c-mo 2x " alt="" aria-hidden="true" data-noaft=""></a><div class="gb_3a"></div><div class="gb_2a"></div></div></div></div><div style="overflow: hidden; position: absolute; top: 0px; visibility: hidden; width: 328px; z-index: 991; height: 0px; margin-top: 57px; right: 0px; margin-right: 4px; transition: height 0.3s ease-in-out 0s;"><iframe role="presentation" frameborder="0" scrolling="no" src="https://ogs.google.com/u/0/widget/app?origin=chrome-search%3A%2F%2Flocal-ntp&amp;cn=app&amp;pid=1&amp;spid=243&amp;hl=en" style="height: 100%; width: 100%; visibility: hidden;"></iframe></div></div><div class="gb_4a gb_F gb_l gb_5a" aria-label="Account Information" aria-hidden="true"><div class="gb_db"><div class="gb_eb"><img class="gb_La gbip gb_ib" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///////yH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s83-c-mo" data-srcset="https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s83-c-mo 1x, https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s192-c-mo 2x " title="Profile" alt="" aria-hidden="true"><div class="gb_mb gb_ib"><a class="gb_nb gb_dg gb_ib gb_ig" aria-label="Change profile picture." href="https://myaccount.google.com/?utm_source=OGB&amp;tab=rk&amp;authuser=0"><svg class="gb_ob" enable-background="new 0 0 24 24" focusable="false" height="26" viewBox="0 0 24 24" width="18" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 14H4V7h16v12zM12 9c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4z"></path></svg></a></div></div><div class="gb_fb"><div class="gb_pb gb_qb"></div><div class="gb_rb">srinidhithegreat01@gmail.com</div><a class="gb_vb gb_eg gbp1 gb_2e gb_7c" href="https://myaccount.google.com/?utm_source=OGB&amp;tab=rk&amp;authuser=0&amp;utm_medium=act" target="_blank">Manage your Google Account</a></div></div><div class="gb_Jb gb_Mb"><div class="gb_kg gb_jc gb_Ea"><div class="gb_kc"></div></div><div class="gb_hg gb_Qb" aria-hidden="false"><a class="gb_Pb gb_0b" aria-hidden="true" href="https://www.google.com/webhp?authuser=0"><img class="gb_2b gb_ib" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///////yH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://lh3.googleusercontent.com/ogw/ADGmqu_9ZXuAeMqOTK_kM68-7ZY6xezd08pfjaTe6eX5sQ=s48-c-mo" alt="" aria-hidden="true"><div class="gb_Sb"><div><div class="gb_8b">Default</div></div><div class="gb_4b">srinidhithegreat01@gmail.com</div><div class="gb_6b">srinidhithegreat01@gmail.com</div></div></a><a class="gb_Pb" href="https://www.google.com/webhp?authuser=1"><img class="gb_2b gb_ib" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///////yH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://lh3.googleusercontent.com/ogw/ADGmqu-imyfodk336C-XyYyspkdk22IG4_v7KLEQvaKa=s48-c-mo" alt="" aria-hidden="true"><div class="gb_Sb"><div class="gb_4b">Susi Raghavan</div><div class="gb_6b">susiraghavan@gmail.com</div></div></a></div><div class="gb_Cb" aria-hidden="true"><svg class="gb_Db" focusable="false" height="20" viewBox="0 0 20 20" width="20" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M0 0h20v20H0V0z" fill="none"></path><path d="M6.18 7L10 10.82 13.82 7 15 8.17l-5 5-5-5z"></path></svg></div><a class="gb_ac gb_Ea gb_Tb" href="https://myaccount.google.com/brandaccounts?authuser=0&amp;continue=https://www.google.com%3Fhl%3Den-US&amp;service=https://www.google.com/webhp%3Fauthuser%3D%24authuser" aria-hidden="true"><div class="gb_bc"><svg focusable="false" height="20" viewBox="0 0 24 24" width="20" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M19 3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 2v10.79C16.52 14.37 13.23 14 12 14s-4.52.37-7 1.79V5h14zM5 19v-.77C6.74 16.66 10.32 16 12 16s5.26.66 7 2.23V19H5zm7-6c1.94 0 3.5-1.56 3.5-3.5S13.94 6 12 6 8.5 7.56 8.5 9.5 10.06 13 12 13zm0-5c.83 0 1.5.67 1.5 1.5S12.83 11 12 11s-1.5-.67-1.5-1.5S11.17 8 12 8z" fill="#5F6368"></path><path d="M0 0h24v24H0V0z" fill="none"></path></svg></div><div class="gb_dc gb_ec">All Brand accounts</div><svg class="gb_fc" focusable="false" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z" fill="#5F6368"></path><path d="M0 0h24v24H0z" fill="none"></path></svg></a></div><div class="gb_Ub" tabindex="-1"><a class="gb_zb gb_ag" href="https://accounts.google.com/AddSession?hl=en&amp;continue=https://www.google.com%3Fhl%3Den-US&amp;ec=GAlA8wE"><div class="gb_Ab"><svg class="gb_Bb" enable-background="new 0 0 24 24" focusable="false" height="20" viewBox="0 0 24 24" width="20" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M9 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0-6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm0 7c-2.67 0-8 1.34-8 4v3h16v-3c0-2.66-5.33-4-8-4zm6 5H3v-.99C3.2 16.29 6.3 15 9 15s5.8 1.29 6 2v1zm3-4v-3h-3V9h3V6h2v3h3v2h-3v3h-2z"></path></svg></div><div class="gb_Eb">Add another account</div></a></div><div class="gb_bg gb_Fb"><a class="gb_Hb gb_fg gb_ng gb_2e gb_7c" id="gb_71" href="https://accounts.google.com/Logout?hl=en&amp;continue=https://www.google.com%3Fhl%3Den-US&amp;timeStmp=1606885486&amp;secTok=.AG5fkS_pRC49HJbAy8QpVXr0RtcE73hFXg&amp;ec=GAdA8wE" target="_top">Sign out of all accounts</a></div><div class="gb_cg gb_wb"><a class="gb_xb gb_Lb" href="https://policies.google.com/privacy?hl=en&amp;authuser=0" target="_blank">Privacy Policy</a><span class="gb_Sa" aria-hidden="true">•</span><a class="gb_xb gb_Kb" href="https://myaccount.google.com/termsofservice?hl=en&amp;authuser=0" target="_blank">Terms of Service</a></div></div></div><div class="gb_6d gb_fe"></div></header><script>(function(){var zbu='https://id.google.com/verify/AHGvNozmrn_60nlO9isYUC3NLw1MARdypk9c40XAdVsQzLDOb579DB1P3yNUnnI8yucV-1VLMFMh2_U6rDCF9VFYLGrM03kElmCQt-KfkpitgoZVcy6APA';(function(){try{var i=new Image();i.src=zbu;if (!google.lc){google.lc = {};}
if (!google.li){google['li']= 0;}
google.lc[google.li]= i;i.onload=i.onerror=(function(lc,li){return function(){delete lc[li];}
})(google.lc,google.li);google.li++;}catch(e){}
})();})();</script></div><script type="text/javascript">this.gbar_=this.gbar_||{};(function(_){var window=this;
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.Id=!_.x||_.dc(9);_.Jd=!_.x||_.dc(9);_.Kd=_.x&&!_.bc("9");_.Ld=function(){if(!_.p.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});try{_.p.addEventListener("test",_.za,b),_.p.removeEventListener("test",_.za,b)}catch(c){}return a}();
_.Md=_.Nb?"webkitTransitionEnd":_.Jb?"otransitionend":"transitionend";

}catch(e){_._DumpException(e)}
try{
_.Nd=function(a,b,c){if(!a.o)if(c instanceof Array){c=_.la(c);for(var d=c.next();!d.done;d=c.next())_.Nd(a,b,d.value)}else{d=(0,_.q)(a.F,a,b);var e=a.D+c;a.D++;b.setAttribute("data-eqid",e);a.B[e]=d;b&&b.addEventListener?b.addEventListener(c,d,!1):b&&b.attachEvent?b.attachEvent("on"+c,d):a.C.log(Error("n`"+b))}};

}catch(e){_._DumpException(e)}
try{
var Od=document.querySelector(".gb_C .gb_D"),Pd=document.querySelector("#gb.gb_Ic");Od&&!Pd&&_.Nd(_.yd,Od,"click");

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Sd,Td,Ud,$d,ae,be,ce,de,ee,fe,ke;_.Qd=function(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]};_.Rd=function(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}};Sd=null;Td=/^[\w+/_-]+[=]{0,2}$/;Ud=function(a){return(a=a.querySelector&&a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Td.test(a)?a:""};
_.Vd=function(a){if(a&&a!=_.p)return Ud(a.document);null===Sd&&(Sd=Ud(_.p.document));return Sd};_.Wd=function(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"};_.Xd=function(a){var b=_.Wd(a);return"array"==b||"object"==b&&"number"==typeof a.length};_.Yd=function(){return Date.now()};_.Zd=function(a,b){return 0==a.lastIndexOf(b,0)};$d=/&/g;ae=/</g;be=/>/g;ce=/"/g;de=/'/g;ee=/\x00/g;fe=/[\x00&<>"']/;
_.ge=function(a,b){if(b)a=a.replace($d,"&amp;").replace(ae,"&lt;").replace(be,"&gt;").replace(ce,"&quot;").replace(de,"&#39;").replace(ee,"&#0;");else{if(!fe.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace($d,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(ae,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(be,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(ce,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(de,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(ee,"&#0;"))}return a};
_.he=function(a){var b=_.Vd(a.ownerDocument&&a.ownerDocument.defaultView);b&&a.setAttribute("nonce",b)};_.ie=function(a,b){a.src=_.Wa(b);_.he(a)};_.je=function(a){return a=_.ge(a,void 0)};ke=!_.x||_.dc(9);_.le=!_.Mb&&!_.x||_.x&&_.dc(9)||_.Mb&&_.bc("1.9.1");_.me=_.x&&!_.bc("9");_.ne=_.x||_.Jb||_.Nb;
_.oe=function(a,b){this.width=a;this.height=b};_.h=_.oe.prototype;_.h.aspectRatio=function(){return this.width/this.height};_.h.jc=function(){return!(this.width*this.height)};_.h.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};_.h.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};_.h.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
var re;_.pe=function(a,b){return(b||document).getElementsByTagName(String(a))};_.M=function(a,b){var c=b||document;if(c.getElementsByClassName)a=c.getElementsByClassName(a)[0];else{c=document;var d=b||c;a=d.querySelectorAll&&d.querySelector&&a?d.querySelector(a?"."+a:""):_.qe(c,"*",a,b)[0]||null}return a||null};
_.qe=function(a,b,c,d){a=d||a;b=b&&"*"!=b?String(b).toUpperCase():"";if(a.querySelectorAll&&a.querySelector&&(b||c))return a.querySelectorAll(b+(c?"."+c:""));if(c&&a.getElementsByClassName){a=a.getElementsByClassName(c);if(b){d={};for(var e=0,f=0,g;g=a[f];f++)b==g.nodeName&&(d[e++]=g);d.length=e;return d}return a}a=a.getElementsByTagName(b||"*");if(c){d={};for(f=e=0;g=a[f];f++)b=g.className,"function"==typeof b.split&&_.ca(b.split(/\s+/),c)&&(d[e++]=g);d.length=e;return d}return a};
_.se=function(a,b){_.La(b,function(c,d){c&&"object"==typeof c&&c.Rb&&(c=c.Fb());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:re.hasOwnProperty(d)?a.setAttribute(re[d],c):_.Zd(d,"aria-")||_.Zd(d,"data-")?a.setAttribute(d,c):a[d]=c})};re={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};
_.ve=function(a,b){var c=String(b[0]),d=b[1];if(!ke&&d&&(d.name||d.type)){c=["<",c];d.name&&c.push(' name="',_.je(d.name),'"');if(d.type){c.push(' type="',_.je(d.type),'"');var e={};_.Na(e,d);delete e.type;d=e}c.push(">");c=c.join("")}c=_.te(a,c);d&&("string"===typeof d?c.className=d:Array.isArray(d)?c.className=d.join(" "):_.se(c,d));2<b.length&&_.ue(a,c,b,2);return c};
_.ue=function(a,b,c,d){function e(k){k&&b.appendChild("string"===typeof k?a.createTextNode(k):k)}for(;d<c.length;d++){var f=c[d];if(!_.Xd(f)||_.Ba(f)&&0<f.nodeType)e(f);else{a:{if(f&&"number"==typeof f.length){if(_.Ba(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}_.Ha(g?_.Qd(f):f,e)}}};_.we=function(a){return _.te(document,a)};
_.te=function(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)};_.xe=function(a){for(var b;b=a.firstChild;)a.removeChild(b)};_.ye=function(a){return a&&a.parentNode?a.parentNode.removeChild(a):null};_.ze=function(a){return _.Ba(a)&&1==a.nodeType};_.Ae=function(a){return 9==a.nodeType?a:a.ownerDocument||a.document};_.Be=function(a,b,c){for(var d=0;a&&(null==c||d<=c);){if(b(a))return a;a=a.parentNode;d++}return null};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ce=function(a,b){this.A=a;this.B=b;this.o=0;this.j=null};Ce.prototype.get=function(){if(0<this.o){this.o--;var a=this.j;this.j=a.next;a.next=null}else a=this.A();return a};var De=function(a,b){a.B(b);100>a.o&&(a.o++,b.next=a.j,a.j=b)};
var Ee=function(a){_.p.setTimeout(function(){throw a;},0)},Fe,Ge=function(){var a=_.p.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!_.w("Presto")&&(a=function(){var e=_.we("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),k="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=(0,_.q)(function(l){if(("*"==
k||l.origin==k)&&l.data==g)this.port1.onmessage()},this);f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,k)}}});if("undefined"!==typeof a&&!_.rb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Of;c.Of=null;e()}};return function(e){d.next={Of:e};d=d.next;b.port2.postMessage(0)}}return function(e){_.p.setTimeout(e,0)}};
var He=function(){this.o=this.j=null},Je=new Ce(function(){return new Ie},function(a){a.reset()});He.prototype.add=function(a,b){var c=Je.get();c.set(a,b);this.o?this.o.next=c:this.j=c;this.o=c};He.prototype.remove=function(){var a=null;this.j&&(a=this.j,this.j=this.j.next,this.j||(this.o=null),a.next=null);return a};var Ie=function(){this.next=this.scope=this.hc=null};Ie.prototype.set=function(a,b){this.hc=a;this.scope=b;this.next=null};
Ie.prototype.reset=function(){this.next=this.scope=this.hc=null};
var Ke,Le,Me,Ne,Pe;_.Oe=function(a,b){Ke||Le();Me||(Ke(),Me=!0);Ne.add(a,b)};Le=function(){if(_.p.Promise&&_.p.Promise.resolve){var a=_.p.Promise.resolve(void 0);Ke=function(){a.then(Pe)}}else Ke=function(){var b=Pe;"function"!==typeof _.p.setImmediate||_.p.Window&&_.p.Window.prototype&&!_.w("Edge")&&_.p.Window.prototype.setImmediate==_.p.setImmediate?(Fe||(Fe=Ge()),Fe(b)):_.p.setImmediate(b)}};Me=!1;Ne=new He;
Pe=function(){for(var a;a=Ne.remove();){try{a.hc.call(a.scope)}catch(b){Ee(b)}De(Je,a)}Me=!1};
_.Qe=function(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}};
var Te,ff,bf,$e,af,gf,ef,hf;_.Se=function(a){this.j=0;this.F=void 0;this.B=this.o=this.A=null;this.C=this.D=!1;if(a!=_.za)try{var b=this;a.call(void 0,function(c){_.Re(b,2,c)},function(c){_.Re(b,3,c)})}catch(c){_.Re(this,3,c)}};Te=function(){this.next=this.context=this.o=this.A=this.j=null;this.B=!1};Te.prototype.reset=function(){this.context=this.o=this.A=this.j=null;this.B=!1};
var Ue=new Ce(function(){return new Te},function(a){a.reset()}),Ve=function(a,b,c){var d=Ue.get();d.A=a;d.o=b;d.context=c;return d};_.Se.prototype.then=function(a,b,c){return We(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};_.Se.prototype.$goog_Thenable=!0;_.Xe=function(a,b){return We(a,null,b,void 0)};_.Se.prototype.cancel=function(a){if(0==this.j){var b=new _.Ye(a);_.Oe(function(){Ze(this,b)},this)}};
var Ze=function(a,b){if(0==a.j)if(a.A){var c=a.A;if(c.o){for(var d=0,e=null,f=null,g=c.o;g&&(g.B||(d++,g.j==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.j&&1==d?Ze(c,b):(f?(d=f,d.next==c.B&&(c.B=d),d.next=d.next.next):$e(c),af(c,e,3,b)))}a.A=null}else _.Re(a,3,b)},cf=function(a,b){a.o||2!=a.j&&3!=a.j||bf(a);a.B?a.B.next=b:a.o=b;a.B=b},We=function(a,b,c,d){var e=Ve(null,null,null);e.j=new _.Se(function(f,g){e.A=b?function(k){try{var l=b.call(d,k);f(l)}catch(m){g(m)}}:f;e.o=c?function(k){try{var l=
c.call(d,k);void 0===l&&k instanceof _.Ye?g(k):f(l)}catch(m){g(m)}}:g});e.j.A=a;cf(a,e);return e.j};_.Se.prototype.K=function(a){this.j=0;_.Re(this,2,a)};_.Se.prototype.J=function(a){this.j=0;_.Re(this,3,a)};_.Re=function(a,b,c){0==a.j&&(a===c&&(b=3,c=new TypeError("q")),a.j=1,_.df(c,a.K,a.J,a)||(a.F=c,a.j=b,a.A=null,bf(a),3!=b||c instanceof _.Ye||ef(a,c)))};
_.df=function(a,b,c,d){if(a instanceof _.Se)return cf(a,Ve(b||_.za,c||null,d)),!0;if(_.Qe(a))return a.then(b,c,d),!0;if(_.Ba(a))try{var e=a.then;if("function"===typeof e)return ff(a,e,b,c,d),!0}catch(f){return c.call(d,f),!0}return!1};ff=function(a,b,c,d,e){var f=!1,g=function(l){f||(f=!0,c.call(e,l))},k=function(l){f||(f=!0,d.call(e,l))};try{b.call(a,g,k)}catch(l){k(l)}};bf=function(a){a.D||(a.D=!0,_.Oe(a.H,a))};$e=function(a){var b=null;a.o&&(b=a.o,a.o=b.next,b.next=null);a.o||(a.B=null);return b};
_.Se.prototype.H=function(){for(var a;a=$e(this);)af(this,a,this.j,this.F);this.D=!1};af=function(a,b,c,d){if(3==c&&b.o&&!b.B)for(;a&&a.C;a=a.A)a.C=!1;if(b.j)b.j.A=null,gf(b,c,d);else try{b.B?b.A.call(b.context):gf(b,c,d)}catch(e){hf.call(null,e)}De(Ue,b)};gf=function(a,b,c){2==b?a.A.call(a.context,c):a.o&&a.o.call(a.context,c)};ef=function(a,b){a.C=!0;_.Oe(function(){a.C&&hf.call(null,b)})};hf=Ee;_.Ye=function(a){_.aa.call(this,a)};_.v(_.Ye,_.aa);_.Ye.prototype.name="cancel";

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var lf;_.jf=function(a,b){b=(0,_.ba)(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c};_.kf=function(a,b){a=a.split(".");b=b||_.p;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b};lf=function(a,b){for(var c in a)if(b.call(void 0,a[c],c,a))return!0;return!1};_.mf=function(a,b){try{return _.Gb(a[b]),!0}catch(c){}return!1};
_.of=function(a,b){this.type="undefined"!=typeof _.nf&&a instanceof _.nf?String(a):a;this.currentTarget=this.target=b;this.defaultPrevented=this.j=!1};_.of.prototype.stopPropagation=function(){this.j=!0};_.of.prototype.preventDefault=function(){this.defaultPrevented=!0};
_.pf=function(a,b){_.of.call(this,a?a.type:"");this.relatedTarget=this.currentTarget=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=this.offsetY=this.offsetX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.Va=null;a&&this.init(a,b)};_.v(_.pf,_.of);var qf={2:"touch",3:"pen",4:"mouse"};
_.pf.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.currentTarget=b;(b=a.relatedTarget)?_.Mb&&(_.mf(b,"nodeName")||(b=null)):"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.offsetX=_.Nb||void 0!==
a.offsetX?a.offsetX:a.layerX,this.offsetY=_.Nb||void 0!==a.offsetY?a.offsetY:a.layerY,this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===
typeof a.pointerType?a.pointerType:qf[a.pointerType]||"";this.state=a.state;this.Va=a;a.defaultPrevented&&this.preventDefault()};_.pf.prototype.stopPropagation=function(){_.pf.U.stopPropagation.call(this);this.Va.stopPropagation?this.Va.stopPropagation():this.Va.cancelBubble=!0};_.pf.prototype.preventDefault=function(){_.pf.U.preventDefault.call(this);var a=this.Va;if(a.preventDefault)a.preventDefault();else if(a.returnValue=!1,_.Kd)try{if(a.ctrlKey||112<=a.keyCode&&123>=a.keyCode)a.keyCode=-1}catch(b){}};
var tf;_.rf="closure_listenable_"+(1E6*Math.random()|0);_.sf=function(a){return!(!a||!a[_.rf])};tf=0;
var uf;uf=function(a,b,c,d,e){this.listener=a;this.j=null;this.src=b;this.type=c;this.capture=!!d;this.oe=e;this.key=++tf;this.sd=this.Vd=!1};_.vf=function(a){a.sd=!0;a.listener=null;a.j=null;a.src=null;a.oe=null};
_.wf=function(a){this.src=a;this.j={};this.o=0};_.wf.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.j[f];a||(a=this.j[f]=[],this.o++);var g=xf(a,b,d,e);-1<g?(b=a[g],c||(b.Vd=!1)):(b=new uf(b,this.src,f,!!d,e),b.Vd=c,a.push(b));return b};_.wf.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.j))return!1;var e=this.j[a];b=xf(e,b,c,d);return-1<b?(_.vf(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.j[a],this.o--),!0):!1};
_.yf=function(a,b){var c=b.type;if(!(c in a.j))return!1;var d=_.jf(a.j[c],b);d&&(_.vf(b),0==a.j[c].length&&(delete a.j[c],a.o--));return d};_.wf.prototype.de=function(a,b){a=this.j[a.toString()];var c=[];if(a)for(var d=0;d<a.length;++d){var e=a[d];e.capture==b&&c.push(e)}return c};_.wf.prototype.Dd=function(a,b,c,d){a=this.j[a.toString()];var e=-1;a&&(e=xf(a,b,c,d));return-1<e?a[e]:null};
_.wf.prototype.hasListener=function(a,b){var c=void 0!==a,d=c?a.toString():"",e=void 0!==b;return lf(this.j,function(f){for(var g=0;g<f.length;++g)if(!(c&&f[g].type!=d||e&&f[g].capture!=b))return!0;return!1})};var xf=function(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.sd&&f.listener==b&&f.capture==!!c&&f.oe==d)return e}return-1};
var zf,Af,Bf,Ef,Gf,Hf,Mf,Lf,If,Nf;zf="closure_lm_"+(1E6*Math.random()|0);Af={};Bf=0;_.N=function(a,b,c,d,e){if(d&&d.once)return _.Cf(a,b,c,d,e);if(Array.isArray(b)){for(var f=0;f<b.length;f++)_.N(a,b[f],c,d,e);return null}c=_.Df(c);return _.sf(a)?a.L(b,c,_.Ba(d)?!!d.capture:!!d,e):Ef(a,b,c,!1,d,e)};
Ef=function(a,b,c,d,e,f){if(!b)throw Error("r");var g=_.Ba(e)?!!e.capture:!!e,k=_.Ff(a);k||(a[zf]=k=new _.wf(a));c=k.add(b,c,d,g,f);if(c.j)return c;d=Gf();c.j=d;d.src=a;d.listener=c;if(a.addEventListener)_.Ld||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Hf(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("s");Bf++;return c};
Gf=function(){var a=If,b=_.Jd?function(c){return a.call(b.src,b.listener,c)}:function(c){c=a.call(b.src,b.listener,c);if(!c)return c};return b};_.Cf=function(a,b,c,d,e){if(Array.isArray(b)){for(var f=0;f<b.length;f++)_.Cf(a,b[f],c,d,e);return null}c=_.Df(c);return _.sf(a)?a.wb(b,c,_.Ba(d)?!!d.capture:!!d,e):Ef(a,b,c,!0,d,e)};
_.Jf=function(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)_.Jf(a,b[f],c,d,e);else d=_.Ba(d)?!!d.capture:!!d,c=_.Df(c),_.sf(a)?a.Ca(b,c,d,e):a&&(a=_.Ff(a))&&(b=a.Dd(b,c,d,e))&&_.Kf(b)};
_.Kf=function(a){if("number"===typeof a||!a||a.sd)return!1;var b=a.src;if(_.sf(b))return b.ah(a);var c=a.type,d=a.j;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Hf(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Bf--;(c=_.Ff(b))?(_.yf(c,a),0==c.o&&(c.src=null,b[zf]=null)):_.vf(a);return!0};Hf=function(a){return a in Af?Af[a]:Af[a]="on"+a};
Mf=function(a,b,c,d){var e=!0;if(a=_.Ff(a))if(b=a.j[b.toString()])for(b=b.concat(),a=0;a<b.length;a++){var f=b[a];f&&f.capture==c&&!f.sd&&(f=Lf(f,d),e=e&&!1!==f)}return e};Lf=function(a,b){var c=a.listener,d=a.oe||a.src;a.Vd&&_.Kf(a);return c.call(d,b)};
If=function(a,b){if(a.sd)return!0;if(!_.Jd){var c=b||_.kf("window.event");b=new _.pf(c,this);var d=!0;if(!(0>c.keyCode||void 0!=c.returnValue)){a:{var e=!1;if(0==c.keyCode)try{c.keyCode=-1;break a}catch(g){e=!0}if(e||void 0==c.returnValue)c.returnValue=!0}c=[];for(e=b.currentTarget;e;e=e.parentNode)c.push(e);a=a.type;for(e=c.length-1;!b.j&&0<=e;e--){b.currentTarget=c[e];var f=Mf(c[e],a,!0,b);d=d&&f}for(e=0;!b.j&&e<c.length;e++)b.currentTarget=c[e],f=Mf(c[e],a,!1,b),d=d&&f}return d}return Lf(a,new _.pf(b,
this))};_.Ff=function(a){a=a[zf];return a instanceof _.wf?a:null};Nf="__closure_events_fn_"+(1E9*Math.random()>>>0);_.Df=function(a){if("function"===typeof a)return a;a[Nf]||(a[Nf]=function(b){return a.handleEvent(b)});return a[Nf]};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Tf,ag;_.Of=function(a){a&&"function"==typeof a.ta&&a.ta()};_.Pf=function(a,b){b=_.Rd(_.Of,b);a.Pa?b():(a.Kb||(a.Kb=[]),a.Kb.push(b))};_.Qf=function(a){var b=[],c=0,d;for(d in a)b[c++]=a[d];return b};_.Rf=function(a,b){if((0,_.Cb)())for(;a.lastChild;)a.removeChild(a.lastChild);a.innerHTML=_.yb(b)};_.Sf=function(a){var b=0,c;for(c in a.j){for(var d=a.j[c],e=0;e<d.length;e++)++b,_.vf(d[e]);delete a.j[c];a.o--}};_.Uf=function(a,b){return"string"===typeof b?a.getElementById(b):b};
_.Vf=function(a){return"CSS1Compat"==a.compatMode};_.Wf=function(a){a=(a||window).document;a=_.Vf(a)?a.documentElement:a.body;return new _.oe(a.clientWidth,a.clientHeight)};_.Xf=function(a){return a?a.parentWindow||a.defaultView:window};_.Yf=function(a){return _.le&&void 0!=a.children?a.children:_.Ia(a.childNodes,function(b){return 1==b.nodeType})};
_.Zf=function(a,b){if(!a||!b)return!1;if(a.contains&&1==b.nodeType)return a==b||a.contains(b);if("undefined"!=typeof a.compareDocumentPosition)return a==b||!!(a.compareDocumentPosition(b)&16);for(;b&&a!=b;)b=b.parentNode;return b==a};_.$f=function(a){try{var b=a&&a.activeElement;return b&&b.nodeName?b:null}catch(c){return null}};ag=function(a){this.j=a||_.p.document||document};_.h=ag.prototype;_.h.G=function(a){return _.Uf(this.j,a)};_.h.Da=function(a,b,c){return _.ve(this.j,arguments)};
_.h.createElement=function(a){return _.te(this.j,a)};_.h.he=function(a,b){a.appendChild(b)};_.h.lg=_.xe;_.h.ie=_.ye;_.h.wi=_.Yf;_.h.kg=_.Zf;_.bg=function(a){return a?new ag(_.Ae(a)):Tf||(Tf=new ag)};_.O=function(){_.I.call(this);this.Eb=new _.wf(this);this.rh=this;this.Nd=null};_.v(_.O,_.I);_.O.prototype[_.rf]=!0;_.h=_.O.prototype;_.h.mi=function(){return this.Nd};_.h.Mc=function(a){this.Nd=a};_.h.addEventListener=function(a,b,c,d){_.N(this,a,b,c,d)};
_.h.removeEventListener=function(a,b,c,d){_.Jf(this,a,b,c,d)};
_.h.dispatchEvent=function(a){var b,c=this.Nd;if(c)for(b=[];c;c=c.Nd)b.push(c);c=this.rh;var d=a.type||a;if("string"===typeof a)a=new _.of(a,c);else if(a instanceof _.of)a.target=a.target||c;else{var e=a;a=new _.of(d,c);_.Na(a,e)}e=!0;if(b)for(var f=b.length-1;!a.j&&0<=f;f--){var g=a.currentTarget=b[f];e=cg(g,d,!0,a)&&e}a.j||(g=a.currentTarget=c,e=cg(g,d,!0,a)&&e,a.j||(e=cg(g,d,!1,a)&&e));if(b)for(f=0;!a.j&&f<b.length;f++)g=a.currentTarget=b[f],e=cg(g,d,!1,a)&&e;return e};
_.h.S=function(){_.O.U.S.call(this);this.Eb&&_.Sf(this.Eb);this.Nd=null};_.h.L=function(a,b,c,d){return this.Eb.add(String(a),b,!1,c,d)};_.h.wb=function(a,b,c,d){return this.Eb.add(String(a),b,!0,c,d)};_.h.Ca=function(a,b,c,d){return this.Eb.remove(String(a),b,c,d)};_.h.ah=function(a){return _.yf(this.Eb,a)};
var cg=function(a,b,c,d){b=a.Eb.j[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.sd&&g.capture==c){var k=g.listener,l=g.oe||g.src;g.Vd&&a.ah(g);e=!1!==k.call(l,d)&&e}}return e&&!d.defaultPrevented};_.O.prototype.de=function(a,b){return this.Eb.de(String(a),b)};_.O.prototype.Dd=function(a,b,c,d){return this.Eb.Dd(String(a),b,c,d)};_.O.prototype.hasListener=function(a,b){return this.Eb.hasListener(void 0!==a?String(a):void 0,b)};
_.dg=function(a,b){_.O.call(this);this.o=a||1;this.j=b||_.p;this.A=(0,_.q)(this.Zk,this);this.B=_.Yd()};_.v(_.dg,_.O);_.h=_.dg.prototype;_.h.yc=!1;_.h.Mb=null;_.h.Zk=function(){if(this.yc){var a=_.Yd()-this.B;0<a&&a<.8*this.o?this.Mb=this.j.setTimeout(this.A,this.o-a):(this.Mb&&(this.j.clearTimeout(this.Mb),this.Mb=null),this.dispatchEvent("tick"),this.yc&&(this.stop(),this.start()))}};_.h.start=function(){this.yc=!0;this.Mb||(this.Mb=this.j.setTimeout(this.A,this.o),this.B=_.Yd())};
_.h.stop=function(){this.yc=!1;this.Mb&&(this.j.clearTimeout(this.Mb),this.Mb=null)};_.h.S=function(){_.dg.U.S.call(this);this.stop();delete this.j};_.eg=function(a,b,c){if("function"===typeof a)c&&(a=(0,_.q)(a,c));else if(a&&"function"==typeof a.handleEvent)a=(0,_.q)(a.handleEvent,a);else throw Error("t");return 2147483647<Number(b)?-1:_.p.setTimeout(a,b||0)};_.fg=function(a){_.p.clearTimeout(a)};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.gg=function(a){return/^[\s\xa0]*$/.test(a)};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var hg;hg=[1,4,2];_.ig=function(a){return(_.Id?0==a.Va.button:"click"==a.type?!0:!!(a.Va.button&hg[0]))&&!(_.Ob&&a.ctrlKey)};_.jg=function(a){_.I.call(this);this.$=a;this.W={}};_.v(_.jg,_.I);var kg=[];_.jg.prototype.L=function(a,b,c,d){return lg(this,a,b,c,d)};_.jg.prototype.A=function(a,b,c,d,e){return lg(this,a,b,c,d,e)};
var lg=function(a,b,c,d,e,f){Array.isArray(c)||(c&&(kg[0]=c.toString()),c=kg);for(var g=0;g<c.length;g++){var k=_.N(b,c[g],d||a.handleEvent,e||!1,f||a.$||a);if(!k)break;a.W[k.key]=k}return a};_.jg.prototype.wb=function(a,b,c,d){return mg(this,a,b,c,d)};var mg=function(a,b,c,d,e,f){if(Array.isArray(c))for(var g=0;g<c.length;g++)mg(a,b,c[g],d,e,f);else{b=_.Cf(b,c,d||a.handleEvent,e,f||a.$||a);if(!b)return a;a.W[b.key]=b}return a};
_.jg.prototype.Ca=function(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)this.Ca(a,b[f],c,d,e);else c=c||this.handleEvent,d=_.Ba(d)?!!d.capture:!!d,e=e||this.$||this,c=_.Df(c),d=!!d,b=_.sf(a)?a.Dd(b,c,d,e):a?(a=_.Ff(a))?a.Dd(b,c,d,e):null:null,b&&(_.Kf(b),delete this.W[b.key]);return this};_.ng=function(a){_.La(a.W,function(b,c){this.W.hasOwnProperty(c)&&_.Kf(b)},a);a.W={}};_.jg.prototype.S=function(){_.jg.U.S.call(this);_.ng(this)};
_.jg.prototype.handleEvent=function(){throw Error("v");};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var pg,qg,rg;_.og=function(a,b){var c=a.length-b.length;return 0<=c&&a.indexOf(b,c)==c};pg=function(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""};qg=function(a){return a.classList?a.classList:pg(a).match(/\S+/g)||[]};rg=function(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)};_.P=function(a,b){return a.classList?a.classList.contains(b):_.ca(qg(a),b)};
_.R=function(a,b){if(a.classList)a.classList.add(b);else if(!_.P(a,b)){var c=pg(a);rg(a,c+(0<c.length?" "+b:b))}};_.sg=function(a,b){if(a.classList)_.Ha(b,function(e){_.R(a,e)});else{var c={};_.Ha(qg(a),function(e){c[e]=!0});_.Ha(b,function(e){c[e]=!0});b="";for(var d in c)b+=0<b.length?" "+d:d;rg(a,b)}};_.S=function(a,b){a.classList?a.classList.remove(b):_.P(a,b)&&rg(a,_.Ia(qg(a),function(c){return c!=b}).join(" "))};
_.ug=function(a,b){a.classList?_.Ha(b,function(c){_.S(a,c)}):rg(a,_.Ia(qg(a),function(c){return!_.ca(b,c)}).join(" "))};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var yg,Bg,Fg,Gg;_.vg=function(a,b,c){return 2>=arguments.length?Array.prototype.slice.call(a,b):Array.prototype.slice.call(a,b,c)};_.wg=function(a,b,c,d){Array.prototype.splice.apply(a,_.vg(arguments,1))};_.xg=function(a){return new _.oe(a.width,a.height)};yg=0;_.zg=function(a){return Object.prototype.hasOwnProperty.call(a,_.Ca)&&a[_.Ca]||(a[_.Ca]=++yg)};_.Ag=function(a){return String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()})};
Bg=function(a){return a.replace(/(^|[\s]+)([a-z])/g,function(b,c,d){return c+d.toUpperCase()})};_.Cg=function(a,b){return a==b?!0:a&&b?a.width==b.width&&a.height==b.height:!1};_.Dg=function(a,b,c){return _.ve(document,arguments)};_.Eg=function(a,b){if("textContent"in a)a.textContent=b;else if(3==a.nodeType)a.data=String(b);else if(a.firstChild&&3==a.firstChild.nodeType){for(;a.lastChild!=a.firstChild;)a.removeChild(a.lastChild);a.firstChild.data=String(b)}else _.xe(a),a.appendChild(_.Ae(a).createTextNode(String(b)))};
Fg={SCRIPT:1,STYLE:1,HEAD:1,IFRAME:1,OBJECT:1};Gg={IMG:" ",BR:"\n"};_.Hg=function(a,b,c){if(!(a.nodeName in Fg))if(3==a.nodeType)c?b.push(String(a.nodeValue).replace(/(\r\n|\r|\n)/g,"")):b.push(a.nodeValue);else if(a.nodeName in Gg)b.push(Gg[a.nodeName]);else for(a=a.firstChild;a;)_.Hg(a,b,c),a=a.nextSibling};
var Kg,Ig;_.Jg=function(a,b,c){if("string"===typeof b)(b=Ig(a,b))&&(a.style[b]=c);else for(var d in b){c=a;var e=b[d],f=Ig(c,d);f&&(c.style[f]=e)}};Kg={};Ig=function(a,b){var c=Kg[b];if(!c){var d=_.Ag(b);c=d;void 0===a.style[d]&&(d=(_.Nb?"Webkit":_.Mb?"Moz":_.x?"ms":_.Jb?"O":null)+Bg(d),void 0!==a.style[d]&&(c=d));Kg[b]=c}return c};_.Lg=function(a,b){var c=a.style[_.Ag(b)];return"undefined"!==typeof c?c:a.style[Ig(a,b)]||""};
_.Mg=function(a,b){var c=_.Ae(a);return c.defaultView&&c.defaultView.getComputedStyle&&(a=c.defaultView.getComputedStyle(a,null))?a[b]||a.getPropertyValue(b)||"":""};_.Ng=function(a,b){return _.Mg(a,b)||(a.currentStyle?a.currentStyle[b]:null)||a.style&&a.style[b]};_.Og=function(a){try{return a.getBoundingClientRect()}catch(b){return{left:0,top:0,right:0,bottom:0}}};_.Pg=function(a,b){"number"==typeof a&&(a=(b?Math.round(a):a)+"px");return a};
_.Rg=function(a){var b=_.Qg;if("none"!=_.Ng(a,"display"))return b(a);var c=a.style,d=c.display,e=c.visibility,f=c.position;c.visibility="hidden";c.position="absolute";c.display="inline";a=b(a);c.display=d;c.position=f;c.visibility=e;return a};_.Qg=function(a){var b=a.offsetWidth,c=a.offsetHeight,d=_.Nb&&!b&&!c;return(void 0===b||d)&&a.getBoundingClientRect?(a=_.Og(a),new _.oe(a.right-a.left,a.bottom-a.top)):new _.oe(b,c)};_.Sg=_.Mb?"MozUserSelect":_.Nb||_.Kb?"WebkitUserSelect":null;

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Tg,Vg;Tg=function(a,b){return null!==a&&b in a?a[b]:void 0};_.Ug=function(a){if(48<=a&&57>=a||96<=a&&106>=a||65<=a&&90>=a||(_.Nb||_.Kb)&&0==a)return!0;switch(a){case 32:case 43:case 63:case 64:case 107:case 109:case 110:case 111:case 186:case 59:case 189:case 187:case 61:case 188:case 190:case 191:case 192:case 222:case 219:case 220:case 221:case 163:case 58:return!0;case 173:return _.Mb;default:return!1}};
Vg=function(a){switch(a){case 61:return 187;case 59:return 186;case 173:return 189;case 224:return 91;case 0:return 224;default:return a}};_.Wg=function(a){if(_.Mb)a=Vg(a);else if(_.Ob&&_.Nb)switch(a){case 93:a=91}return a};
_.Xg=function(a,b,c,d,e,f){if(_.Nb&&!_.bc("525"))return!0;if(_.Ob&&e)return _.Ug(a);if(e&&!d)return!1;if(!_.Mb){"number"===typeof b&&(b=_.Wg(b));var g=17==b||18==b||_.Ob&&91==b;if((!c||_.Ob)&&g||_.Ob&&16==b&&(d||f))return!1}if((_.Nb||_.Kb)&&d&&c)switch(a){case 220:case 219:case 221:case 192:case 186:case 189:case 187:case 188:case 190:case 191:case 192:case 222:return!1}if(_.x&&d&&b==a)return!1;switch(a){case 13:return _.Mb?f||e?!1:!(c&&d):!0;case 27:return!(_.Nb||_.Kb||_.Mb)}return _.Mb&&(d||e||
f)?!1:_.Ug(a)};_.Yg=function(){};_.Aa(_.Yg);_.Yg.prototype.j=0;_.Zg=function(a){return":"+(a.j++).toString(36)};
var $g,dh;_.ah=function(a){_.O.call(this);this.j=a||_.bg();this.sa=$g;this.Y=null;this.Ea=!1;this.o=null;this.M=void 0;this.K=this.C=this.A=this.D=null;this.Oa=!1};_.v(_.ah,_.O);_.ah.prototype.Ya=_.Yg.va();$g=null;_.bh=function(a){return a.Y||(a.Y=_.Zg(a.Ya))};_.ah.prototype.G=function(){return this.o};_.ch=function(a){a.M||(a.M=new _.jg(a));return a.M};
dh=function(a,b){if(a==b)throw Error("x");var c;if(c=b&&a.A&&a.Y){c=a.A;var d=a.Y;c=c.K&&d?Tg(c.K,d)||null:null}if(c&&a.A!=b)throw Error("x");a.A=b;_.ah.U.Mc.call(a,b)};_.ah.prototype.Mc=function(a){if(this.A&&this.A!=a)throw Error("y");_.ah.U.Mc.call(this,a)};_.ah.prototype.Nb=function(){this.o=this.j.createElement("DIV")};_.ah.prototype.La=function(a){eh(this,a)};var eh=function(a,b,c){if(a.Ea)throw Error("z");a.o||a.Nb();b?b.insertBefore(a.o,c||null):a.j.j.body.appendChild(a.o);a.A&&!a.A.Ea||a.Ga()};
_.h=_.ah.prototype;_.h.Nf=function(){return!0};_.h.$b=function(a){this.o=a};_.h.Ga=function(){this.Ea=!0;_.fh(this,function(a){!a.Ea&&a.G()&&a.Ga()})};_.h.lb=function(){_.fh(this,function(a){a.Ea&&a.lb()});this.M&&_.ng(this.M);this.Ea=!1};_.h.S=function(){this.Ea&&this.lb();this.M&&(this.M.ta(),delete this.M);_.fh(this,function(a){a.ta()});!this.Oa&&this.o&&_.ye(this.o);this.A=this.D=this.o=this.K=this.C=null;_.ah.U.S.call(this)};
_.h.Cc=function(a,b,c){if(a.Ea&&(c||!this.Ea))throw Error("z");if(0>b||b>_.gh(this))throw Error("B");this.K&&this.C||(this.K={},this.C=[]);if(a.A==this){var d=_.bh(a);this.K[d]=a;_.jf(this.C,a)}else{d=this.K;var e=_.bh(a);if(null!==d&&e in d)throw Error("i`"+e);d[e]=a}dh(a,this);_.wg(this.C,b,0,a);a.Ea&&this.Ea&&a.A==this?(c=this.hd(),(c.childNodes[b]||null)!=a.G()&&(a.G().parentElement==c&&c.removeChild(a.G()),b=c.childNodes[b]||null,c.insertBefore(a.G(),b))):c?(this.o||this.Nb(),b=_.hh(this,b+1),
eh(a,this.hd(),b?b.o:null)):this.Ea&&!a.Ea&&a.o&&a.o.parentNode&&1==a.o.parentNode.nodeType&&a.Ga()};_.h.hd=function(){return this.o};_.gh=function(a){return a.C?a.C.length:0};_.hh=function(a,b){return a.C?a.C[b]||null:null};_.fh=function(a,b,c){a.C&&_.Ha(a.C,b,c)};_.ah.prototype.Fd=function(a,b){if(a){var c="string"===typeof a?a:_.bh(a);a=this.K&&c?Tg(this.K,c)||null:null;if(c&&a){var d=this.K;c in d&&delete d[c];_.jf(this.C,a);b&&(a.lb(),a.o&&_.ye(a.o));dh(a,null)}}if(!a)throw Error("C");return a};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var ih;
_.jh=function(a,b){b?a.setAttribute("role",b):a.removeAttribute("role")};_.T=function(a,b,c){Array.isArray(c)&&(c=c.join(" "));var d="aria-"+b;""===c||void 0==c?(ih||(ih={atomic:!1,autocomplete:"none",dropeffect:"none",haspopup:!1,live:"off",multiline:!1,multiselectable:!1,orientation:"vertical",readonly:!1,relevant:"additions text",required:!1,sort:"none",busy:!1,disabled:!1,hidden:!1,invalid:"false"}),c=ih,b in c?a.setAttribute(d,c[b]):a.removeAttribute(d)):a.setAttribute(d,c)};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.kh=!_.x&&!_.ub();

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.mh=function(a,b,c){_.lh.L(b,c,void 0,a.$||a,a);return a};_.nh=function(a,b){b=b instanceof _.cb?b:_.jb(b);a.href=_.db(b)};_.oh=function(a,b){var c=b||document;return c.querySelectorAll&&c.querySelector?c.querySelectorAll("."+a):_.qe(document,"*",a,b)};_.ph=function(a,b){b.parentNode&&b.parentNode.insertBefore(a,b.nextSibling)};_.qh=function(a,b){return b?_.Be(a,function(c){return!b||"string"===typeof c.className&&_.ca(c.className.split(/\s+/),b)},void 0):null};
var rh,sh;rh=function(){};_.lh=new rh;sh=["click","keydown","keyup"];rh.prototype.L=function(a,b,c,d,e){var f=function(g){var k=_.Df(b),l=_.ze(g.target)?g.target.getAttribute("role")||null:null;"click"==g.type&&_.ig(g)?k.call(d,g):13!=g.keyCode&&3!=g.keyCode||"keyup"==g.type?32!=g.keyCode||"keyup"!=g.type||"button"!=l&&"tab"!=l||(k.call(d,g),g.preventDefault()):(g.type="keypress",k.call(d,g))};f.yb=b;f.Lk=d;e?e.L(a,sh,f,c):_.N(a,sh,f,c)};
rh.prototype.Ca=function(a,b,c,d,e){for(var f,g=0;f=sh[g];g++){var k=a;var l=f;var m=!!c;l=_.sf(k)?k.de(l,m):k?(k=_.Ff(k))?k.de(l,m):[]:[];for(k=0;m=l[k];k++){var r=m.listener;if(r.yb==b&&r.Lk==d){e?e.Ca(a,f,m.listener,c,d):_.Jf(a,f,m.listener,c,d);break}}}};

}catch(e){_._DumpException(e)}
try{
var th;th=function(a,b,c){if(a.o)return null;if(c instanceof Array){var d=null;c=_.la(c);for(var e=c.next();!e.done;e=c.next())(e=th(a,b,e.value))&&(d=e);return d}d=null;a.j&&a.j.type==c&&a.A==b&&(d=a.j,a.j=null);if(e=b.getAttribute("data-eqid"))b.removeAttribute("data-eqid"),(e=a.B[e])?b.removeEventListener?b.removeEventListener(c,e,!1):b.detachEvent&&b.detachEvent("on"+c,e):a.C.log(Error("o`"+b));return d};_.uh=function(a,b,c){return function(){try{return b.apply(c,arguments)}catch(d){a.log(d)}}};
_.wh=function(a,b,c,d,e,f){d=_.uh(a,d,f);a=_.N(b,c,d,e,f);_.vh(b,c);return a};_.vh=function(a,b){if(a instanceof Element&&(b=th(_.Ic("eq"),a,b||[])))if(_.x&&b instanceof MouseEvent&&a.dispatchEvent){var c=document.createEvent("MouseEvent");c.initMouseEvent(b.type,!0,!0,b.view,b.detail,b.screenX,b.screenY,b.clientX,b.clientY,b.ctrlKey,b.altKey,b.shiftKey,b.metaKey,b.button,b.relatedTarget);a.dispatchEvent(c)}else a.dispatchEvent&&a.dispatchEvent(b)};

}catch(e){_._DumpException(e)}
try{
_.xh=function(a,b){_.jg.call(this,b);this.C=a;this.Qb=b||this};_.n(_.xh,_.jg);_.xh.prototype.L=function(a,b,c,d){if(c){if("function"!=typeof c)throw new TypeError("D");c=_.uh(this.C,c,this.Qb);c=_.jg.prototype.L.call(this,a,b,c,d);_.vh(a,yh(b));return c}return _.jg.prototype.L.call(this,a,b,c,d)};
_.xh.prototype.A=function(a,b,c,d,e){if(c){if("function"!=typeof c)throw new TypeError("D");c=_.uh(this.C,c,e||this.Qb);c=_.jg.prototype.A.call(this,a,b,c,d,e);_.vh(a,yh(b));return c}return _.jg.prototype.A.call(this,a,b,c,d,e)};_.xh.prototype.wb=function(a,b,c,d){if(c){if("function"!=typeof c)throw new TypeError("D");c=_.uh(this.C,c,this.Qb);c=_.jg.prototype.wb.call(this,a,b,c,d);_.vh(a,yh(b));return c}return _.jg.prototype.wb.call(this,a,b,c,d)};
var yh=function(a){return Array.isArray(a)?_.Ja(a,yh):"string"===typeof a?a:a?a.toString():a};
_.zh=function(a,b){_.xh.call(this,b);this.o=a};_.n(_.zh,_.xh);_.zh.prototype.G=function(){return this.o};_.zh.prototype.S=function(){this.o=null;_.xh.prototype.S.call(this)};

}catch(e){_._DumpException(e)}
try{
_.Ah=function(a,b,c){_.zh.call(this,a,b);this.B=c;(a=_.M("gb_tc",this.o))&&_.mh(this,a,this.j)};_.n(_.Ah,_.zh);_.Ah.prototype.j=function(a){var b;(a=a.currentTarget)&&(a=a.getAttributeNode("data-ved"))&&a.value&&(b={ved:a.value});this.B.log(39,b)};

}catch(e){_._DumpException(e)}
try{
var Ch,Dh,Eh,Hh;_.U=function(a,b,c){c?_.R(a,b):_.S(a,b)};_.Bh=function(a,b,c,d){if(null!=a)for(a=a.firstChild;a;){if(b(a)&&(c.push(a),d)||_.Bh(a,b,c,d))return!0;a=a.nextSibling}return!1};Ch=function(a,b){var c=[];_.Bh(a,b,c,!1);return c};Dh=function(a){return _.x&&!_.bc("9")?(a=a.getAttributeNode("tabindex"),null!=a&&a.specified):a.hasAttribute("tabindex")};Eh=function(a){a=a.tabIndex;return"number"===typeof a&&0<=a&&32768>a};
_.Fh=function(a){var b;if((b="A"==a.tagName&&a.hasAttribute("href")||"INPUT"==a.tagName||"TEXTAREA"==a.tagName||"SELECT"==a.tagName||"BUTTON"==a.tagName?!a.disabled&&(!Dh(a)||Eh(a)):Dh(a)&&Eh(a))&&_.x){var c;"function"!==typeof a.getBoundingClientRect||_.x&&null==a.parentElement?c={height:a.offsetHeight,width:a.offsetWidth}:c=a.getBoundingClientRect();a=null!=c&&0<c.height&&0<c.width}else a=b;return a};_.Gh=function(a,b){a=a.getAttribute("aria-"+b);return null==a||void 0==a?"":String(a)};
Hh=function(a){return null!=_.Be(a,function(b){return 1==b.nodeType&&"true"==_.Gh(b,"hidden")})};_.Ih=function(a){return a?Ch(a,function(b){return 1==b.nodeType&&_.Fh(b)&&!Hh(b)}):[]};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.Jh=function(a){return null==a?"":String(a)};

}catch(e){_._DumpException(e)}
try{
var Kh=function(a){_.I.call(this);this.C=a;this.A=null;this.o={};this.D={};this.j={};this.B=null};_.n(Kh,_.I);_.Lh=function(a){if(a.A)return a.A;for(var b in a.j)if(a.j[b].df()&&a.j[b].Vb())return a.j[b];return null};_.h=Kh.prototype;_.h.Bf=function(a){a&&_.Lh(this)&&a!=_.Lh(this)&&_.Lh(this).ze(!1);this.A=a};_.h.Bg=function(a){a=this.j[a]||a;return _.Lh(this)==a};_.h.Le=function(a,b){b=b.qd();if(this.o[a]&&this.o[a][b])for(var c=0;c<this.o[a][b].length;c++)try{this.o[a][b][c]()}catch(d){this.C.log(d)}};
_.h.wh=function(a){return!this.D[a.qd()]};_.h.$g=function(a){this.j[a]&&(_.Lh(this)&&_.Lh(this).qd()==a||this.j[a].ze(!0))};_.h.ab=function(a){this.B=a;for(var b in this.j)this.j[b].df()&&this.j[b].ab(a)};_.h.vf=function(a){this.j[a.qd()]=a};var Mh=new Kh(_.L);_.Kc("dd",Mh);

}catch(e){_._DumpException(e)}
try{
var Oh,Ph,Rh,Sh,Uh,Wh,Xh,ai,bi,fi,ki,li,mi;_.Nh=function(a,b){b&&_.nh(a,a.href.replace(/([?&](continue|followup)=)[^&]*/g,"$1"+encodeURIComponent(b)))};Oh=function(a,b){if(void 0!==a.j||void 0!==a.o)throw Error("p");a.o=b;_.pd(a)};Ph=function(a){_.z(this,a,0,-1,null,null)};_.v(Ph,_.y);_.Qh=function(a,b){b.parentNode&&b.parentNode.insertBefore(a,b)};Rh=function(a){a=a.getAttribute("src");return null!=a&&""!=a};
Sh=function(a,b,c){a=_.M("gb_ua",a.G());if(""!=b||""!=c)if(_.P(a,"gb_ra"))""!=_.Lg(a,"background-image")&&(b=""!=c?c:b,_.Jg(a,"background-image","url('"+b+"')"),a=_.M("gb_wc",a),null!=a&&Rh(a)&&a.setAttribute("src",b));else if("IMG"==a.tagName){var d=""!=b?b:c;null!=a&&Rh(a)&&a.setAttribute("src",d);b!=c&&(c=""!=c?c+" 2x ":"",""!=b&&(c=c+(""==c?"":",")+(b+" 1x")),a.setAttribute("srcset",c))}};_.Th=function(a,b,c){_.I.call(this);this.yb=a;this.o=b||0;this.j=c;this.Ra=(0,_.q)(this.vi,this)};
_.v(_.Th,_.I);_.h=_.Th.prototype;_.h.Zc=0;_.h.S=function(){_.Th.U.S.call(this);this.stop();delete this.yb;delete this.j};_.h.start=function(a){this.stop();this.Zc=_.eg(this.Ra,void 0!==a?a:this.o)};_.h.stop=function(){0!=this.Zc&&_.fg(this.Zc);this.Zc=0};_.h.vi=function(){this.Zc=0;this.yb&&this.yb.call(this.j)};Uh=function(a){return String(a).replace(/([A-Z])/g,"-$1").toLowerCase()};_.Vh=function(a,b){return _.M(a,b)};Wh=function(a,b){var c=b.parentNode;c&&c.replaceChild(a,b)};
Xh=function(a,b){var c=[];return _.Bh(a,b,c,!0)?c[0]:void 0};_.Yh=function(a,b){b?a.tabIndex=0:(a.tabIndex=-1,a.removeAttribute("tabIndex"))};_.Zh=function(a){if(_.me&&null!==a&&"innerText"in a)a=a.innerText.replace(/(\r\n|\r|\n)/g,"\n");else{var b=[];_.Hg(a,b,!0);a=b.join("")}a=a.replace(/ \xAD /g," ").replace(/\xAD/g,"");a=a.replace(/\u200B/g,"");_.me||(a=a.replace(/ +/g," "));" "!=a&&(a=a.replace(/^\s*/,""));return a};
_.$h=function(a,b,c){if(_.kh&&a.dataset)a.dataset[b]=c;else{if(/-[a-z]/.test(b))throw Error("l");a.setAttribute("data-"+Uh(b),c)}};ai=function(a){if(/-[a-z]/.test("item"))return null;if(_.kh&&a.dataset){if(_.vb()&&!("item"in a.dataset))return null;a=a.dataset.item;return void 0===a?null:a}return a.getAttribute("data-"+Uh("item"))};bi=function(a,b){return/-[a-z]/.test(b)?!1:_.kh&&a.dataset?b in a.dataset:a.hasAttribute?a.hasAttribute("data-"+Uh(b)):!!a.getAttribute("data-"+Uh(b))};
_.ci=function(a){this.o=a;this.j=null};_.di=function(a){a.j||(a.j=_.N(a.o,"keydown",a.A,!1,a))};_.gi=function(a){fi(a);_.U(a.o,"gb_u",!1)};_.ci.prototype.A=function(a){9!=a.keyCode||_.P(this.o,"gb_u")||(_.U(this.o,"gb_u",!0),fi(this))};fi=function(a){a.j&&(_.Kf(a.j),a.j=null)};_.hi=function(a,b){_.O.call(this);this.D=a;b&&(this.D.id=b)};_.n(_.hi,_.O);_.h=_.hi.prototype;_.h.G=function(){return this.D};_.h.hk=function(){return this.D.id};
_.h.li=function(){var a=this.D.id;a||(a="gb$"+_.Zg(_.Yg.va()),this.D.id=a);return a};_.h.S=function(){_.ye(this.D);_.O.prototype.S.call(this)};_.h.rd=function(){return this.G()};_.ii=function(a){return Xh(a,function(b){return _.ze(b)&&_.Fh(b)})};_.ji=function(a){(a=_.ii(a))&&a.focus()};ki={Ml:"gb_ta",am:"gb_3d",ul:"gb_Lc"};li=function(){var a=_.we("LI");_.R(a,"gb_Sc");_.jh(a,"menuitem");return a};
mi=function(a,b){b||(b=li(),a.rd().appendChild(b));_.hi.call(this,b);this.C=new _.jg(this);_.mh(this.C,this.G(),this.Fi)};_.n(mi,_.hi);_.h=mi.prototype;_.h.Zj=function(a){a?_.$h(this.G(),"item",a):(a=this.G(),!/-[a-z]/.test("item")&&(_.kh&&a.dataset?bi(a,"item")&&delete a.dataset.item:a.removeAttribute("data-"+Uh("item"))));return this};_.h.Ld=function(){return ai(this.G())};_.h.vd=function(a){_.U(this.G(),"gb_Ca",a);return this};_.h.focus=function(){_.ji(this.G())};_.h.Fi=function(){this.dispatchEvent("click")};
var ni=function(a,b){if(!b){b=li();_.R(b,"gb_Xc");var c=_.Dg("A","gb_Uc");_.Yh(c,!0);b.appendChild(c);var d=_.Dg("SPAN","gb_Vc");c.appendChild(d);a.rd().appendChild(b)}mi.call(this,a,b);this.A=_.Vh("gb_Uc",this.G());this.B=_.M("gb_Wc",this.A);this.j=null;this.o=_.M("gb_Vc",this.A)};_.n(ni,mi);_.h=ni.prototype;_.h.Ld=function(){return mi.prototype.Ld.call(this)||this.Kg()};_.h.Kg=function(){return _.Zh(this.o)};_.h.ak=function(a){_.Eg(this.o,a);return this};
_.h.$j=function(a){this.B||(this.B=_.Dg("IMG","gb_Wc"),this.B.setAttribute("alt",""),this.j?(Wh(this.B,this.j),this.j=null):_.Qh(this.B,this.o));this.B.setAttribute("src",a);return this};_.h.Qk=function(a){if(!(a instanceof Element&&"svg"==a.tagName.toLowerCase()))return this;this.B?(Wh(a,this.B),this.B=null):this.j?Wh(a,this.j):_.Qh(a,this.o);var b=a.getAttribute("class");b?a.setAttribute("class",b+" gb_Wc"):a.setAttribute("class","gb_Wc");this.j=a;return this};_.h.focus=function(){this.A.focus()};
_.oi=function(a){_.hi.call(this,a);this.o=[];this.J={}};_.n(_.oi,_.hi);_.oi.prototype.sa=function(a){var b=this.J[a];if(b)return b;var c=document.getElementById(a);if(c)for(var d=0,e=this.o.length;d<e;++d)if(b=this.o[d],b.G()==c)return this.J[a]=b;return null};_.oi.prototype.Ib=function(a){a.Mc(this);this.o.push(a);var b=a.D.id;b&&(this.J[b]=a)};_.oi.prototype.Y=function(){for(var a=0,b=this.o.length;a<b;a++)this.o[a].ta();this.J={};this.o=[]};
var pi=function(a,b){if(!b){b=_.we("UL");_.R(b,"gb_Pc");var c=_.Dg("SPAN","gb_Tc");b.appendChild(c)}_.oi.call(this,b);this.A=a;a=this.G().getElementsByClassName("gb_Sc");for(b=0;b<a.length;b++)c=a[b],_.P(c,"gb_Xc")?this.Ib(new ni(this,c)):this.Ib(new mi(this,c));this.j=_.M("gb_Tc",this.G())};_.n(pi,_.oi);_.h=pi.prototype;_.h.Ib=function(a){_.oi.prototype.Ib.call(this,a);var b=this.A,c=a.G();c=c.id||(c.id="gbm"+_.Zg(_.Yg.va()));b.P[c]=a};_.h.Xj=function(){return null!=this.j?_.Zh(this.j):null};
_.h.Yj=function(a){return null!=this.j?(_.Eg(this.j,a),this):null};_.h.Ah=function(){var a=new mi(this);this.Ib(a);return a};_.h.Bh=function(){var a=new ni(this);this.Ib(a);return a};
var qi=function(a){return a instanceof HTMLElement&&bi(a,"ogobm")},ri="click mousedown scroll touchstart wheel keydown".split(" "),si=function(a,b){this.Ra=a;this.j=b},V=function(a,b,c,d,e,f,g){_.oi.call(this,a);this.j=b;this.F=a;this.C=c;this.M=d;this.N=e;this.B=_.M("gb_Mc",this.j);this.O=new _.ci(this.B);this.H=_.M("gb_Nc",this.B);this.K=_.M("gb_Oc",this.B);this.P={};this.R=[];this.W=f||!1;this.T=g||!1;this.A=new _.jg(this);ti(this);a=this.B.getElementsByClassName("gb_Pc");for(b=0;b<a.length;b++)this.Ib(new pi(this,
a[b]))};_.n(V,_.oi);_.h=V.prototype;_.h.S=function(){_.oi.prototype.S.call(this);ui(this)};_.h.rd=function(){return this.B};_.h.bk=function(){return _.M("gb_we",this.j)};_.h.zh=function(){vi(this);return wi(this,this.H)};_.h.yh=function(){vi(this);return wi(this,this.K)};var wi=function(a,b){var c=new pi(a),d=c.G();b.appendChild(d);a.Ib(c);return c},vi=function(a){a.H||(a.H=_.we("DIV"),_.R(a.H,"gb_Nc"),a.B.appendChild(a.H),a.K=_.we("DIV"),_.R(a.K,"gb_Oc"),a.B.appendChild(a.K))};
V.prototype.ha=function(a){_.U(this.j,"gb_Kc",1==a);this.dispatchEvent("msc")};V.prototype.X=function(){return xi(this)?0:1};var yi=function(a,b){switch(b){case "menu":_.S(a.G(),"gb_Ea");break;case "back":_.S(a.C,"gb_Ea");break;case "close":_.S(a.M,"gb_Ea")}},zi=function(a){_.R(a.G(),"gb_Ea");_.R(a.C,"gb_Ea");_.R(a.M,"gb_Ea")},Ai=function(a){return!_.P(a,"gb_Ea")};_.h=V.prototype;_.h.isVisible=function(a){switch(a){case "menu":return Ai(this.G());case "back":return Ai(this.C);case "close":return Ai(this.M)}return!1};
_.h.open=function(a){this.N||(a&&_.Jg(this.j,"transition","none"),this.dispatchEvent("beforeshow"),_.R(this.j,"gb_oa"),_.T(this.G(),"expanded",!0),_.ji(this.B),_.di(this.O),this.dispatchEvent("open"),this.A.A(document.body,ri,this.vg,!0,this),this.A.L(document.body,"focusin",this.Lg),a&&_.eg(function(){_.Jg(this.j,"transition","")},0,this))};_.h.Nk=function(a){this.N&&_.T(this.G(),"expanded",a)};
_.h.close=function(a){this.N||(a&&_.Jg(this.j,"transition","none"),_.S(this.j,"gb_oa"),_.T(this.G(),"expanded",!1),document.activeElement==this.G()&&this.G().blur(),_.gi(this.O),this.dispatchEvent("close"),ui(this),a&&_.eg(function(){_.Jg(this.j,"transition","")},0,this))};_.h.Xk=function(a){Ai(this.F)&&_.R(this.F,"gb_Cc");_.S(this.C,"gb_Ea");a&&_.Cf(this.C,"click",a)};_.h.vj=function(){_.R(this.C,"gb_Ea");_.P(this.F,"gb_Cc")&&_.S(this.F,"gb_Cc")};_.h.Wb=function(){return _.P(this.j,"gb_oa")};
var ti=function(a){_.mh(a.A,a.G(),a.Z);a.G().addEventListener("keydown",function(b){32==b.keyCode&&b.preventDefault()});_.mh(a.A,a.B,a.aj);a.A.L(a.j,"keydown",a.dk);a.A.L(a.j,"keyup",a.Wi);_.mh(a.A,a.C,function(){this.dispatchEvent("bbc")});_.mh(a.A,a.M,function(){this.dispatchEvent("cbc")});if(_.P(a.j,"gb_ta")||_.P(a.j,"gb_3d"))a.A.L(window,"resize",a.V),a.V();_.P(a.j,"gb_Fc")||a.A.wb(window,"touchstart",function(){_.Jg(a.j,"overflow-y","auto")})};
V.prototype.V=function(){var a=window.visualViewport?window.visualViewport.height:window.innerHeight;a&&_.Jg(this.j,"height","calc("+a+"px - 100%)")};V.prototype.Z=function(){this.dispatchEvent("mbc");if(!this.N){if(this.Wb()){this.close();var a=!0}else this.open(),a=!1;a&&this.G().focus()}};var xi=function(a){return!_.P(a.j,"gb_Kc")||_.P(a.j,"gb_ta")||_.P(a.j,"gb_3d")};_.h=V.prototype;_.h.Wi=function(a){9===a.keyCode&&this.Wb()&&(a=this.O,_.U(a.o,"gb_u",!0),fi(a))};
_.h.dk=function(a){a:{if(36==a.keyCode||35==a.keyCode){var b=_.Ih(this.j);if(0<b.length){var c=b[b.length-1];36==a.keyCode&&(c=!xi(this)&&1<b.length?b[1]:b[0]);c.focus();a.preventDefault();break a}}27!=a.keyCode||this.W&&!xi(this)||(this.close(),null!=this.F&&this.F.focus())}9===a.keyCode&&this.Wb()&&xi(this)&&(b=a.target,c=_.Ih(this.j),0<c.length&&(b==c[0]&&a.shiftKey?(c[c.length-1].focus(),a.preventDefault()):b!=c[c.length-1]||a.shiftKey||(c[0].focus(),a.preventDefault())))};
_.h.aj=function(a){if(a.target instanceof Node){a:{a=a.target;for(var b=this.B;a&&a!==b;){var c=a.id;if(c in this.P){a=this.P[c];break a}a=a.parentNode}a=null}if(a){a=a.Ld();b=0;for(c=this.R.length;b<c;++b){var d=this.R[b];d.Ra.call(d.j,a)}this.W&&!xi(this)||this.close()}}};
_.h.vg=function(a){this.Wb()&&a.target instanceof Node&&!(!xi(this)||this.T&&_.Be(a.target,qi))&&("keydown"==a.type?27==a.keyCode&&(a.preventDefault(),a.stopPropagation(),this.close(),this.G().focus()):_.qh(a.target,"gb_F")||_.qh(a.target,"gb_xc")||_.Zf(this.j,a.target)||("touchstart"==a.type&&(a.preventDefault(),a.stopPropagation()),this.close()))};
_.h.Lg=function(){this.Wb()&&(!xi(this)||"IFRAME"!=document.activeElement.tagName&&(this.T&&_.Be(document.activeElement,qi)||_.qh(document.activeElement,"gb_Ec")||_.qh(document.activeElement,"gb_F")||_.ji(this.B)))};var ui=function(a){a.A.Ca(document.body,ri,a.vg,!1,a);a.A.Ca(document.body,"focusin",a.Lg)};V.prototype.$=function(a,b){this.R.push(new si(a,b))};_.Bi=function(a){_.hi.call(this,a);_.lh.L(a,this.j,!1,this)};_.n(_.Bi,_.hi);_.Bi.prototype.j=function(a){this.dispatchEvent("click")||a.preventDefault()};
var Ci=function(){this.j=null};Ci.prototype.Yc=function(){return this.j};
var Di=function(a,b,c){this.o=a;this.A=b;this.j=c||_.p};
var Ei=function(a){this.j=[];this.B=a||this};Ei.prototype.o=function(a,b,c){this.C(a,b,c);this.j.push(new Di(a,b,c))};Ei.prototype.C=function(a,b,c){c=c||_.p;for(var d=0,e=this.j.length;d<e;d++){var f=this.j[d];if(f.o==a&&f.A==b&&f.j==c){this.j.splice(d,1);break}}};Ei.prototype.A=function(a){a.j=this.B;for(var b=0,c=this.j.length;b<c;b++){var d=this.j[b];"catc"==d.o&&d.A.call(d.j,a)}};
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.Gi=function(a,b){_.O.call(this);this.j=a;this.A=Fi(this.j);this.F=b||100;this.B=_.N(a,"resize",this.C,!1,this)};_.v(_.Gi,_.O);_.Gi.prototype.S=function(){_.Kf(this.B);_.Gi.U.S.call(this)};_.Gi.prototype.C=function(){this.o||(this.o=new _.Th(this.D,this.F,this),_.Pf(this,this.o));this.o.start()};
_.Gi.prototype.D=function(){if(!this.j.Pa){var a=this.A,b=Fi(this.j);this.A=b;if(a){var c=!1;a.width!=b.width&&(this.dispatchEvent("b"),c=!0);a.height!=b.height&&(this.dispatchEvent("a"),c=!0);c&&this.dispatchEvent("resize")}else this.dispatchEvent("a"),this.dispatchEvent("b"),this.dispatchEvent("resize")}};
var Hi=function(a){_.O.call(this);this.o=a||window;this.A=_.N(this.o,"resize",this.B,!1,this);this.j=_.Wf(this.o)},Ii,Fi;_.v(Hi,_.O);_.Ji=function(){var a=window,b=_.zg(a);return Ii[b]=Ii[b]||new Hi(a)};Ii={};Fi=function(a){return a.j?_.xg(a.j):null};Hi.prototype.S=function(){Hi.U.S.call(this);this.A&&(_.Kf(this.A),this.A=null);this.j=this.o=null};Hi.prototype.B=function(){var a=_.Wf(this.o);_.Cg(a,this.j)||(this.j=a,this.dispatchEvent("resize"))};
var Li=function(a,b){this.B=new Ei(this);this.H=a;this.D=b;this.j=Ki(a.offsetWidth,this.D);this.K=new _.Gi(_.Ji(),10);_.N(this.K,"b",function(){window.requestAnimationFrame?window.requestAnimationFrame((0,_.q)(this.F,this)):this.F()},!1,this)},Ki=function(a,b){for(var c=0,d=b.length-1,e=b[0];c<d;){if(a<=e.max)return e.id;e=b[++c]}return b[d].id};Li.prototype.F=function(){var a=Ki(this.H.offsetWidth,this.D);a!=this.j&&(this.j=a,this.A(new Ci))};Li.prototype.o=function(a,b,c){this.B.o(a,b,c)};
Li.prototype.C=function(a,b){this.B.C(a,b)};Li.prototype.A=function(a){this.B.A(a)};
var Mi={id:"unlimitedProductControl",xe:Number.MAX_SAFE_INTEGER};
_.Ni=function(a){_.hi.call(this,a);_.N(a,"click",this.j,!1,this)};_.n(_.Ni,_.hi);_.Ni.prototype.o=function(){var a=this.G().getAttribute("aria-pressed");return(null==a?a:"boolean"===typeof a?a:"true"==a)||!1};_.Ni.prototype.j=function(a){a=a.currentTarget;var b=_.Gh(a,"pressed");_.gg(_.Jh(b))||"true"==b||"false"==b?_.T(a,"pressed","true"==b?"false":"true"):a.removeAttribute("aria-pressed");this.dispatchEvent("click")};
_.Oi=function(){_.t("gbar.I",_.hi);_.hi.prototype.ia=_.hi.prototype.hk;_.hi.prototype.ib=_.hi.prototype.G;_.hi.prototype.ic=_.hi.prototype.li;_.t("gbar.J",_.oi);_.oi.prototype.ja=_.oi.prototype.sa;_.oi.prototype.jb=_.oi.prototype.Y;_.t("gbar.K",_.Bi);_.t("gbar.L",_.Ni);_.Ni.prototype.la=_.Ni.prototype.o};
var W=function(a,b,c,d){_.O.call(this);this.A=a;_.S(this.A,"gb_Td");this.o=b;this.M=c;this.Oa="";this.hb=d;this.H=this.j=null;this.Fa=this.P=this.X=!1;this.ua=_.J(_.B(this.o,16),!1);this.$=new _.jg(this);this.wa=_.M("gb_Zc",this.A);this.V=_.J(_.B(b,6),!1);this.Pc=_.M("gb_3c",this.wa);this.C=_.M("gb_Vd",this.A);this.O=_.M("gb_6d",this.A);(this.ma=_.J(_.B(this.o,21),!1))&&this.C&&(this.Aa=_.M("gb_Le",this.A),this.Md=_.M("gb_Pe",this.A),this.R=_.M("gb_Me",this.A));this.J=_.M("gb_9d",this.A);this.T=_.M("gb_Rc",
this.A);this.zd=_.M("gb_5e",this.A);this.F=_.M("gb_1c",this.A);this.D=_.M("gb_8d",this.A);this.Z=Array.prototype.slice.call(_.oh("gb_fe",this.A));this.W=!1;this.vc=_.J(_.B(this.o,19),!1);this.tc=_.J(_.B(this.o,20),!1);a=Pi(this,!0);b=Pi(this,!1);this.Nc=Math.max(a,b);this.Y=_.B(this.o,15);c=_.Qc(_.A(this.o,30),0);0!=c&&Qi(this,c);a=Ri(this,a,b);this.K=new Li(this.A,Si);this.Zb=_.K(_.A(this.o,37));this.Yb=_.K(_.A(this.o,38));this.uc=_.P(this.A,"gb_be");this.Sc=_.J(_.B(this.o,39));this.ma&&this.C&&
(this.Ma=new Li(this.A,Ti),this.Ma.o("catc",this.ka,this),this.ka(),_.mh(this.$,this.Aa,function(){var e=this.Md,f=!_.P(e,"gb_Ea");_.U(e,"gb_Ea",f)}));this.xc=_.J(_.B(this.o,1),!1);this.wc=_.J(_.B(this.o,40),!1);Ui(this);Vi(this,this.K.j);this.K.o("catc",this.mc,this);_.B(this.o,8)&&document.addEventListener("scroll",(0,_.q)(function(){_.U(this.A,"gb_Xd",0<window.scrollY)},this));null!=this.D&&_.B(this.o,7)&&(this.ha=new Li(this.D,a),this.ha.o("catc",this.Ye,this),this.Ye())};_.n(W,_.O);_.h=W.prototype;
_.h.G=function(){return this.A};_.h.Rk=function(a){this.H=a;Wi(this,this.X);a=Xi(this);0!=a&&Yi(this,a)};_.h.Sk=function(a,b){this.H&&Sh(this.H,a,b)};_.h.ab=function(a){this.Db(a||this.Sc?1:0);this.Qb(a?this.Zb:this.Yb);var b=_.M("gb_4");null!=b&&_.U(b,"gb_ka",a);this.j&&this.wc&&_.U(this.j.j,"gb_Jc",a);_.rd.va().j.then(function(c){c.ab(a)},void 0,this);(b=_.M("gb_ja",this.A))&&_.U(b,"gb_ka",a);_.Ic("dd").ab(a)};
_.h.Tk=function(a){this.wa&&(_.Eg(this.Pc,a||""),_.U(this.wa,"gb_Ea",!a),this.V=!!a,Vi(this,this.K.j))};_.h.ek=function(){return _.M("gb_we",this.C)};_.h.Ye=function(){if(null!=this.ha){var a=this.ha.j;3==a?Zi(this,!1):1==a?Zi(this,!0):Zi(this,"gb_Lc"==this.K.j)}};
var Zi=function(a,b){if(_.B(a.o,7)&&(!a.W||b)){if(a.Y){var c=_.M("gb_Ce",a.A);if(c){var d=_.M("gb_De",a.A),e="gb_Lc"!=a.K.j||b?"":a.Nc+"px";_.Jg(c,"min-width",e);_.Jg(d,"min-width",e)}}_.P(a.D,"gb_Re")!=b&&(_.U(a.D,"gb_Re",b),b?a.dispatchEvent("sfi"):a.dispatchEvent("sfu"),_.U(_.M("gb_6e",a.D),"gb_Re",b),b&&a.ka())}},Ui=function(a){var b=_.rd.va();a.C||Oh(b.o,Error("I"));_.J(_.B(a.o,11))||Oh(b.H,Error("J"));_.J(_.B(a.o,7))||Oh(b.F,Error("K"));_.J(_.B(a.o,12))||Oh(b.C,Error("L"));_.J(_.B(a.o,13))||
Oh(b.D,Error("M"));_.J(_.B(a.o,41))||Oh(b.A,Error("N"))},Vi=function(a,b){if(!a.j&&a.C){var c=_.M("gb_xc",a.A);if(c){var d=_.M("gb_Ec");if(d){var e=_.M("gb_Ac");if(e){var f=_.M("gb_Bc");if(f){a.j=new V(c,d,e,f,_.J(_.B(a.o,16),!1),_.J(_.B(a.o,9),!1),_.J(_.B(a.o,33),!1));a.j.L("open",a.qc,!1,a);a.j.L("close",a.nc,!1,a);a.j.L("msc",a.sc,!1,a);switch(_.A(a.o,32)){case 1:a.N("back");break;case 2:a.N("close");break;case 3:a.N("none");break;default:a.N("default")}_.Oi();_.t("gbar.C",V);V.prototype.ca=V.prototype.rd;
V.prototype.cb=V.prototype.zh;V.prototype.cc=V.prototype.$;V.prototype.cd=V.prototype.ha;V.prototype.ce=V.prototype.yh;V.prototype.cf=V.prototype.open;V.prototype.cg=V.prototype.close;V.prototype.ch=V.prototype.X;V.prototype.ci=V.prototype.Xk;V.prototype.cj=V.prototype.vj;V.prototype.ck=V.prototype.Wb;V.prototype.cl=V.prototype.Nk;V.prototype.cm=V.prototype.bk;_.t("gbar.D",pi);pi.prototype.da=pi.prototype.Ah;pi.prototype.db=pi.prototype.Bh;pi.prototype.dc=pi.prototype.Xj;pi.prototype.dd=pi.prototype.Yj;
_.t("gbar.E",mi);mi.prototype.ea=mi.prototype.G;mi.prototype.eb=mi.prototype.vd;mi.prototype.ec=mi.prototype.Zj;mi.prototype.ed=mi.prototype.Ld;_.t("gbar.F",ni);ni.prototype.fa=ni.prototype.ak;ni.prototype.fb=ni.prototype.$j;ni.prototype.fc=ni.prototype.Qk;ni.prototype.fd=ni.prototype.Kg;ni.prototype.ed=ni.prototype.Ld;_.qd(_.rd.va().o,a.j)}else a.M.log(Error("E"))}else a.M.log(Error("F"))}else a.M.log(Error("G"))}else a.M.log(Error("H"))}a.j&&!a.P&&a.N("default");a.j&&a.tc&&a.N("none");$i(a);a.vc||
a.ua?a.X=!0:(c="gb_ta"==b,d=_.J(_.B(a.o,5),!1),e=_.J(_.B(a.o,7),!1),a.X=!(a.V||c&&(d||e)));c=aj(a,b);a.j&&c?_.bj(a)||null==a.T||(c=_.M("gb_Qc"),a.T.parentNode!=c&&c.insertBefore(a.T,c.childNodes[0]||null),_.R(a.J,"gb_ae"),a.sa(),a.dispatchEvent("upi")):_.bj(a)&&a.C&&null!=a.T&&(c=a.zd,c.insertBefore(a.T,c.childNodes[0]||null),_.S(a.J,"gb_ae"),a.sa(),a.dispatchEvent("upo"));c="gb_ta"==b;a.H&&!a.ua&&(d=a.H.G(),e=!a.V,_.U(d,"gb_Ea",!e),e&&Wi(a,a.X));a.j&&(a.j.isVisible("menu")||a.j.isVisible("back"))&&
!xi(a.j)&&(a.Fa=a.j.Wb());d=_.Qf(ki);_.ug(a.A,d);_.R(a.A,b);_.B(a.o,7);a.Y&&null!=a.F&&("gb_Lc"!=b?(_.Jg(a.F,"min-width",""),_.Jg(a.J,"min-width","")):(e=_.Rg(a.F).width,f=_.Rg(a.J).width,e=Math.max(e,f),_.Jg(a.F,"min-width",e+"px"),_.Jg(a.J,"min-width",e+"px")));c?a.W||(a.W=!0,Zi(a,a.W)):(a.W=!1,a.Ye());null!=a.D&&(e="gb_3d"==b,_.U(a.D,"gb_Xe",!c&&!e),_.U(a.D,"gb_We",c||e));a.j&&(c=a.j.j,_.ug(c,d),_.R(c,b),xi(a.j)?_.M("gb_je",void 0).appendChild(c):a.A.appendChild(c),a.j.isVisible("menu")||a.j.isVisible("back"))&&
(b=!xi(a.j),c=a.j.Wb(),b&&!c&&a.Fa?a.j.open():!b&&c&&a.j.close());_.cj(a)},Wi=function(a,b){var c=_.M("gb_ua",a.H.G());_.U(c,"gb_Ea",!b);a=_.M("gb_he",a.H.G());null!=a&&_.U(a,"gb_ve",!b)},Ri=function(a,b,c){var d=320,e=_.Qc(_.A(a.o,29),0);0<e&&(d=e);e=d+2*Math.max(b,c);b=d+b+c;return e!=b&&a.Y?[{id:1,max:b},{id:2,max:e},{id:3}]:[{id:1,max:b},{id:3}]},Pi=function(a,b){if(a=_.M(b?"gb_Ce":"gb_De",a.A)){var c=a.offsetWidth;_.Ha(a.children,function(d){_.P(d,"gb_Ea")&&(c-=d.offsetWidth)});return c}return 0},
dj=function(a){return function(){a.click()}},ej=function(a){var b=_.M("gb_Ce",a.A),c=_.M("gb_De",a.A),d=[];b&&_.Ha(b.children,function(e){d.push(e)});_.J(_.B(a.o,7),!1)&&(a=_.M("gb_Re",a.D))&&(a=_.M("gb_zf",a),a.j=!0,d.push(a));c&&_.Ha(c.children,function(e){d.push(e)});return d};
W.prototype.ka=function(){if(this.ma&&this.C){var a=ej(this),b=!1;a=_.Ia(a,function(f){b=b||_.P(f,"gb_Fe");return _.P(f,"gb_7c")||_.P(f,"gb_Sf")||_.P(f,"gb_zf")});var c=this.Ma.j.xe,d=!1;if(a.length>c||b)d=!0,c--;var e=a.length-c;if(d!=!_.P(this.Aa,"gb_Ea")||e!=this.R.children){_.U(this.Aa,"gb_Ea",!d);if(d)for(;this.R.firstChild;)this.R.removeChild(this.R.firstChild);fj(this,a,c);d?this.$.A(document.body,gj,this.Ia,!0,this):this.$.Ca(document.body,gj,this.Ia,!1,this)}}};
var fj=function(a,b,c){b=_.Ia(b,function(f){return _.P(f,"gb_Fe")?(hj(this,f),!1):!0},a);for(var d=0;d<b.length;d++){var e=b[d];d>=c?hj(a,e):_.S(e,"gb_Ea")}},hj=function(a,b){_.R(b,"gb_Ea");var c=_.we("LI");_.sg(c,["gb_Ne","gb_Sc","gb_Xc"]);_.Yh(c,!0);_.mh(a.$,c,dj(b));var d=_.Dg("A","gb_Uc");c.appendChild(d);var e=_.Dg("SPAN","gb_Vc");d.appendChild(e);d=b.j?b.getAttribute("aria-label"):b.title;_.Eg(e,d);d=!1;_.P(b,"gb_Sf")&&(d=!0);var f,g=b.children[0];d?f=g.children[0].children[0].src:b.j?f="https://www.gstatic.com/images/icons/material/system/1x/search_black_24dp.png":
f=g.src;a.B=_.Dg("IMG");_.sg(a.B,["gb_Wc","gb_Oe"]);a.B.setAttribute("src",f);_.Qh(a.B,e);a.R.appendChild(c)};W.prototype.Ia=function(a){!_.P(this.Md,"gb_Ea")&&a.target instanceof Node&&("keydown"==a.type?27==a.keyCode&&(a.preventDefault(),a.stopPropagation(),_.R(this.Md,"gb_Ea"),this.G().focus()):_.Zf(this.Md,a.target)||("touchstart"==a.type&&(a.preventDefault(),a.stopPropagation()),_.R(this.Md,"gb_Ea")))};W.prototype.mc=function(){Vi(this,this.K.j);this.j&&_.ij(this,this.j.Wb(),!1);this.dispatchEvent("ffc")};
_.ij=function(a,b,c){a.j&&(xi(a.j)&&(c=b=!1),a=document.body,_.U(a,"gb_Ae",b),_.U(a,"gb_ze",c))};W.prototype.qc=function(){_.ij(this,!0,!0)};W.prototype.nc=function(){_.ij(this,!1,!0)};W.prototype.sc=function(){var a=xi(this.j),b=this.j.j;a?_.M("gb_je",void 0).appendChild(b):this.A.appendChild(b)};_.bj=function(a){return!!a.j&&_.P(a.J,"gb_ae")};
W.prototype.N=function(a){var b=!1;switch(a){case "back":this.P=!0;zi(this.j);yi(this.j,"back");b=!0;break;case "close":this.P=!0;zi(this.j);yi(this.j,"close");b=!0;break;case "default":this.P=!1;aj(this,this.K.j)||this.xc?(this.j&&!this.j.isVisible("menu")&&(zi(this.j),yi(this.j,"menu")),b=!0):(this.j&&this.j.isVisible("back")&&zi(this.j),this.j&&this.j.isVisible("menu")?(a=this.j,a.close(),_.R(a.G(),"gb_Ea"),Ai(a.C)&&_.S(a.G(),"gb_Cc")):(a=_.M("gb_xc",this.A))&&_.R(a,"gb_Ea"),b=!1);break;case "none":this.P=
!0,zi(this.j),b=!1}null!=this.F&&_.U(this.F,"gb_2c",b)};var aj=function(a,b){var c="gb_ta"==b;b="gb_3d"==b;var d=_.J(_.B(a.o,5),!1),e=_.J(_.B(a.o,2),!1);return!(_.J(_.B(a.o,10),!1)||a.ua)&&e&&(c||b&&(d||a.V))};W.prototype.getHeight=function(){var a=this.A.offsetHeight;if(this.uc){var b=_.M("gb_Od");b&&(a+=b.offsetHeight)}return a};_.cj=function(a){var b=a.getHeight()+"px";a.Oa!=b&&(a.Oa=b,a.hb&&(a.hb.style.height=b),a.dispatchEvent("resize"))};W.prototype.Oc=function(){this.O&&_.cj(this)};
W.prototype.Ba=function(){if(!this.O){var a=_.we("DIV");_.sg(a,["gb_6d","gb_fe"]);jj(a,Xi(this));a.style.backgroundColor=this.A.style.backgroundColor;this.Z.push(a);_.ph(a,this.C);this.O=a}return this.O};W.prototype.Qc=function(){_.ye(this.O);this.O=null;_.cj(this)};_.kj=function(a,b){a.C?a.C.appendChild(b):a.J?a.J.appendChild(b):a.M.log(Error("O"))};W.prototype.Db=function(a){2==a&&(a=0);for(var b=0;b<this.Z.length;b++)jj(this.Z[b],a);Yi(this,a)};
var Yi=function(a,b){if(a.H){if(2==b){b=_.K(_.A(a.o,24),"");var c=_.K(_.A(a.o,27),"")}else 1==b?(b=_.K(_.A(a.o,23),""),c=_.K(_.A(a.o,26),"")):(b=_.K(_.A(a.o,22),""),c=_.K(_.A(a.o,25),""));""==b&&""==c||Sh(a.H,b,c)}},Xi=function(a){a=a.Z[0];return a.classList.contains("gb_yc")?1:a.classList.contains("gb_ge")?2:0},jj=function(a,b){_.ug(a,["gb_ge","gb_yc"]);1==b?_.R(a,"gb_yc"):2==b&&_.R(a,"gb_ge")};W.prototype.Qb=function(a){this.A.style.backgroundColor=a};W.prototype.lc=function(){return this.A.style.backgroundColor};
W.prototype.sa=function(){var a=_.Ic("dd");_.Lh(a)&&_.Lh(a).ze(!1);a.Bf(null)};W.prototype.Tc=function(a){Qi(this,a-8-10);$i(this)};var Qi=function(a,b){null==a.D?a.M.log(Error("P")):a.Y?a.M.log(Error("Q")):a.Ya=0>b?0:b},$i=function(a){null!=a.F&&("gb_ta"==a.K.j?_.Jg(a.F,"min-width",""):null!=a.Ya&&_.Jg(a.F,"min-width",a.Ya+"px"))};W.prototype.yd=function(a){_.U(_.M("gb_rc",this.C),"gb_Ea",!a)};W.prototype.Rc=function(a){if(a){var b=_.M("gb_4");null!=b&&_.Nh(b,a);_.rd.va().j.then(function(c){c.Vg(a)})}};
var gj="click mousedown scroll touchstart wheel keydown".split(" "),Si=[{id:"gb_ta",max:599},{id:"gb_3d",max:1023},{id:"gb_Lc"}],Ti=[{id:{id:"oneProductControl",xe:1},max:320},{id:{id:"twoProductControl",xe:2},max:360},{id:{id:"threeProductControl",xe:3},max:410},{id:Mi}];
var lj=function(a,b){b.xa=b.type;b.xb=b.target;return a.call(this,b)};
var mj;_.O.prototype.za=_.Rd(function(a,b,c,d,e){return a.call(this,b,_.Rd(lj,c),d,e)},_.O.prototype.L);_.O.prototype.zb=_.O.prototype.mi;var nj=_.M("gb_sa");
if(null==nj)mj=null;else{var oj=_.F(_.td,Ph,6)||new Ph,pj=new W(nj,oj,_.L,_.M("gb_Zd"));_.t("gbar.P",W);W.prototype.pa=W.prototype.getHeight;W.prototype.pb=W.prototype.Tk;W.prototype.pc=W.prototype.Db;W.prototype.pd=W.prototype.Qb;W.prototype.pe=W.prototype.Ba;W.prototype.pf=W.prototype.Oc;W.prototype.pg=W.prototype.Qc;W.prototype.ph=W.prototype.ek;W.prototype.pi=W.prototype.sa;W.prototype.pj=W.prototype.Tc;W.prototype.pk=W.prototype.yd;W.prototype.pl=W.prototype.Rc;W.prototype.pm=W.prototype.N;W.prototype.pn=
W.prototype.lc;W.prototype.po=W.prototype.Sk;W.prototype.pp=W.prototype.ab;_.qd(_.rd.va().B,pj);mj=pj}_.qj=mj;

}catch(e){_._DumpException(e)}
try{
var rj=document.querySelector(".gb_Ra .gb_D"),sj=document.querySelector("#gb.gb_Ic");rj&&!sj&&_.Nd(_.yd,rj,"click");

}catch(e){_._DumpException(e)}
try{
(function(){for(var a=document.querySelectorAll(".gb_tc"),b=0;b<a.length;b++)_.Nd(_.yd,a[b],"click");_.rd.va().B.then(function(c){if(c){var d=_.M("gb_rc",c.C);d&&(d=new _.Ah(d,_.L,_.xd),c.Rk(d))}})})();

}catch(e){_._DumpException(e)}
})(this.gbar_);
// Google Inc.
</script>

  <div id="ntp-contents">
    <div id="logo">
      <!-- The logo that is displayed in the absence of a doodle. -->
      <div id="logo-default" title="Google" class="show-logo"></div>
      <!-- Logo displayed when theme prevents doodles. Doesn't fade. -->
      <div id="logo-non-white" title="Google"></div>
      <!-- A doodle, if any: its link and image. -->
      <div id="logo-doodle">
        <div id="logo-doodle-container">
          <div id="logo-doodle-wrapper">
            <button id="logo-doodle-button">
              <img id="logo-doodle-image" tabindex="-1">
            </button>
          </div>
        </div>
        <iframe id="logo-doodle-iframe" scrolling="no"></iframe>
      </div>
    </div>

    <div id="fakebox-container" hidden="">
      <div id="fakebox">
        <div class="search-icon"></div>
        <div id="fakebox-text"></div>
        <input id="fakebox-input" autocomplete="off" tabindex="-1" type="url" aria-hidden="true">
        <div id="fakebox-cursor"></div>
        <button id="fakebox-microphone" class="microphone-icon" hidden=""></button>
      </div>
    </div>

    <div id="realbox-container">
      <div id="realbox-input-wrapper">
        <div id="realbox-icon" data-default-icon="search.svg" data-icon="search.svg" style="-webkit-mask-image: url(&quot;search.svg&quot;);">
        </div>
        <input id="realbox" type="search" autocomplete="off" spellcheck="false" aria-live="polite" autofocus="" placeholder="Search Google or type a URL">
        <button id="realbox-microphone" class="microphone-icon" title="Search by voice"></button>
        <div id="realbox-matches"></div>
      </div>
    </div>

    <div id="user-content">
      <!-- Search suggestions will be inserted here. -->
      <div id="most-visited">
        <!-- The container for the tiles. The MV iframe goes in here. -->
        <div id="mv-tiles"><iframe id="mv-single" name="mv-single" title="Most visited" src="chrome-search://most-visited/single.html?title=Most%20visited&amp;removeTooltip=Don't%20show%20on%20this%20page&amp;enableCustomLinks=1&amp;addLink=Add%20shortcut&amp;addLinkTooltip=Add%20shortcut&amp;editLinkTooltip=Edit%20shortcut"></iframe></div>
      </div>
    </div>

    <!-- Notification shown when the tiles are modified. -->
    <div id="mv-notice-container">
      <div id="mv-notice" class="notice-hide" role="alert">
        <span id="mv-msg">Shortcut removed</span>
        <!-- Links in the notification. -->
        <span id="mv-notice-links">
          <span id="mv-undo" class="ripple" tabindex="0" role="button">Undo</span>
          <span id="mv-restore" class="ripple" tabindex="0" role="button"></span>
        </span>
      </div>
    </div>

    <div id="attribution" style="display: none;"><div id="attribution-text">Theme created by</div></div>

    <div id="error-notice-container">
      <div id="error-notice" class="notice-hide" role="alert">
        <span id="error-notice-icon"></span>
        <span id="error-notice-msg"></span>
        <span id="error-notice-link" class="ripple" tabindex="0" role="button"></span>
      </div>
    </div>

    <div id="edit-bg" tabindex="0" role="button" class="ep-enhanced" aria-label="Customize this page" title="Customize this page">
      <div id="edit-bg-icon"></div>
      <span id="edit-bg-text">Customize</span>
    </div>

    <div id="custom-bg-attr"></div>
  </div>

  <dialog div="" id="edit-bg-dialog">
    <div id="edit-bg-menu">
      <div id="edit-bg-title">Customize this page</div>
      <div id="edit-bg-default-wallpapers" class="bg-option" tabindex="0">
        <div class="bg-option-img"></div>
        <div id="edit-bg-default-wallpapers-text" class="bg-option-text">Chrome backgrounds</div>
      </div>
      <div id="edit-bg-upload-image" class="bg-option" tabindex="0">
        <div class="bg-option-img"></div>
        <div id="edit-bg-upload-image-text" class="bg-option-text">Upload an image</div>
      </div>
      <div id="edit-bg-divider"></div>
      <div id="custom-links-restore-default" class="bg-option" tabindex="0">
        <div class="bg-option-img"></div>
        <div id="custom-links-restore-default-text" class="bg-option-text">Restore default shortcuts</div>
      </div>
      <div id="edit-bg-restore-default" class="bg-option bg-option-disabled" tabindex="-1">
        <div class="bg-option-img"></div>
        <div id="edit-bg-restore-default-text" class="bg-option-text">Restore default background</div>
      </div>
    </div>
  </dialog>

  <dialog id="ddlsd">
    <div id="ddlsd-title"></div>
    <button id="ddlsd-close"></button>
    <div id="ddlsd-content">
      <button id="ddlsd-fbb" class="ddlsd-sbtn"></button>
      <button id="ddlsd-twb" class="ddlsd-sbtn"></button>
      <button id="ddlsd-emb" class="ddlsd-sbtn"></button>
      <hr id="ddlsd-hr">
      <div id="ddlsd-link">
        <span id="ddlsd-text-ctr">
          <input type="text" id="ddlsd-text" dir="ltr">
        </span>
        <button id="ddlsd-copy"></button>
      </div>
    </div>
  </dialog>

  <dialog id="bg-sel-menu" class="customize-dialog">
    <div id="bg-sel-title-bar">
    <div id="bg-sel-back-circle" tabindex="0" role="button" aria-label="Back">
      <div id="bg-sel-back"></div>
    </div>
    <div id="bg-sel-title"></div>
    </div>
    <div id="bg-sel-tiles" tabindex="0"></div>
    <div id="bg-sel-footer">
      <button id="bg-sel-footer-cancel" class="bg-sel-footer-button paper secondary ripple" tabindex="0" aria-label="Cancel">Cancel</button>
      <button id="bg-sel-footer-done" class="bg-sel-footer-button paper primary ripple" tabindex="-1" aria-label="Done" disabled="">Done</button>
    </div>
  </dialog>

  <dialog id="customization-menu" class="customize-dialog">
    <div id="menu-nav-panel" role="tablist" aria-label="Customize this page">
      <button id="backgrounds-button" class="menu-option" tabindex="0" role="tab" aria-controls="backgrounds-menu backgrounds-image-menu" aria-selected="true" aria-labelledby="backgrounds-menu-option" title="Background">
        <div class="menu-option-icon-wrapper">
          <div id="backgrounds-icon" class="menu-option-icon"></div>
        </div>
        <div id="backgrounds-menu-option" class="menu-option-label">
          Background
        </div>
      </button>
      <button id="shortcuts-button" class="menu-option" tabindex="0" role="tab" aria-controls="shortcuts-menu" aria-selected="false" aria-labelledby="shortcuts-menu-option" title="Shortcuts">
        <div class="menu-option-icon-wrapper">
          <div id="shortcuts-icon" class="menu-option-icon"></div>
        </div>
        <div id="shortcuts-menu-option" class="menu-option-label">
          Shortcuts
        </div>
      </button>
      <button id="colors-button" class="menu-option" tabindex="0" role="tab" aria-controls="colors-menu" aria-selected="false" aria-labelledby="colors-menu-option" title="Color and theme">
        <div class="menu-option-icon-wrapper">
          <div id="colors-icon" class="menu-option-icon"></div>
        </div>
        <div id="colors-menu-option" class="menu-option-label">
          Color and theme
        </div>
      </button>
    </div>
    <div id="menu-contents">
      <div id="menu-header">
        <div id="menu-back-circle" tabindex="0" role="button" aria-label="Back" title="Back">
          <div id="menu-back"></div>
        </div>
        <div id="menu-title">Customize this page</div>
        <div id="refresh-daily-wrapper">
          <div id="refresh-toggle-wrapper" title="Refresh daily">
            <label class="switch">
              <input id="refresh-daily-toggle" type="checkbox" aria-labelledby="refresh-text">
              <span class="toggle">
                <div class="knob"></div>
                <div class="highlight"></div>
              </span>
            </label>
          </div>
          <div id="refresh-text">Refresh daily</div>
        </div>
      </div>
      <div id="backgrounds-menu" class="menu-panel" tabindex="0" role="tabpanel" aria-label="Background">
        <div id="backgrounds-upload" class="bg-sel-tile-bg">
          <div id="backgrounds-upload-icon" class="bg-sel-tile" tabindex="-1" role="button" aria-label="Upload from device" aria-pressed="false" title="Upload from device">
            <div id="backgrounds-upload-arrow"></div>
            <div id="backgrounds-upload-text">Upload from device</div>
          </div>
        </div>
        <div id="backgrounds-default" class="bg-sel-tile-bg">
          <div id="backgrounds-default-icon" class="bg-sel-tile" tabindex="-1" role="button" aria-label="No background" title="No background" aria-pressed="false">
            <div class="mini-page">
              <div class="mini-header-colorful"></div>
              <div class="mini-shortcuts"></div>
            </div>
          </div>
          <div class="bg-sel-tile-title">No background</div>
        </div>
      </div>
      <div id="backgrounds-image-menu" class="menu-panel" tabindex="0" role="tabpanel" aria-label="Background"></div>
      <div id="backgrounds-disabled-menu" class="menu-panel" tabindex="0" role="tabpanel" aria-label="Background">
        <div id="backgrounds-disabled-wrapper">
          <div id="backgrounds-disabled-icon"></div>
          <div id="backgrounds-disabled-title">
            Custom backgrounds have been turned off by your administrator
          </div>
        </div>
      </div>
      <div id="shortcuts-menu" class="menu-panel" tabindex="0" role="tabpanel" aria-label="Shortcuts">
        <div id="sh-options">
          <div class="sh-option">
            <div id="sh-option-cl" class="sh-option-image" tabindex="-1" role="button" aria-pressed="false" aria-labelledby="sh-option-cl-title" title="My shortcuts">
              <div class="sh-option-icon"></div>
              <div class="sh-option-mini">
                <div class="mini-page">
                  <div class="mini-header"></div>
                  <div class="mini-shortcuts"></div>
                </div>
              </div>
            </div>
            <div id="sh-option-cl-title" class="sh-option-title">
              My shortcuts
            </div>
            Shortcuts are curated by you
          </div>
          <div class="sh-option">
            <div id="sh-option-mv" class="sh-option-image" tabindex="-1" role="button" aria-pressed="false" aria-labelledby="sh-option-mv-title" title="Most visited sites">
              <div class="sh-option-icon"></div>
              <div class="sh-option-mini">
                <div class="mini-page">
                  <div class="mini-header"></div>
                  <div class="mini-shortcuts"></div>
                </div>
              </div>
            </div>
            <div id="sh-option-mv-title" class="sh-option-title">
              Most visited sites
            </div>
            Shortcuts are suggested based on websites you visit often
          </div>
        </div>
        <div id="sh-hide">
          <div id="sh-hide-icon"></div>
          <div>
            <div id="sh-hide-title">Hide shortcuts</div>
            Don't show shortcuts on this page
          </div>
          <div id="sh-hide-toggle-wrapper" title="Hide shortcuts">
            <label class="switch">
              <input id="sh-hide-toggle" type="checkbox" tabindex="-1" aria-labelledby="sh-hide-title">
              <span class="toggle">
                <div class="knob"></div>
                <div class="highlight"></div>
              </span>
            </label>
          </div>
        </div>
      </div>
      <div id="colors-menu" class="menu-panel" tabindex="0" role="tabpanel" aria-label="Color and theme">
        <div id="colors-theme" tabindex="0">
            <div id="colors-theme-icon"></div>
            <div id="colors-theme-info">
              <div id="colors-theme-name"></div>
              Current theme you have installed
            </div>
            <a id="colors-theme-link" target="_blank">
              <div id="colors-theme-link-icon"> </div>
            </a>
            <button id="colors-theme-uninstall" class="paper secondary">
              Uninstall
            </button>
        </div>
        <div id="color-picker-container" class="bg-sel-tile-bg">
          <div id="color-picker-tile" class="bg-sel-tile" tabindex="-1" aria-label="Select color" title="Select color" role="button" aria-pressed="false">
            <div id="left-semicircle"></div>
            <div id="color-picker-icon"></div>
            <input id="color-picker" type="color" style="display:none">
            
          </div>
        </div>
        <div id="colors-default" class="bg-sel-tile-bg">
          <div id="colors-default-icon" class="bg-sel-tile" tabindex="-1" aria-label="Default" title="Default" role="button" aria-pressed="false">
          </div>
        </div>
      </div>
    </div>
    <div id="menu-footer">
      <button id="menu-cancel" class="bg-sel-footer-button paper secondary ripple" title="Cancel">Cancel</button>
      <button id="menu-done" class="bg-sel-footer-button paper primary ripple" title="Done">Done</button>
    </div>
  </dialog>

  <dialog id="voice-overlay-dialog" class="overlay-dialog">
    <div id="voice-overlay" class="overlay-hidden">
      <button id="voice-close-button" class="close-button" title="Close" aria-label="Close">×</button>
      <div id="voice-outer" class="outer">
        <div class="inner-container">
          <div id="voice-button-container" class="button-container">
            <!-- The audio level animation. -->
            <span id="voice-level" class="level"></span>
            <!-- The microphone button. -->
            <span id="voice-button" class="button">
              <!-- The microphone icon (in CSS). -->
              <div class="microphone">
                <span class="receiver"></span>
                <div class="wrapper">
                  <span class="stem"></span>
                  <span class="shell"></span>
                </div>
              </div>
            </span>
          </div>
          <div id="text-container" aria-live="polite">
            <!-- Low confidence text underneath high confidence text. -->
            <span id="voice-text-i" class="voice-text"></span>
            <!-- High confidence text on top of low confidence text. -->
            <span id="voice-text-f" class="voice-text"></span>
          </div>
        </div>
      </div>
    </div>
  </dialog>
  <div id="screen-reader-announcer" role="status" aria-live="polite"></div>

  <div id="one-google-end-of-body"><div></div></div>

  <script defer="" src="chrome-search://local-ntp/voice.js" integrity="sha256-C9ctze2LhHtwL+fcPVPkmVRYjQgXTGs4xfBAzlQwGWk="></script>


<script id="search-suggestions-loader" src="chrome-search://local-ntp/search-suggestions.js"></script><script id="one-google-loader" src="chrome-search://local-ntp/one-google.js"></script><script id="promo-loader" src="chrome-search://local-ntp/promo.js"></script><script src="chrome-search://local-ntp/doodle.js"></script><dialog id="custom-links-edit-dialog" class="customize-dialog"><iframe id="custom-links-edit" name="custom-links-edit" title="Edit shortcut" src="chrome-search://most-visited/edit.html?addTitle=Add%20shortcut&amp;editTitle=Edit%20shortcut&amp;nameField=Name&amp;urlField=URL&amp;linkRemove=Remove&amp;linkCancel=Cancel&amp;linkDone=Done&amp;invalidUrl=Type%20a%20valid%20URL"></iframe></dialog><script type="text/javascript">this.gbar_=this.gbar_||{};(function(_){var window=this;
try{
if(_.qj){var tj;if(tj=_.A(_.qj.o,3))for(var uj=_.oh(tj),vj=0;vj<uj.length;vj++)_.$h(uj[vj],"ogpc","");_.ij(_.qj,!!_.qj.j&&_.qj.j.Wb(),!1)}
;
}catch(e){_._DumpException(e)}
try{
_.wj=function(a){_.z(this,a,0,-1,null,null)};_.v(_.wj,_.y);_.xj=function(a,b,c){a.rel=c;a.href=-1!=c.toLowerCase().indexOf("stylesheet")?_.Xa(b):b instanceof _.Va?_.Xa(b):b instanceof _.cb?_.db(b):_.db(_.jb(b))};
_.yj=function(a){return _.Ya(_.A(a,4)||"")};

}catch(e){_._DumpException(e)}
try{
var zj=function(a,b,c){_.xd.log(46,{att:a,max:b,url:c})},Bj=function(a,b,c){_.xd.log(47,{att:a,max:b,url:c});a<b?Aj(a+1,b):_.L.log(Error("R`"+a+"`"+b),{url:c})},Aj=function(a,b){if(Cj){var c=_.we("SCRIPT");c.async=!0;c.type="text/javascript";c.charset="UTF-8";_.ie(c,Cj);c.onload=_.Rd(zj,a,b,c.src);c.onerror=_.Rd(Bj,a,b,c.src);_.xd.log(45,{att:a,max:b,url:c.src});_.pe("HEAD")[0].appendChild(c)}},Dj=function(a){_.z(this,a,0,-1,null,null)};_.v(Dj,_.y);
var Ej=_.F(_.td,Dj,17)||new Dj,Fj,Cj=(Fj=_.F(Ej,_.wj,1))?_.yj(Fj):null,Gj,Hj=(Gj=_.F(Ej,_.wj,2))?_.yj(Gj):null,Ij=function(){Aj(1,2);if(Hj){var a=_.we("LINK");a.setAttribute("type","text/css");_.xj(a,Hj,"stylesheet");var b=_.Vd();b&&a.setAttribute("nonce",b);_.pe("HEAD")[0].appendChild(a)}};
(function(){var a=_.ud();if(_.B(a,18))Ij();else{var b=_.A(a,19)||0;window.addEventListener("load",function(){window.setTimeout(Ij,b)})}})();

}catch(e){_._DumpException(e)}
})(this.gbar_);
// Google Inc.
</script><div class="gb_oe"><div class="gb_qe"><div>Google Account</div><div class="gb_qb">srinidhithegreat01@gmail.com</div><div>srinidhithegreat01@gmail.com</div></div></div><div class="gb_zc">Main menu</div><div class="gb_Sd">Google apps</div><script src="chrome-search://local-ntp/doodle.js?v=50" gapi_processed="true"></script></body></html>

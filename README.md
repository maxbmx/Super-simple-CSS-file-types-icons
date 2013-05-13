filetype-icons
==============

Super simple CSS file types icons.

CSS:
.file-type-icon{display:block; width:30px; height:40px; background:#F9F9F9; position:relative; border:1px solid #E6E6E6; border-radius:2px; box-shadow:inset 1px 1px 0 0 #ffffff, inset -1px -1px 0 0 #ffffff, inset 0 10px 20px -10px rgba(0,0,0,.05);}
.file-type-icon .corner{display:block; position:absolute; top:-1px; right:-1px; width: 0; height: 0; border-left: 12px solid #eeeeee; border-top: 12px solid #ffffff; /*change this color if you want to use it on custom background*/ box-shadow:-1px 1px 0px 0 #E6E6E6;}
.file-type-icon .type{background:#777; text-align:center; display:block; position:absolute; bottom:6px; left:-2px; height:15px; line-height:15px; font-size:10px; color:#fff; border-radius:1px; width:25px;}
.file-type-icon .type.txt{background:#F9B142;}
.file-type-icon .type.doc{background:#0088CC;}
.file-type-icon .type.xls{background:#85A91A;}
.file-type-icon .type.pdf{background:#C80000;}

HTML:
<div class="file-type-icon">
  <span class="corner"></span>
  <span class="type">html</span>
</div>

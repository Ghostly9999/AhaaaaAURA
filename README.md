--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v80=v2(v0(v30,16));if v19 then local v89=v5(v80,v19);v19=nil;return v89;else return v80;end end end);local function v20(v31,v32,v33) if v33 then local v81=0 -0 ;local v82;while true do if (v81==(0 -(0 -0))) then v82=(v31/(((1640 -(1523 + 114)) -1)^(v32-(2 -1))))%(2^(((v33-(620 -(555 + 64))) -(v32-(932 -(857 + 74)))) + (569 -(367 + 181 + 20)))) ;return v82-(v82%1) ;end end else local v83=(929 -(214 + 713))^(v32-(1 + 0)) ;return (((v31%(v83 + v83))>=v83) and (1 + (1270 -(226 + 1044)))) or (877 -(282 + 595)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + 2 );v18=v18 + (8 -6) ;return (v36 * (373 -(32 + 85))) + v35 ;end local function v23() local v37=(0 -0) -0 ;local v38;local v39;local v40;local v41;while true do if (v37==(1 + (952 -(802 + 150)))) then return (v41 * (16777396 -(67 + 113))) + (v40 * (14533 + 51003)) + (v39 * ((2200 -987) -(892 + 65))) + v38 ;end if (v37==(0 -0)) then v38,v39,v40,v41=v1(v16,v18,v18 + 3 );v18=v18 + (9 -(4 + 1)) ;v37=(998 -(915 + 82)) -0 ;end end end local function v24() local v42=v23();local v43=v23();local v44=2 -1 ;local v45=(v20(v43,1,12 + 8 ) * ((2 -0)^(1219 -(1069 + 97 + 21)))) + v42 ;local v46=v20(v43,47 -26 ,67 -36 );local v47=((v20(v43,(778 -(201 + 571)) + 26 )==(1 -(1138 -(116 + 1022)))) and  -(1 + 0)) or ((3297 -2505) -(368 + 423)) ;if (v46==(0 -0)) then if (v45==(18 -(10 + 8))) then return v47 * ((0 + 0) -0) ;else v46=443 -((1518 -1102) + 26) ;v44=0 -(0 -0) ;end elseif (v46==((1738 -(814 + 45)) + 1168)) then return ((v45==(0 -0)) and (v47 * ((439 -(145 + (721 -428)))/(430 -(44 + 386))))) or (v47 * NaN) ;end return v8(v47,v46-1023 ) * (v44 + (v45/((1488 -(998 + 488))^(17 + 35)))) ;end local function v25(v48) local v49;if  not v48 then v48=v23();if (v48==0) then return "";end end v49=v3(v16,v18,(v18 + v48) -(1 + 0) );v18=v18 + v48 ;local v50={};for v64=1 + 0 , #v49 do v50[v64]=v2(v1(v3(v49,v64,v64)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return 0;end)();local v52=(function() return;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();while true do if (v51~= #"}") then else local v86=(function() return 0 + 0 ;end)();while true do if ((1 + 1)==v86) then v51=(function() return 1 + 1 ;end)();break;end if ((202 -(14 + 188))==v86) then v56=(function() return v23();end)();v57=(function() return {};end)();v86=(function() return 1;end)();end if (v86==(676 -(534 + 141))) then for v102= #"~",v56 do local v103=(function() return 0 + 0 ;end)();local v104=(function() return;end)();local v105=(function() return;end)();local v106=(function() return;end)();while true do if (v103~=(1 + 0)) then else v106=(function() return nil;end)();while true do if (v104== #".") then if (v105== #"~") then v106=(function() return v21()~=(0 + 0) ;end)();elseif (v105==2) then v106=(function() return v24();end)();elseif (v105== #"asd") then v106=(function() return v25();end)();end v57[v102]=(function() return v106;end)();break;end if (v104==0) then local v115=(function() return 0;end)();while true do if (v115~=0) then else v105=(function() return v21();end)();v106=(function() return nil;end)();v115=(function() return 1 -0 ;end)();end if (v115==(1 -0)) then v104=(function() return  #">";end)();break;end end end end break;end if (v103==(0 -0)) then v104=(function() return 0;end)();v105=(function() return nil;end)();v103=(function() return 1 + 0 ;end)();end end end v55[ #"-19"]=(function() return v21();end)();v86=(function() return 2;end)();end end end if (2~=v51) then else for v90= #"~",v23() do local v91=(function() return 0 + 0 ;end)();local v92=(function() return;end)();while true do if (v91~=(396 -(115 + 281))) then else v92=(function() return v21();end)();if (v20(v92, #"[", #",")==0) then local v107=(function() return 0 -0 ;end)();local v108=(function() return;end)();local v109=(function() return;end)();local v110=(function() return;end)();while true do if (v107==(1 + 0)) then local v111=(function() return 0;end)();while true do if (v111==1) then v107=(function() return 2;end)();break;end if (v111==0) then v110=(function() return {v22(),v22(),nil,nil};end)();if (v108==(0 -0)) then local v197=(function() return 0;end)();local v198=(function() return;end)();while true do if (v197==0) then v198=(function() return 0 -0 ;end)();while true do if (v198==(867 -(550 + 317))) then v110[ #"19("]=(function() return v22();end)();v110[ #"0836"]=(function() return v22();end)();break;end end break;end end elseif (v108== #"}") then v110[ #"xxx"]=(function() return v23();end)();elseif (v108==(2 -0)) then v110[ #"xnx"]=(function() return v23() -(2^(22 -6)) ;end)();elseif (v108== #"19(") then local v345=(function() return 0 -0 ;end)();local v346=(function() return;end)();while true do if (v345==(285 -(134 + 151))) then v346=(function() return 1665 -(970 + 695) ;end)();while true do if (v346==(0 -0)) then v110[ #"19("]=(function() return v23() -(2^(2006 -(582 + 1408))) ;end)();v110[ #"?id="]=(function() return v22();end)();break;end end break;end end end v111=(function() return 3 -2 ;end)();end end end if (2~=v107) then else if (v20(v109, #">", #"/")~= #"}") then else v110[2]=(function() return v57[v110[2 -0 ]];end)();end if (v20(v109,7 -5 ,1826 -(1195 + 629) )== #",") then v110[ #"gha"]=(function() return v57[v110[ #"-19"]];end)();end v107=(function() return 3;end)();end if (3==v107) then if (v20(v109, #"-19", #"gha")== #" ") then v110[ #"0313"]=(function() return v57[v110[ #"?id="]];end)();end v52[v90]=(function() return v110;end)();break;end if (v107==0) then local v113=(function() return 0;end)();while true do if (v113~=(0 -0)) then else v108=(function() return v20(v92,2, #"91(");end)();v109=(function() return v20(v92, #"0836",6);end)();v113=(function() return 242 -(187 + 54) ;end)();end if (v113~=(781 -(162 + 618))) then else v107=(function() return 1 + 0 ;end)();break;end end end end end break;end end end for v93= #"\\",v23() do v53[v93-#"|" ]=(function() return v28();end)();end return v55;end if (v51~=(0 + 0)) then else local v87=(function() return 0 -0 ;end)();local v88=(function() return;end)();while true do if (0==v87) then v88=(function() return 0 -0 ;end)();while true do if (v88==2) then v51=(function() return  #"]";end)();break;end if (v88~=1) then else v54=(function() return {};end)();v55=(function() return {v52,v53,nil,v54};end)();v88=(function() return 2;end)();end if (v88==(1636 -(1373 + 263))) then v52=(function() return {};end)();v53=(function() return {};end)();v88=(function() return 1;end)();end end break;end end end end end local function v29(v58,v59,v60) local v61=v58[1001 -(451 + 549) ];local v62=v58[1 + 1 ];local v63=v58[4 -1 ];return function(...) local v66=v61;local v67=v62;local v68=v63;local v69=v27;local v70=1 -0 ;local v71= -1;local v72={};local v73={...};local v74=v12("#",...) -(1 + 0) ;local v75={};local v76={};for v84=0,v74 do if (v84>=v68) then v72[v84-v68 ]=v73[v84 + (1 -0) ];else v76[v84]=v73[v84 + (342 -(79 + 139 + 123)) ];end end local v77=(v74-v68) + 1 ;local v78;local v79;while true do local v85=1581 -(1535 + 46) ;while true do if ((0 + 0)==v85) then v78=v66[v70];v79=v78[(338 -(10 + 327)) + 0 ];v85=(391 + 170) -((644 -(118 + 220)) + 254) ;end if ((2173>379) and (v85==1)) then if (v79<=(1 + 1 + 18)) then if (v79<=(17 -(457 -(108 + 341)))) then if (v79<=4) then if (v79<=(1468 -(899 + 256 + 312))) then if (v79==(0 + 0)) then v76[v78[2]]={};else local v120=v78[2];local v121={};for v193=1, #v75 do local v194=v75[v193];for v199=0 -(0 -0) , #v194 do local v200=v194[v199];local v201=v200[1];local v202=v200[2];if (((v201==v76) and (v202>=v120)) or (2591==3409)) then v121[v202]=v201[v202];v200[1]=v121;end end end end elseif (v79<=(605 -(268 + (1828 -(711 + 782))))) then local v122=290 -((115 -55) + (699 -(270 + 199))) ;local v123;while true do if ((4514>3324) and ((572 -(426 + 146))==v122)) then v123=nil;v76[v78[1 + 1 ]]=v76[v78[3]];v70=v70 + (1457 -(282 + 1174)) ;v122=812 -(569 + 242) ;end if (v122==(5 -3)) then v70=v70 + 1 + 0 ;v78=v66[v70];v76[v78[1026 -(706 + 318) ]]=v76[v78[1254 -(234 + 487 + 530) ]];v122=1274 -(945 + 326) ;end if (v122==9) then v70=v78[7 -4 ];break;end if ((v122==(3 + 0)) or (208>=4828)) then v70=v70 + (701 -(271 + 429)) ;v78=v66[v70];v76[v78[2]]=v59[v78[3]];v122=4 + 0 ;end if (v122==1) then v78=v66[v70];v123=v78[1502 -(1408 + 92) ];v76[v123]=v76[v123](v76[v123 + 1 ]);v122=1088 -(461 + (2444 -(580 + 1239))) ;end if (6==v122) then v76[v123]=v76[v123](v76[v123 + (1289 -(993 + 295)) ]);v70=v70 + 1 + 0 ;v78=v66[v70];v122=7;end if (v122==(1178 -(418 + 753))) then v76[v78[1 + (2 -1) ]]=v76[v78[1 + 2 ]];v70=v70 + 1 + 0 ;v78=v66[v70];v122=8;end if ((v122==(2 + 3)) or (1583>3567)) then v70=v70 + 1 + 0 ;v78=v66[v70];v123=v78[(20 + 511) -(406 + 123) ];v122=6;end if (v122==8) then v76[v78[1771 -(1749 + 9 + 11) ]]=v78[3];v70=v70 + 1 ;v78=v66[v70];v122=9;end if (v122==(1 + 3)) then v70=v70 + (1323 -(1249 + 73)) ;v78=v66[v70];v76[v78[2]]=v76[v78[(4 -2) + 1 + 0 ]];v122=5;end end elseif (v79==3) then local v203=v78[1147 -(466 + 679) ];local v204=v78[4];local v205=v203 + 2 ;local v206={v76[v203](v76[v203 + (2 -1) ],v76[v205])};for v281=1,v204 do v76[v205 + v281 ]=v206[v281];end local v207=v206[1901 -(106 + 1794) ];if (v207 or (1313==794)) then local v301=0 + 0 ;while true do if ((3174>2902) and (v301==(0 + 0))) then v76[v205]=v207;v70=v78[8 -5 ];break;end end else v70=v70 + (2 -1) ;end else local v208;local v209;local v208,v210;local v211;local v212;v76[v78[116 -(4 + 110) ]]=v76[v78[587 -(57 + 527) ]];v70=v70 + (1168 -(645 + 522)) ;v78=v66[v70];v76[v78[1429 -((1831 -(1010 + 780)) + 1386) ]]=v60[v78[106 -(17 + 86 + 0) ]];v70=v70 + 1 + 0 ;v78=v66[v70];v76[v78[3 -1 ]]=v59[v78[8 -(23 -18) ]];v70=v70 + (167 -((357 -235) + 44)) ;v78=v66[v70];v212=v78[2 -0 ];v211=v76[v78[9 -(1842 -(1045 + 791)) ]];v76[v212 + 1 + (0 -0) ]=v211;v76[v212]=v211[v78[(1 -0) + 3 ]];v70=v70 + (1 -0) ;v78=v66[v70];v212=v78[67 -(30 + 35) ];v208,v210=v69(v76[v212](v76[v212 + 1 + 0 ]));v71=(v210 + v212) -(1258 -(1043 + (719 -(351 + 154)))) ;v209=0;for v284=v212,v71 do v209=v209 + (3 -2) ;v76[v284]=v208[v209];end v70=v70 + (1213 -(323 + 889)) ;v78=v66[v70];v212=v78[5 -3 ];v208={v76[v212](v13(v76,v212 + (321 -(53 + 267)) ,v71))};v209=0 + 0 ;for v287=v212,v78[4] do local v288=413 -(15 + 398) ;while true do if (v288==(982 -(18 + 964))) then v209=v209 + 1 ;v76[v287]=v208[v209];break;end end end v70=v70 + 1 ;v78=v66[v70];v70=v78[3];end elseif (v79<=((1596 -(1281 + 293)) -(282 -(28 + 238)))) then if (v79==(10 -5)) then local v124=v76[v78[3 + 1 ]];if v124 then v70=v70 + (1560 -(1381 + 178)) + 0 ;else v76[v78[852 -(20 + 830) ]]=v124;v70=v78[3 + 0 ];end else v60[v78[3 + 0 ]]=v76[v78[128 -(116 + 10) ]];end elseif ((4120<=4260) and (v79<=(1 + 6))) then do return v76[v78[740 -(542 + 196) ]];end elseif (v79>(7 + 1)) then if (v76[v78[3 -1 ]]<=v76[v78[2 + 2 ]]) then v70=v70 + 1 + 0 ;else v70=v78[2 + 1 ];end else v76[v78[1 + 1 ]]=v59[v78[3]];end elseif (v79<=(36 -22)) then if (v79<=11) then if (v79>10) then local v127=0 -0 ;local v128;while true do if (v127==(1551 -(1126 + (1465 -1040)))) then v128=v78[2];v76[v128](v13(v76,v128 + (406 -(118 + 287)) ,v78[11 -8 ]));break;end end else local v129=1121 -(118 + 1003) ;local v130;local v131;local v132;while true do if ((v129==(0 -0)) or (883>4778)) then v130=v67[v78[380 -(142 + 235) ]];v131=nil;v129=4 -3 ;end if (v129==(1 + 1)) then for v303=978 -(553 + 424) ,v78[7 -3 ] do v70=v70 + 1 ;local v304=v66[v70];if ((v304[1 + 0 ]==28) or (3620>=4891)) then v132[v303-(1 + 0) ]={v76,v304[2 + 1 ]};else v132[v303-1 ]={v59,v304[6 -3 ]};end v75[ #v75 + 1 + 0 ]=v132;end v76[v78[9 -7 ]]=v29(v130,v131,v60);break;end if (v129==(754 -(239 + 514))) then v132={};v131=v10({},{__index=function(v306,v307) local v308=v132[v307];return v308[1 + 0 ][v308[1331 -(797 + 532) ]];end,__newindex=function(v309,v310,v311) local v312=v132[v310];v312[1][v312[2 + 0 ]]=v311;end});v129=1 + 1 ;end end end elseif (v79<=((24 + 3) -15)) then if  not v76[v78[1204 -(373 + 829) ]] then v70=v70 + (732 -(476 + 255)) ;else v70=v78[(767 + 366) -(369 + 761) ];end elseif (v79==(8 + 5)) then if ((4258>937) and (v78[2 -0 ]==v76[v78[7 -3 ]])) then v70=v70 + (239 -(64 + 174)) ;else v70=v78[1 + 2 ];end else local v233=v78[2 -0 ];v76[v233](v13(v76,v233 + (337 -(144 + 192)) ,v71));end elseif ((v79<=17) or (4869<906)) then if ((v79<=(231 -(42 + 174))) or (1225>4228)) then local v133=v78[(2 -0) + (1156 -(1074 + 82)) ];local v134=v76[v78[(6 -3) + (1784 -(214 + 1570)) ]];v76[v133 + (1456 -(990 + 465)) + 0 ]=v134;v76[v133]=v134[v78[1508 -(363 + 1141) ]];elseif ((3328>2238) and (v79>(1596 -(1183 + 397)))) then v76[v78[5 -3 ]]=v76[v78[3 + 0 ]][v78[3 + 1 ]];elseif (v76[v78[1977 -(1913 + 26 + 36) ]]==v78[3 + 1 ]) then v70=v70 + (2 -1) ;else v70=v78[1936 -(565 + 1368) ];end elseif (v79<=18) then local v138;local v139;v76[v78[7 -5 ]]={};v70=v70 + (1662 -(1477 + 184)) ;v78=v66[v70];v76[v78[2]][v78[3 -0 ]]=v78[4 + 0 ];v70=v70 + (857 -(246 + 318 + 292)) ;v78=v66[v70];v76[v78[2 -0 ]][v78[(8 + 0) -5 ]]=v78[308 -(244 + 60) ];v70=v70 + 1 + 0 ;v78=v66[v70];v76[v78[2]][v78[479 -(41 + 435) ]]=v78[1005 -(938 + 63) ];v70=v70 + (3 -2) + 0 ;v78=v66[v70];v76[v78[1127 -((2662 -(1668 + 58)) + (815 -(512 + 114))) ]][v78[1 + 2 ]]=v76[v78[1617 -(1565 + 48) ]];v70=v70 + 1 + 0 ;v78=v66[v70];v76[v78[1140 -((2038 -1256) + 356) ]]=v60[v78[270 -(176 + 91) ]];v70=v70 + 1 ;v78=v66[v70];v139=v78[4 -2 ];v138=v76[v78[3]];v76[v139 + ((1 -0) -0) ]=v138;v76[v139]=v138[v78[1096 -((3392 -2417) + 117) ]];v70=v70 + (1876 -(157 + 1718)) ;v78=v66[v70];v76[v78[2 + 0 ]]=v78[10 -7 ];v70=v70 + 1 ;v78=v66[v70];v139=v78[2];v76[v139]=v76[v139](v13(v76,v139 + (3 -2) ,v78[1021 -(697 + 150 + 171) ]));v70=v70 + ((1 + 1) -1) ;v78=v66[v70];v76[v78[3 -(1 + 0) ]]=v76[v78[(20 -14) -3 ]];elseif ((3839>1405) and (v79>19)) then v70=v78[2 + (1995 -(109 + 1885)) ];else v76[v78[3 -1 ]]= #v76[v78[7 -4 ]];end elseif (v79<=(1257 -(322 + 905))) then if (v79<=(636 -(602 + 9))) then if (v79<=(1211 -(449 + (2209 -(1269 + 200))))) then if ((v79==21) or (1293<=507)) then local v162=v78[874 -(826 + 46) ];v76[v162]=v76[v162]();else local v164=947 -(245 + 702) ;local v165;local v166;local v167;while true do if (v164==(3 -2)) then v167=0 + (0 -0) ;for v316=v165,v78[1902 -(260 + 1638) ] do v167=v167 + (441 -(382 + 58)) ;v76[v316]=v166[v167];end break;end if (((0 -0)==v164) or (2896<805)) then v165=v78[2 + 0 ];v166={v76[v165](v13(v76,v165 + 1 ,v71))};v164=1;end end end elseif (v79<=(67 -44)) then do return;end elseif ((2316==2316) and (v79>((2055 -(802 + 24)) -(902 + 303)))) then v76[v78[3 -1 ]][v78[3]]=v76[v78[9 -5 ]];elseif v76[v78[1 + 1 ]] then v70=v70 + (1691 -(1121 + 569)) ;else v70=v78[217 -(22 + 192) ];end elseif (v79<=(710 -(483 + 200))) then if ((v79>(1489 -(1404 + (101 -42)))) or (2570==1533)) then for v195=v78[5 -3 ],v78[3] do v76[v195]=nil;end else local v168;v76[v78[2 -0 ]]=v76[v78[3]][v78[4]];v70=v70 + 1 ;v78=v66[v70];v76[v78[767 -(468 + 297) ]]=v76[v78[565 -(334 + 228) ]];v70=v70 + (3 -2) ;v78=v66[v70];v76[v78[4 -2 ]]=v76[v78[3]];v70=v70 + 1 ;v78=v66[v70];v168=v78[2 -0 ];v76[v168](v13(v76,v168 + 1 + 0 ,v78[(301 -62) -(141 + 15 + 80) ]));v70=v70 + 1 ;v78=v66[v70];v70=v78[3 + 0 ];end elseif (v79<=(71 -(34 + 9))) then v76[v78[4 -2 ]]=v76[v78[1 + 2 ]];elseif (v79==(79 -50)) then if (v76[v78[2 + 0 ]]~=v76[v78[1 + 2 + 1 ]]) then v70=v70 + (1 -0) ;else v70=v78[2 + 1 ];end else local v240=v78[165 -(92 + 71) ];local v241,v242=v69(v76[v240](v76[v240 + 1 + 0 + 0 ]));v71=(v242 + v240) -1 ;local v243=0 -0 ;for v293=v240,v71 do local v294=0;while true do if (v294==(765 -(574 + 191))) then v243=v243 + (2 -1) ;v76[v293]=v241[v243];break;end end end end elseif ((v79<=((96 -67) + 3 + 3)) or (883==1460)) then if ((v79<=(79 -(20 + 27))) or (4619<=999)) then if (v79>(16 + 15)) then local v180=v78[(702 + 149) -(254 + 595) ];local v181=v76[v180];local v182=v76[v180 + (128 -(55 + 71)) ];if (v182>((0 + 0) -0)) then if ((v181>v76[v180 + (1791 -(573 + 1217)) ]) or (3410>4116)) then v70=v78[8 -(3 + 2) ];else v76[v180 + (1434 -(797 + 636)) + 2 ]=v181;end elseif (v181<v76[v180 + 1 ]) then v70=v78[4 -1 ];else v76[v180 + (14 -11) ]=v181;end elseif ((v78[2]<v76[v78[943 -((2333 -(1427 + 192)) + 225) ]]) or (903>=3059)) then v70=v70 + (2 -1) ;else v70=v78[3 -0 ];end elseif ((v79<=33) or (3976<2857)) then local v183=0 + 0 ;local v184;while true do if (v183==(0 -0)) then v184=v78[808 -(118 + 688) ];do return v13(v76,v184,v184 + v78[51 -(25 + 23) ] );end break;end end elseif (v79==(7 + 27)) then v76[v78[1888 -(927 + 959) ]]=v78[3];else v76[v78[6 -4 ]]=v29(v67[v78[3]],nil,v60);end elseif (v79<=(770 -(6 + 10 + 716))) then if ((4930>2307) and (v79<=(69 -33))) then local v185=97 -(11 + 86) ;local v186;local v187;local v188;while true do if (((0 -0)==v185) or (4046<1291)) then v186=v78[287 -(175 + 110) ];v187={v76[v186](v76[v186 + (4 -3) ])};v185=(4171 -2374) -(503 + 1293) ;end if ((2 -1)==v185) then v188=0 + 0 ;for v325=v186,v78[1065 -(810 + 251) ] do v188=v188 + 1 + 0 ;v76[v325]=v187[v188];end break;end end elseif (v79==(11 + 1 + 25)) then local v248=v78[2 + 0 ];v76[v248]=v76[v248](v76[v248 + 1 ]);else v76[v78[535 -(43 + 490) ]]=v60[v78[736 -(711 + 22) ]];end elseif ((v79<=(150 -111)) or (4241==3545)) then local v189=v78[2];local v190=v76[v189 + (861 -(240 + 619)) ];local v191=v76[v189] + v190 ;v76[v189]=v191;if (v190>(0 + 0 + 0)) then if ((v191<=v76[v189 + (1 -0) ]) or (4048>4232)) then local v328=0;while true do if ((0 + 0)==v328) then v70=v78[1747 -(1344 + (726 -(192 + 134))) ];v76[v189 + (408 -(255 + (1426 -(316 + 960)))) ]=v191;break;end end end elseif (v191>=v76[v189 + 1 + 0 ]) then local v329=0;while true do if ((0 + 0)==v329) then v70=v78[3];v76[v189 + 3 ]=v191;break;end end end elseif ((v79>(170 -130)) or (1750>=3473)) then v76[v78[2]][v78[9 -6 ]]=v78[1743 -(225 + 179 + 1335) ];else local v254=v78[408 -(183 + 223) ];v76[v254]=v76[v254](v13(v76,v254 + (1 -0) ,v78[2 + 1 ]));end v70=v70 + 1 ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!123Q00028Q00026Q000840026Q00F03F026Q00104003103Q00412Q7461636B412Q6C506C6179657273027Q0040030B3Q004C6F63616C506C6179657203063Q0073686172656403083Q0073652Q74696E677303083Q006B692Q6C617572612Q01030B3Q006D617864697374616E6365026Q003E4003093Q00646562752Q67696E67010003043Q0067616D65030A3Q004765745365727669636503073Q00506C617965727300513Q0012223Q00014Q001B000100063Q0026103Q0016000100020004143Q00160001001222000700013Q0026100007000C000100010004143Q000C000100060A00053Q000100022Q001C3Q00034Q001C3Q00024Q001B000600063Q001222000700033Q00261000070005000100030004143Q0005000100060A00060001000100042Q001C3Q00014Q001C3Q00024Q001C3Q00034Q001C3Q00043Q0012223Q00043Q0004143Q001600010004143Q000500010026103Q001E000100040004143Q001E000100060A00070002000100032Q001C3Q00064Q001C3Q00044Q001C3Q00053Q001206000700053Q0004143Q004F00010026103Q002D000100060004143Q002D0001001222000700013Q00261000070027000100010004143Q002700012Q001B000400043Q00060A00040003000100012Q001C3Q00033Q001222000700033Q00261000070021000100030004143Q002100012Q001B000500053Q0012223Q00023Q0004143Q002D00010004143Q002100010026103Q003B000100030004143Q003B0001001222000700013Q000E0D00010035000100070004143Q003500010020110002000100072Q001B000300033Q001222000700033Q000E0D00030030000100070004143Q00300001000223000300043Q0012223Q00063Q0004143Q003B00010004143Q003000010026103Q0002000100010004143Q00020001001226000700083Q0020110007000700090006180007004200013Q0004143Q004200012Q00173Q00013Q001226000700084Q001200083Q000300302Q0008000A000B00302Q0008000C000D00302Q0008000E000F00102Q00070009000800122Q000700103Q00202Q00070007001100122Q000900126Q0007000900024Q000100073Q0012223Q00033Q0004143Q000200012Q00018Q00173Q00013Q00053Q00073Q00028Q0003063Q00697061697273030B3Q004765744368696C6472656E2Q033Q0049734103043Q00542Q6F6C030E3Q0046696E6446697273744368696C64030C3Q0044616D61676552656D6F746500263Q0012223Q00014Q001B000100013Q0026103Q0002000100010004143Q000200012Q000800026Q0008000300014Q00250002000200022Q001C000100023Q0006180001002500013Q0004143Q00250001001226000200023Q00200F0003000100032Q001E000300044Q001600023Q00040004143Q0021000100200F000700060004001222000900054Q00280007000900020006180007002100013Q0004143Q00210001001222000700014Q001B000800083Q00261000070016000100010004143Q0016000100200F000900060006001222000B00074Q00280009000B00022Q001C000800093Q0006180008002100013Q0004143Q002100012Q0007000800023Q0004143Q002100010004143Q001600010006030002000F000100020004143Q000F00010004143Q002500010004143Q000200012Q00173Q00017Q00103Q00028Q00026Q00F03F03053Q007061697273030A3Q00476574506C617965727303063Q004865616C746803153Q0046696E6446697273744368696C644F66436C612Q73030A3Q00466F7263654669656C6403063Q0073686172656403083Q0073652Q74696E6773030B3Q006D617864697374616E636503053Q007461626C6503063Q00696E7365727403163Q0046696E6446697273744368696C64576869636849734103083Q00426173655061727403153Q0044697374616E636546726F6D43686172616374657203083Q00506F736974696F6E00663Q0012223Q00014Q001B000100013Q0026103Q0005000100020004143Q000500012Q0007000100023Q0026103Q0002000100010004143Q000200014Q00026Q0004000100023Q00122Q000200036Q00035Q00202Q0003000300044Q000300046Q00023Q000400044Q006100012Q0008000700013Q00061D00060061000100070004143Q00610001001222000700014Q001B000800093Q00261000070055000100020004143Q005500010006180008006100013Q0004143Q006100010006180009006100013Q0004143Q00610001002011000A00090005000E1F000100610001000A0004143Q0061000100200F000A00080006001222000C00074Q0028000A000C000200060C000A0061000100010004143Q00610001001222000A00014Q001B000B000D3Q002610000A0029000100010004143Q00290001001222000B00014Q001B000C000C3Q001222000A00023Q002610000A0024000100020004143Q002400012Q001B000D000D3Q002610000B003B000100020004143Q003B0001000618000D006100013Q0004143Q00610001001226000E00083Q002011000E000E0009002011000E000E000A000609000D00610001000E0004143Q00610001001226000E000B3Q00201A000E000E000C4Q000F00016Q001000066Q000E0010000100044Q00610001000E0D0001002C0001000B0004143Q002C0001001222000E00013Q002610000E004C000100010004143Q004C000100200F000F0008000D0012220011000E4Q0028000F001100022Q001C000C000F3Q000605000D004B0001000C0004143Q004B00012Q0008000F00013Q00200F000F000F000F0020110011000C00102Q0028000F001100022Q001C000D000F3Q001222000E00023Q002610000E003E000100020004143Q003E0001001222000B00023Q0004143Q002C00010004143Q003E00010004143Q002C00010004143Q006100010004143Q002400010004143Q0061000100261000070014000100010004143Q001400012Q0008000A00024Q0002000B00066Q000A000200024Q0008000A6Q000A00036Q000B00066Q000A000200024Q0009000A3Q00122Q000700023Q00044Q001400010006030002000F000100020004143Q000F00010012223Q00023Q0004143Q000200012Q00173Q00017Q00093Q00028Q00026Q00F03F027Q004003053Q007061697273026Q001440030A3Q004669726553657276657203063Q0073686172656403083Q0073652Q74696E677303083Q006B692Q6C6175726100393Q0012223Q00014Q001B000100033Q0026103Q0032000100020004143Q003200012Q001B000300033Q0026100001000E000100020004143Q000E000100060C0002000A000100010004143Q000A00012Q00173Q00014Q000800046Q00150004000100022Q001C000300043Q001222000100033Q00261000010024000100030004143Q002400012Q0013000400033Q000E1F00010038000100040004143Q00380001001226000400044Q001C000500034Q00240004000200060004143Q00210001001222000900023Q001222000A00053Q001222000B00023Q00042000090021000100200F000D000200062Q0008000F00014Q001C001000084Q001E000F00104Q000E000D3Q00010004270009001B000100060300040017000100020004143Q001700010004143Q0038000100261000010005000100010004143Q00050001001226000400073Q00201100040004000800201100040004000900060C0004002C000100010004143Q002C00012Q00173Q00014Q0008000400024Q00150004000100022Q001C000200043Q001222000100023Q0004143Q000500010004143Q00380001000E0D0001000200013Q0004143Q00020001001222000100014Q001B000200023Q0012223Q00023Q0004143Q000200012Q00173Q00017Q00033Q00028Q0003153Q0046696E6446697273744368696C644F66436C612Q7303083Q0048756D616E6F696401143Q001222000100014Q001B000200023Q00261000010002000100010004143Q00020001001222000300013Q00261000030005000100010004143Q000500012Q000800046Q001C00056Q00250004000200022Q001C000200043Q00060500040010000100020004143Q0010000100200F000400020002001222000600034Q00280004000600022Q0007000400023Q0004143Q000500010004143Q000200012Q00173Q00017Q00013Q0003093Q0043686172616374657201053Q0006050001000300013Q0004143Q0003000100201100013Q00012Q0007000100024Q00173Q00017Q00",v9(),...);

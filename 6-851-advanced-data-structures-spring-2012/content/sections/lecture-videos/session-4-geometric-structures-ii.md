---
about_this_resource_text: '<p><strong>Description:</strong> Fractional cascading in
  3D orthogonal range searching in O(log n) time.  Moving data, e.g., where 2D points
  move at known velocity and acceleration: kinetic predecessor and kinetic.</p> <p><strong>Speaker:</strong>
  Prof. Erik Demaine</p>'
course_id: 6-851-advanced-data-structures-spring-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: FzS0n_Z8lrk
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Video-YouTube-Stream
  type: Video
  uid: dcfa3265457c3f25dd0b57dc5dae2228
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/session-4-geometric-structures/id735348884?i=169609888
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Video-iTunes U-MP4
  type: Video
  uid: fccb55395e2d6abfdedc6fee106e5609
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.851S12/MIT6_851S12_lec04_300k.mp4
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Video-Internet Archive-MP4
  type: Video
  uid: f38c0d69b02cf63de4cd16853ddd2436
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/FzS0n_Z8lrk/default.jpg
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 28bcf4c60141d6b06e33a217619beec2
- id: 3Play-3PlayYouTubeid-MP4
  media_location: FzS0n_Z8lrk
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 60c6e4b6c8498501a61e15be4a49ba00
- id: FzS0n_Z8lrk.srt
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-4-geometric-structures-ii/FzS0n_Z8lrk.srt
  title: 3play caption file
  type: null
  uid: 57d68919610dadbca7e97575600b110e
- id: FzS0n_Z8lrk.pdf
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-4-geometric-structures-ii/FzS0n_Z8lrk.pdf
  title: 3play pdf file
  type: null
  uid: 476deba0346d2d69d907b45faef41578
- id: Caption-3Play YouTube id-SRT
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: aa6ba6114cbe32d7800df9edf250bf45
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 552da32ec5bd3c68ad33cdd36c4e1075
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 61b9b02dbdcf589c876f956d39bcae79
inline_embed_id: 27484179session4:geometricstructuresii4040380
layout: video
order_index: null
parent_uid: b66cbbb7b35e74ff17cdbf44e5fb6b1d
related_resources_text: ''
short_url: session-4-geometric-structures-ii
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-4-geometric-structures-ii
template_type: Tabbed
title: 'Session 4: Geometric Structures II'
transcript: <p><span m='90'>The</span> <span m='180'>following</span> <span m='630'>content</span>
  <span m='1200'>is</span> <span m='1320'>provided</span> <span m='1770'>under</span>
  <span m='2009'>a</span> <span m='2070'>Creative</span> <span m='2490'>Commons</span>
  <span m='2910'>license.</span> <span m='4030'>Your</span> <span m='4200'>support</span>
  <span m='4710'>will</span> <span m='4860'>help</span> <span m='5100'>MIT</span>
  <span m='5550'>OpenCourseWare</span> <span m='6360'>continue</span> <span m='6870'>to</span>
  <span m='6960'>offer</span> <span m='7380'>high</span> <span m='7620'>quality</span>
  <span m='8100'>educational</span> <span m='8730'>resources</span> <span m='9360'>for</span>
  <span m='9510'>free.</span> <span m='10720'>To</span> <span m='10740'>make</span>
  <span m='10920'>a</span> <span m='10980'>donation</span> <span m='11730'>or</span>
  <span m='11940'>view</span> <span m='12390'>additional</span> <span m='12810'>materials</span>
  <span m='13320'>from</span> <span m='13500'>hundreds</span> <span m='13920'>of</span>
  <span m='14040'>MIT</span> <span m='14460'>courses,</span> <span m='15550'>visit</span>
  <span m='15780'>MIT</span> <span m='16200'>OpenCourseWare</span> <span m='17280'>at</span>
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='22240'>ERIK DEMAINE:</span>
  <span m='22270'>All</span> <span m='22300'>right.</span> <span m='22530'>Time</span>
  <span m='22750'>for</span> <span m='22870'>some</span> <span m='23050'>more</span>
  <span m='23290'>geometry,</span> <span m='24580'>and,</span> <span m='24880'>in</span>
  <span m='24970'>particular,</span> <span m='25490'>some</span> <span m='25540'>more</span>
  <span m='25750'>fractional</span> <span m='26230'>cascading,</span> <span m='26560'>which</span>
  <span m='26890'>is a</span> <span m='27340'>cool</span> <span m='28270'>topic</span>
  <span m='28670'>we</span> <span m='28780'>saw</span> <span m='29510'>last</span>
  <span m='29800'>lecture.</span> <span m='31150'>And</span> <span m='31270'>then</span>
  <span m='31390'>we're</span> <span m='31480'>going</span> <span m='31600'>to</span>
  <span m='31660'>do</span> <span m='31780'>a</span> <span m='31840'>different</span>
  <span m='32110'>kind</span> <span m='32409'>of</span> <span m='33100'>data</span>
  <span m='33340'>structure</span> <span m='33670'>called</span> <span m='33850'>kinetic</span>
  <span m='34210'>data</span> <span m='34390'>structures,</span> <span m='34900'>where</span>
  <span m='35020'>you</span> <span m='35110'>have</span> <span m='35320'>moving</span>
  <span m='35710'>data.</span> <span m='37690'>And</span> <span m='38110'>that</span>
  <span m='38230'>will</span> <span m='38320'>actually</span> <span m='38560'>be</span>
  <span m='38650'>most</span> <span m='38980'>of the</span> <span m='39100'>lecture.</span>
  </p><p><span m='39880'>But</span> <span m='40060'>last</span> <span m='40330'>time,</span>
  <span m='40540'>we</span> <span m='40630'>saw</span> <span m='40900'>this</span>
  <span m='41050'>nice</span> <span m='41350'>general</span> <span m='41740'>black</span>
  <span m='42030'>box</span> <span m='42550'>transformation,</span> <span m='43360'>fractional</span>
  <span m='43750'>cascading,</span> <span m='44410'>and</span> <span m='44770'>we</span>
  <span m='44860'>didn't</span> <span m='45040'>really</span> <span m='45580'>see</span>
  <span m='46000'>a</span> <span m='46030'>lot</span> <span m='46240'>of</span> <span
  m='46330'>applications</span> <span m='46930'>of</span> <span m='47080'>it.</span>
  <span m='47230'>We</span> <span m='47590'>saw</span> <span m='47820'>a</span> <span
  m='47890'>simple</span> <span m='48310'>example</span> <span m='48760'>in</span>
  <span m='48850'>orthogonal</span> <span m='49330'>range</span> <span m='49510'>searching.</span>
  <span m='49960'>But</span> <span m='50080'>I</span> <span m='50170'>want</span>
  <span m='50290'>to</span> <span m='50380'>show</span> <span m='50500'>you</span>
  <span m='50620'>today</span> <span m='50860'>a</span> <span m='50920'>much</span>
  <span m='51130'>cooler</span> <span m='51430'>one</span> <span m='52750'>in</span>
  <span m='52960'>the</span> <span m='53050'>original</span> <span m='53440'>fractional</span>
  <span m='53860'>cascading</span> <span m='54340'>papers.</span> </p><p><span m='55210'>So</span>
  <span m='55540'>remember,</span> <span m='55900'>in</span> <span m='56020'>general,</span>
  <span m='56470'>what</span> <span m='56620'>it</span> <span m='56710'>lets</span>
  <span m='56980'>you</span> <span m='57100'>do</span> <span m='57310'>is</span> <span
  m='57400'>search</span> <span m='57730'>for</span> <span m='58000'>a</span> <span
  m='58060'>common</span> <span m='58510'>element</span> <span m='58900'>x,</span>
  <span m='59650'>find</span> <span m='60010'>its</span> <span m='60130'>predecessor</span>
  <span m='60700'>and</span> <span m='60790'>successor</span> <span m='61780'>in</span>
  <span m='62020'>k</span> <span m='62980'>sorted</span> <span m='63400'>lists,</span>
  <span m='64180'>in</span> <span m='64360'>order</span> <span m='64629'>log</span>
  <span m='65050'>n</span> <span m='65170'>plus</span> <span m='65530'>k</span> <span
  m='65830'>time,</span> <span m='66190'>instead</span> <span m='66430'>of</span>
  <span m='66520'>the</span> <span m='66670'>obvious</span> <span m='67060'>k</span>
  <span m='67360'>times</span> <span m='67810'>log</span> <span m='68050'>n,</span>
  <span m='69170'>where</span> <span m='69650'>n</span> <span m='69820'>is</span>
  <span m='69970'>the</span> <span m='70060'>length</span> <span m='70360'>of</span>
  <span m='70450'>each</span> <span m='70630'>list.</span> <span m='72310'>And</span>
  <span m='72640'>the</span> <span m='72760'>general</span> <span m='73150'>version</span>
  <span m='73720'>that</span> <span m='73870'>we</span> <span m='74380'>talked</span>
  <span m='74770'>about</span> <span m='75790'>is,</span> <span m='76210'>if</span>
  <span m='76480'>you're</span> <span m='76900'>navigating</span> <span m='77620'>a</span>
  <span m='77680'>graph,</span> <span m='78160'>and</span> <span m='78260'>at</span>
  <span m='78310'>each</span> <span m='78550'>node</span> <span m='78730'>of</span>
  <span m='78790'>the</span> <span m='78910'>graph,</span> <span m='79280'>you</span>
  <span m='79380'>have</span> <span m='79510'>one</span> <span m='79660'>of</span>
  <span m='79750'>these</span> <span m='79930'>lists,</span> <span m='80740'>then</span>
  <span m='80920'>you</span> <span m='81010'>can</span> <span m='81130'>instantly</span>
  <span m='81610'>know</span> <span m='83380'>where</span> <span m='83590'>x</span>
  <span m='83860'>fits</span> <span m='84160'>in</span> <span m='84250'>that</span>
  <span m='84430'>list</span> <span m='85300'>in</span> <span m='85480'>constant</span>
  <span m='85900'>time</span> <span m='86350'>per</span> <span m='86650'>thing,</span>
  <span m='86980'>as</span> <span m='87100'>long</span> <span m='87280'>as</span>
  <span m='87370'>you</span> <span m='87520'>spend</span> <span m='87820'>log</span>
  <span m='88060'>n</span> <span m='88150'>time</span> <span m='88360'>to</span> <span
  m='88450'>get</span> <span m='88570'>started,</span> <span m='90160'>provided</span>
  <span m='90670'>your</span> <span m='90790'>graph</span> <span m='91090'>has</span>
  <span m='91270'>bounded</span> <span m='91610'>degree.</span> <span m='92140'>That</span>
  <span m='92290'>was</span> <span m='92440'>necessary</span> <span m='92950'>to</span>
  <span m='93070'>do</span> <span m='93280'>all</span> <span m='93400'>the</span>
  <span m='93490'>fractional</span> <span m='93910'>cascading</span> <span m='94510'>stuff</span>
  <span m='94840'>of</span> <span m='94960'>copying</span> <span m='95410'>half</span>
  <span m='95730'>into</span> <span m='95920'>the</span> <span m='96040'>next</span>
  <span m='96940'>level</span> <span m='97210'>up.</span> </p><p><span m='98950'>So</span>
  <span m='99160'>we're</span> <span m='99280'>going</span> <span m='99400'>to</span>
  <span m='99490'>use</span> <span m='99790'>this</span> <span m='100960'>result</span>
  <span m='101860'>to</span> <span m='102010'>get</span> <span m='102220'>a</span>
  <span m='102280'>lag</span> <span m='102550'>factor</span> <span m='102970'>improvement</span>
  <span m='103570'>in</span> <span m='104020'>our</span> <span m='104230'>old</span>
  <span m='104440'>friend</span> <span m='104770'>orthogonal</span> <span m='105310'>range</span>
  <span m='105550'>searching.</span> <span m='106660'>So</span> <span m='106870'>let's</span>
  <span m='107170'>do</span> <span m='109910'>orthogonal</span> <span m='110350'>range</span>
  <span m='110650'>searching.</span> </p><p><span m='113800'>So</span> <span m='113980'>last</span>
  <span m='114310'>time,</span> <span m='115210'>we</span> <span m='115330'>saw</span>
  <span m='115570'>how</span> <span m='115690'>to</span> <span m='115810'>do</span>
  <span m='116020'>two dimensional</span> <span m='117010'>orthogonal</span> <span
  m='117580'>range</span> <span m='117820'>searching</span> <span m='118330'>in</span>
  <span m='118540'>log</span> <span m='118930'>n</span> <span m='119110'>per</span>
  <span m='119320'>query.</span> <span m='120250'>That</span> <span m='120430'>was</span>
  <span m='120670'>using</span> <span m='121060'>fractional</span> <span m='121480'>cascading,</span>
  <span m='122860'>or,</span> <span m='123100'>really,</span> <span m='123570'>half</span>
  <span m='123950'>of</span> <span m='124030'>fractional</span> <span m='124390'>cascading,</span>
  <span m='124900'>which</span> <span m='125050'>was</span> <span m='125170'>just</span>
  <span m='125350'>a</span> <span m='125410'>cross-linking</span> <span m='126100'>idea.</span>
  <span m='129729'>This</span> <span m='129910'>time</span> <span m='130150'>we're</span>
  <span m='130270'>going</span> <span m='130389'>to</span> <span m='130479'>do</span>
  <span m='130660'>3D</span> <span m='132010'>orthogonal</span> <span m='132580'>range</span>
  <span m='132820'>searching</span> <span m='133720'>in</span> <span m='133900'>log</span>
  <span m='134200'>n</span> <span m='134380'>time.</span> <span m='137100'>Our</span>
  <span m='137230'>space</span> <span m='137620'>is</span> <span m='137710'>going</span>
  <span m='137860'>to</span> <span m='137950'>go</span> <span m='138160'>up</span>
  <span m='138280'>by</span> <span m='138490'>a</span> <span m='138520'>couple</span>
  <span m='138800'>log</span> <span m='139060'>factors.</span> <span m='140720'>But</span>
  <span m='140800'>this</span> <span m='141010'>is</span> <span m='141100'>pretty</span>
  <span m='141340'>cool.</span> <span m='141580'>In</span> <span m='141700'>general,</span>
  <span m='142120'>for d</span> <span m='142300'>dimensions,</span> <span m='142960'>this</span>
  <span m='143170'>gives</span> <span m='143440'>us</span> <span m='143620'>log</span>
  <span m='143980'>to</span> <span m='144140'>the</span> <span m='144340'>d minus</span>
  <span m='145120'>two,</span> <span m='146020'>whereas</span> <span m='146260'>last</span>
  <span m='146500'>class,</span> <span m='146800'>we</span> <span m='146890'>saw</span>
  <span m='147100'>how</span> <span m='147160'>to</span> <span m='147250'>do</span>
  <span m='147400'>log</span> <span m='147730'>the</span> <span m='147850'>d minus</span>
  <span m='148330'>1.</span> </p><p><span m='148690'>Now,</span> <span m='148840'>this</span>
  <span m='149080'>is</span> <span m='149170'>static</span> <span m='149710'>only.</span>
  <span m='151180'>You</span> <span m='151330'>could</span> <span m='151450'>probably</span>
  <span m='151780'>do</span> <span m='151900'>poly-log</span> <span m='152860'>update.</span>
  <span m='153580'>But</span> <span m='153790'>let's</span> <span m='154000'>not</span>
  <span m='154150'>worry</span> <span m='154300'>about</span> <span m='154510'>updates.</span>
  <span m='154990'>We're</span> <span m='155380'>just</span> <span m='155530'>trying</span>
  <span m='155710'>to</span> <span m='155800'>do</span> <span m='155920'>static.</span>
  </p><p><span m='158350'>So</span> <span m='158530'>3D</span> <span m='159130'>orthogonal</span>
  <span m='159700'>range</span> <span m='159970'>search</span> <span m='161740'>using</span>
  <span m='162130'>fractional</span> <span m='162550'>cascading--</span> <span m='163300'>this</span>
  <span m='163510'>is</span> <span m='163630'>kind</span> <span m='163870'>of</span>
  <span m='163960'>a</span> <span m='164260'>tour</span> <span m='164440'>de</span>
  <span m='164530'>force.</span> <span m='164890'>There's</span> <span m='164980'>a</span>
  <span m='165070'>really</span> <span m='165310'>cool</span> <span m='165490'>result.</span>
  <span m='166930'>It's</span> <span m='167230'>in</span> <span m='167590'>the</span>
  <span m='168880'>"Applications</span> <span m='169450'>of</span> <span m='169540'>Fractional</span>
  <span m='169900'>Cascading"</span> <span m='170350'>paper</span> <span m='170650'>by</span>
  <span m='170960'>Chazelle</span> <span m='171280'>and Guibas.</span> <span m='172150'>And</span>
  <span m='172330'>it</span> <span m='172390'>proceeds</span> <span m='172840'>in</span>
  <span m='173020'>four</span> <span m='174280'>easy</span> <span m='174610'>steps.</span>
  <span m='175360'>Each of the</span> <span m='175780'>steps</span> <span m='176080'>are</span>
  <span m='176170'>easy,</span> <span m='176500'>but</span> <span m='176620'>it's</span>
  <span m='176710'>kind</span> <span m='176920'>of</span> <span m='177010'>amazing</span>
  <span m='177850'>where</span> <span m='178000'>we</span> <span m='178090'>get</span>
  <span m='178270'>to.</span> </p><p><span m='179600'>We're</span> <span m='179850'>going</span>
  <span m='179950'>to</span> <span m='180070'>start</span> <span m='180490'>out</span>
  <span m='180850'>with</span> <span m='181810'>a</span> <span m='181870'>two dimensional</span>
  <span m='183520'>restricted</span> <span m='184300'>orthogonal</span> <span m='184840'>range</span>
  <span m='185150'>query.</span> <span m='185850'>We'll</span> <span m='186070'>see</span>
  <span m='186310'>why</span> <span m='187300'>at</span> <span m='187420'>the</span>
  <span m='187510'>very</span> <span m='187870'>end.</span> <span m='189160'>But</span>
  <span m='189370'>this</span> <span m='189580'>is</span> <span m='189670'>actually</span>
  <span m='190120'>from</span> <span m='190420'>another</span> <span m='190780'>paper</span>
  <span m='191140'>of</span> <span m='191200'>Chazelle</span> <span m='192280'>in</span>
  <span m='192430'>the</span> <span m='192520'>same</span> <span m='192790'>year.</span>
  </p><p><span m='195590'>OK,</span> <span m='196080'>in</span> <span m='196210'>general,</span>
  <span m='196930'>remember,</span> <span m='198560'>in</span> <span m='198720'>3-D,</span>
  <span m='199660'>we're</span> <span m='199780'>trying</span> <span m='200080'>to</span>
  <span m='200200'>do</span> <span m='202840'>querying</span> <span m='203230'>with</span>
  <span m='203380'>a</span> <span m='203440'>rectangle--</span> <span m='205270'>a1,</span>
  <span m='206050'>b1,</span> <span m='206830'>a2,</span> <span m='207370'>b2,</span>
  <span m='209380'>a3,</span> <span m='210850'>b3.</span> <span m='212770'>We</span>
  <span m='212860'>want</span> <span m='213040'>to</span> <span m='213100'>know</span>
  <span m='213220'>all</span> <span m='213430'>the</span> <span m='213550'>points</span>
  <span m='213850'>in</span> <span m='213940'>that</span> <span m='214090'>rectangle.</span>
  <span m='215360'>So</span> <span m='215380'>I'm</span> <span m='215440'>going</span>
  <span m='215560'>to</span> <span m='215620'>start</span> <span m='215890'>out</span>
  <span m='216010'>with</span> <span m='216160'>a</span> <span m='216220'>very</span>
  <span m='216430'>restricted</span> <span m='216910'>form,</span> <span m='217180'>which</span>
  <span m='217330'>is</span> <span m='217450'>only</span> <span m='217750'>two dimensional,</span>
  <span m='218980'>for</span> <span m='219160'>whatever</span> <span m='219490'>reason.</span>
  <span m='219805'>And</span> <span m='220120'>we'll</span> <span m='220240'>see</span>
  <span m='220420'>why</span> <span m='220660'>later.</span> </p><p><span m='221350'>y-coordinate</span>
  <span m='222010'>and</span> <span m='222130'>z-coordinate,</span> <span m='222880'>skipping</span>
  <span m='223330'>x--</span> <span m='224560'>and</span> <span m='224800'>the</span>
  <span m='224920'>left</span> <span m='225190'>end</span> <span m='225360'>point</span>
  <span m='225520'>doesn't</span> <span m='225760'>exist.</span> <span m='226510'>So</span>
  <span m='226720'>you</span> <span m='226870'>go</span> <span m='227050'>all</span>
  <span m='227260'>the</span> <span m='227350'>way</span> <span m='227530'>up</span>
  <span m='227710'>to</span> <span m='227830'>b2,</span> <span m='228220'>and</span>
  <span m='228310'>you</span> <span m='228400'>go</span> <span m='228520'>all</span>
  <span m='228700'>the</span> <span m='228820'>way</span> <span m='228910'>up</span>
  <span m='229030'>to</span> <span m='229120'>b3.</span> <span m='229870'>This</span>
  <span m='230080'>is</span> <span m='230260'>a</span> <span m='231160'>quarter</span>
  <span m='231520'>plane</span> <span m='231880'>in</span> <span m='231970'>two</span>
  <span m='232120'>dimensions.</span> </p><p><span m='233470'>I</span> <span m='233500'>want</span>
  <span m='233650'>to</span> <span m='233710'>know</span> <span m='233830'>all</span>
  <span m='234010'>the</span> <span m='234100'>points</span> <span m='234580'>in</span>
  <span m='234730'>there.</span> <span m='234910'>It's</span> <span m='235150'>the</span>
  <span m='235240'>same</span> <span m='235480'>as</span> <span m='235540'>saying</span>
  <span m='235840'>all</span> <span m='235960'>the</span> <span m='236080'>points</span>
  <span m='237010'>that</span> <span m='237310'>are</span> <span m='237460'>dominated</span>
  <span m='238120'>by</span> <span m='238270'>this</span> <span m='238450'>point.</span>
  <span m='239860'>Both</span> <span m='240130'>y-</span> <span m='240370'>and</span>
  <span m='240460'>z-coordinates</span> <span m='241060'>are</span> <span m='241180'>dominated</span>
  <span m='242290'>by</span> <span m='242440'>that</span> <span m='242710'>yz</span>
  <span m='243070'>coordinate.</span> <span m='244150'>This</span> <span m='244360'>is</span>
  <span m='245200'>b2,</span> <span m='246255'>b3.</span> </p><p><span m='248500'>So</span>
  <span m='248680'>we</span> <span m='248800'>can</span> <span m='248920'>solve</span>
  <span m='249220'>this</span> <span m='249460'>in</span> <span m='249670'>log</span>
  <span m='249970'>n</span> <span m='250120'>time</span> <span m='252370'>plus</span>
  <span m='252650'>k.</span> <span m='253660'>But</span> <span m='253840'>I</span>
  <span m='253960'>want</span> <span m='254080'>to</span> <span m='254200'>be</span>
  <span m='254380'>a</span> <span m='254440'>little</span> <span m='254740'>bit</span>
  <span m='254860'>more</span> <span m='255010'>precise</span> <span m='255460'>about</span>
  <span m='255640'>what</span> <span m='255790'>that</span> <span m='255940'>log</span>
  <span m='256420'>in is,</span> <span m='256870'>and</span> <span m='257019'>say</span>
  <span m='257260'>that</span> <span m='257410'>this</span> <span m='257649'>costs</span>
  <span m='258880'>whatever it</span> <span m='259260'>costs</span> <span m='259630'>to</span>
  <span m='259750'>search</span> <span m='261220'>for</span> <span m='262690'>b3,</span>
  <span m='263430'>the</span> <span m='263620'>z-coordinate,</span> <span m='266180'>in</span>
  <span m='266310'>a</span> <span m='266380'>z</span> <span m='266620'>list--</span>
  <span m='267080'>in</span> <span m='267190'>a</span> <span m='267250'>list</span>
  <span m='267670'>of</span> <span m='268600'>z-coordinates</span> <span m='269980'>of</span>
  <span m='270100'>points--</span> <span m='271150'>plus</span> <span m='271690'>order</span>
  <span m='271990'>k.</span> <span m='273220'>I</span> <span m='273310'>write</span>
  <span m='273520'>it</span> <span m='273610'>this</span> <span m='273790'>way</span>
  <span m='274000'>because</span> <span m='274360'>if</span> <span m='274450'>we</span>
  <span m='274570'>have</span> <span m='274750'>many</span> <span m='275170'>searches</span>
  <span m='276190'>among</span> <span m='276640'>lists,</span> <span m='277090'>then</span>
  <span m='277300'>we</span> <span m='277420'>can</span> <span m='277570'>speed</span>
  <span m='277810'>things</span> <span m='278110'>up.</span> <span m='278740'>So</span>
  <span m='278830'>I</span> <span m='278890'>don't</span> <span m='279010'>want</span>
  <span m='279160'>to</span> <span m='279220'>just</span> <span m='279340'>think</span>
  <span m='279520'>of</span> <span m='279610'>it</span> <span m='279670'>as</span>
  <span m='279790'>log</span> <span m='280210'>n. I</span> <span m='280300'>want</span>
  <span m='280420'>to</span> <span m='280480'>think</span> <span m='280720'>of</span>
  <span m='280810'>it</span> <span m='280930'>as</span> <span m='281680'>one</span>
  <span m='281920'>of</span> <span m='281980'>these</span> <span m='282130'>fractional</span>
  <span m='282550'>cascading</span> <span m='284350'>operations.</span> </p><p><span
  m='285740'>So</span> <span m='285760'>this</span> <span m='285910'>is</span> <span
  m='285980'>the</span> <span m='286060'>time</span> <span m='286390'>bound</span>
  <span m='286660'>I</span> <span m='286720'>want</span> <span m='286870'>to</span>
  <span m='286960'>get</span> <span m='288580'>for</span> <span m='288730'>finding</span>
  <span m='289060'>the</span> <span m='289180'>k</span> <span m='289360'>points</span>
  <span m='289750'>in</span> <span m='289960'>this</span> <span m='290890'>search</span>
  <span m='291190'>range.</span> <span m='294260'>Now,</span> <span m='294370'>here's</span>
  <span m='294670'>the</span> <span m='294790'>fun</span> <span m='295000'>part.</span>
  <span m='296620'>We're</span> <span m='296740'>going</span> <span m='296860'>to</span>
  <span m='296920'>transform</span> <span m='297490'>this</span> <span m='297730'>into</span>
  <span m='298150'>a</span> <span m='298240'>kind</span> <span m='298510'>of</span>
  <span m='299140'>stabbing</span> <span m='299680'>ray</span> <span m='299900'>problem,</span>
  <span m='300400'>like</span> <span m='300610'>we</span> <span m='300700'>saw</span>
  <span m='301990'>last</span> <span m='302380'>class,</span> <span m='302820'>and</span>
  <span m='303050'>in</span> <span m='303460'>the</span> <span m='303640'>retroactive</span>
  <span m='304210'>stuff,</span> <span m='304630'>and</span> <span m='304750'>so</span>
  <span m='304870'>on.</span> </p><p><span m='327400'>So</span> <span m='327450'>let's</span>
  <span m='327630'>suppose</span> <span m='328110'>I</span> <span m='328260'>have</span>
  <span m='328590'>some</span> <span m='329820'>points.</span> <span m='334010'>I'm</span>
  <span m='334110'>just</span> <span m='334260'>going</span> <span m='334380'>to</span>
  <span m='334500'>draw</span> <span m='334800'>an</span> <span m='334890'>arbitrary</span>
  <span m='335280'>arrangement.</span> <span m='335640'>Hopefully,</span> <span m='336030'>it's</span>
  <span m='336180'>reasonably</span> <span m='337320'>interesting.</span> <span m='340140'>Those</span>
  <span m='340350'>are</span> <span m='340410'>the</span> <span m='340680'>points</span>
  <span m='340950'>I</span> <span m='341040'>want</span> <span m='341160'>to</span>
  <span m='341250'>be</span> <span m='341340'>able</span> <span m='341460'>to</span>
  <span m='341650'>query.</span> <span m='343150'>And</span> <span m='343560'>if</span>
  <span m='343800'>I'm</span> <span m='343980'>given,</span> <span m='344340'>say,</span>
  <span m='344670'>a</span> <span m='344730'>query</span> <span m='345600'>like</span>
  <span m='347430'>this</span> <span m='347700'>one,</span> <span m='349200'>I</span>
  <span m='349350'>want</span> <span m='349500'>to</span> <span m='349590'>know</span>
  <span m='349920'>all</span> <span m='350160'>the</span> <span m='350280'>points</span>
  <span m='351390'>in</span> <span m='351540'>here.</span> </p><p><span m='352750'>So</span>
  <span m='352800'>what</span> <span m='352920'>I'm</span> <span m='352980'>going</span>
  <span m='353100'>to</span> <span m='353190'>do</span> <span m='353490'>is</span>
  <span m='353820'>draw</span> <span m='354330'>a</span> <span m='354750'>leftward</span>
  <span m='355380'>horizontal</span> <span m='356070'>ray</span> <span m='357090'>from</span>
  <span m='357390'>the</span> <span m='357510'>query</span> <span m='357840'>point.</span>
  <span m='360000'>And</span> <span m='360180'>I'm</span> <span m='360240'>going</span>
  <span m='360390'>to</span> <span m='360480'>draw--</span> <span m='360865'>maybe</span>
  <span m='361250'>use a</span> <span m='361680'>color--</span> <span m='363150'>upward</span>
  <span m='363720'>vertical</span> <span m='364230'>rays</span> <span m='364710'>from</span>
  <span m='364980'>each</span> <span m='365190'>of</span> <span m='365250'>the</span>
  <span m='365340'>points.</span> <span m='373690'>OK.</span> <span m='374080'>And</span>
  <span m='376360'>where</span> <span m='376540'>there's</span> <span m='376740'>crossings,</span>
  <span m='377830'>those</span> <span m='378130'>correspond</span> <span m='378760'>to</span>
  <span m='379030'>points</span> <span m='379450'>that</span> <span m='379630'>are</span>
  <span m='379720'>in</span> <span m='379900'>the</span> <span m='380650'>query</span>
  <span m='381310'>quarter</span> <span m='381580'>plane.</span> <span m='382610'>OK,</span>
  <span m='382810'>so</span> <span m='382990'>same</span> <span m='383230'>problem--</span>
  <span m='384140'>but</span> <span m='384190'>now,</span> <span m='384340'>thinking</span>
  <span m='384670'>about</span> <span m='384910'>rays.</span> </p><p><span m='386870'>So</span>
  <span m='386920'>here's</span> <span m='387160'>a</span> <span m='387220'>cool</span>
  <span m='387460'>thing</span> <span m='387700'>you</span> <span m='387820'>can</span>
  <span m='388000'>do</span> <span m='388780'>with</span> <span m='388990'>this</span>
  <span m='390370'>approach.</span> <span m='391460'>So</span> <span m='392650'>we</span>
  <span m='392800'>want</span> <span m='392950'>to</span> <span m='393010'>preprocess</span>
  <span m='394180'>these</span> <span m='394360'>vertical</span> <span m='394750'>rays</span>
  <span m='395500'>so</span> <span m='395650'>that,</span> <span m='395770'>then,</span>
  <span m='395980'>we</span> <span m='396100'>can</span> <span m='396250'>stab</span>
  <span m='397360'>with</span> <span m='397590'>a</span> <span m='397630'>horizontal</span>
  <span m='398160'>ray.</span> <span m='398290'>And</span> <span m='398680'>it's</span>
  <span m='398860'>actually</span> <span m='399130'>easier</span> <span m='399370'>to</span>
  <span m='399430'>think</span> <span m='399610'>of</span> <span m='399700'>it</span>
  <span m='399760'>as</span> <span m='399850'>coming</span> <span m='400240'>from</span>
  <span m='400420'>the</span> <span m='400510'>left,</span> <span m='401320'>because</span>
  <span m='401500'>that's</span> <span m='401680'>kind</span> <span m='401860'>of</span>
  <span m='401950'>a</span> <span m='401980'>consistent</span> <span m='402580'>x-coordinate,</span>
  <span m='403480'>and</span> <span m='403630'>walking</span> <span m='404110'>to</span>
  <span m='404230'>the</span> <span m='404350'>right.</span> <span m='404680'>I'd</span>
  <span m='404800'>like</span> <span m='404950'>to</span> <span m='405040'>find</span>
  <span m='405340'>this</span> <span m='405610'>intersection,</span> <span m='406310'>then</span>
  <span m='406420'>find</span> <span m='406630'>this</span> <span m='406840'>one,</span>
  <span m='407350'>then</span> <span m='407500'>find</span> <span m='407680'>this</span>
  <span m='407830'>one.</span> <span m='407950'>Eventually,</span> <span m='408310'>I</span>
  <span m='408370'>get</span> <span m='408550'>to</span> <span m='408670'>the</span>
  <span m='408790'>desired</span> <span m='409840'>y-coordinate.</span> <span m='410650'>This</span>
  <span m='410830'>is</span> <span m='411220'>the y</span> <span m='411520'>direction,</span>
  <span m='412900'>and</span> <span m='413080'>this</span> <span m='413290'>is</span>
  <span m='414460'>z</span> <span m='414730'>direction.</span> <span m='416630'>Then</span>
  <span m='417010'>I</span> <span m='417100'>stop.</span> </p><p><span m='418510'>So</span>
  <span m='418630'>if</span> <span m='418720'>I</span> <span m='418780'>could</span>
  <span m='418900'>get</span> <span m='419080'>started</span> <span m='419500'>over</span>
  <span m='419680'>here</span> <span m='419860'>in</span> <span m='419980'>log</span>
  <span m='420250'>n</span> <span m='420400'>time,</span> <span m='420700'>and</span>
  <span m='420790'>then</span> <span m='420970'>do</span> <span m='421090'>a</span>
  <span m='421180'>walk</span> <span m='421630'>in</span> <span m='421780'>constant</span>
  <span m='422200'>time</span> <span m='422560'>per</span> <span m='423310'>intersection,</span>
  <span m='424150'>I'd</span> <span m='424360'>be</span> <span m='424540'>golden.</span>
  <span m='426110'>That</span> <span m='426940'>is</span> <span m='427120'>possible.</span>
  <span m='428900'>And</span> <span m='429280'>the</span> <span m='429640'>way</span>
  <span m='430060'>that</span> <span m='430790'>Chazelle</span> <span m='431830'>did</span>
  <span m='432070'>this--</span> <span m='433690'>I'm going</span> <span m='433870'>to</span>
  <span m='433960'>erase</span> <span m='434380'>the</span> <span m='434510'>query</span>
  <span m='434950'>ray--</span> <span m='439440'>is</span> <span m='439830'>to</span>
  <span m='440580'>decompose</span> <span m='441240'>the</span> <span m='441330'>plane</span>
  <span m='442230'>in</span> <span m='442420'>a</span> <span m='442530'>pretty</span>
  <span m='442770'>simple</span> <span m='443040'>way.</span> <span m='443250'>We're</span>
  <span m='443310'>going</span> <span m='443430'>to</span> <span m='443520'>draw</span>
  <span m='444530'>a</span> <span m='444570'>horizontal</span> <span m='446010'>segment</span>
  <span m='446670'>from</span> <span m='446880'>each</span> <span m='447060'>point.</span>
  <span m='447480'>We're</span> <span m='447600'>going</span> <span m='447720'>to</span>
  <span m='447780'>extend</span> <span m='448200'>it</span> <span m='448320'>to</span>
  <span m='448470'>the</span> <span m='448560'>right</span> <span m='449100'>until</span>
  <span m='449370'>it</span> <span m='449460'>hits</span> <span m='449580'>something,</span>
  <span m='449970'>extend it</span> <span m='450420'>to</span> <span m='450540'>the</span>
  <span m='450630'>left.</span> <span m='450930'>In</span> <span m='450990'>this</span>
  <span m='451140'>case,</span> <span m='451350'>it</span> <span m='451440'>goes</span>
  <span m='451650'>off</span> <span m='451800'>to</span> <span m='451890'>infinity.</span>
  </p><p><span m='452940'>Here,</span> <span m='453210'>I</span> <span m='453280'>extend</span>
  <span m='453810'>this</span> <span m='454080'>guy.</span> <span m='454620'>I</span>
  <span m='455100'>extend</span> <span m='455490'>this</span> <span m='455640'>guy.</span>
  <span m='456886'>I</span> <span m='457230'>extend</span> <span m='457770'>this</span>
  <span m='458010'>guy.</span> <span m='459630'>I extend</span> <span m='459810'>this</span>
  <span m='460020'>guy.</span> <span m='462090'>And</span> <span m='462480'>extend</span>
  <span m='462870'>this</span> <span m='463050'>one</span> <span m='463260'>out</span>
  <span m='463500'>here.</span> <span m='468815'>I'm going</span> <span m='469240'>to</span>
  <span m='469380'>add</span> <span m='469650'>one</span> <span m='469860'>more</span>
  <span m='471060'>point</span> <span m='471480'>over</span> <span m='471750'>here--</span>
  <span m='473310'>a</span> <span m='473370'>little</span> <span m='473580'>more</span>
  <span m='473730'>exciting.</span> <span m='476700'>So</span> <span m='476850'>this</span>
  <span m='477030'>stops</span> <span m='477630'>there.</span> <span m='478430'>This</span>
  <span m='478650'>goes</span> <span m='478950'>to</span> <span m='479100'>there.</span>
  </p><p><span m='479370'>AUDIENCE:</span> <span m='479576'>One</span> <span m='479782'>more--</span>
  <span m='480194'>to the right.</span> </p><p><span m='480606'>ERIK DEMAINE:</span>
  <span m='481020'>One</span> <span m='481320'>more</span> <span m='481740'>up</span>
  <span m='481900'>here--</span> <span m='482160'>thanks.</span> <span m='484230'>OK.</span>
  <span m='485220'>So</span> <span m='485400'>this</span> <span m='485610'>is</span>
  <span m='485790'>kind</span> <span m='486030'>of</span> <span m='486660'>decomposition</span>
  <span m='487470'>into</span> <span m='488550'>slabs</span> <span m='489030'>or</span>
  <span m='489120'>bricks</span> <span m='489480'>or</span> <span m='489570'>something.</span>
  <span m='490330'>It</span> <span m='490580'>looks</span> <span m='490800'>good.</span>
  <span m='491220'>And</span> <span m='491310'>so</span> <span m='491820'>the</span>
  <span m='492060'>idea</span> <span m='492360'>is,</span> <span m='493200'>over</span>
  <span m='493470'>here,</span> <span m='494410'>there's,</span> <span m='494690'>at</span>
  <span m='494790'>most,</span> <span m='495210'>n</span> <span m='495510'>different</span>
  <span m='496940'>rays</span> <span m='497340'>that</span> <span m='497460'>make</span>
  <span m='497610'>it</span> <span m='497700'>all</span> <span m='497820'>the</span>
  <span m='497880'>way</span> <span m='498000'>to</span> <span m='498120'>the</span>
  <span m='498180'>left.</span> </p><p><span m='501210'>Do</span> <span m='501390'>a</span>
  <span m='501450'>search.</span> <span m='501840'>That's</span> <span m='502080'>your</span>
  <span m='502200'>z</span> <span m='502410'>search.</span> <span m='503400'>So</span>
  <span m='503550'>that's</span> <span m='505440'>this</span> <span m='505570'>search</span>
  <span m='505920'>for</span> <span m='506190'>b3</span> <span m='506670'>in</span>
  <span m='506820'>the</span> <span m='506880'>z</span> <span m='507080'>list.</span>
  <span m='508140'>So</span> <span m='508230'>remember,</span> <span m='508560'>our</span>
  <span m='508710'>goal</span> <span m='508920'>is</span> <span m='509040'>to</span>
  <span m='509160'>get</span> <span m='509310'>to</span> <span m='509430'>here.</span>
  <span m='510060'>So</span> <span m='510240'>we</span> <span m='510300'>search</span>
  <span m='510540'>for</span> <span m='510630'>that</span> <span m='510780'>z-coordinate</span>
  <span m='511380'>over</span> <span m='511590'>here.</span> <span m='511800'>We</span>
  <span m='511860'>say,</span> <span m='512039'>OK,</span> <span m='512429'>it</span>
  <span m='512520'>falls</span> <span m='512820'>here.</span> </p><p><span m='514080'>Then</span>
  <span m='514289'>I</span> <span m='514440'>enter</span> <span m='514799'>this</span>
  <span m='515010'>face.</span> <span m='516039'>I'd</span> <span m='516090'>like</span>
  <span m='516270'>to</span> <span m='516390'>then</span> <span m='517020'>navigate</span>
  <span m='517500'>to</span> <span m='517620'>this</span> <span m='517830'>face,</span>
  <span m='518159'>say,</span> <span m='518370'>OK,</span> <span m='519179'>that's</span>
  <span m='519419'>where</span> <span m='519570'>I</span> <span m='519690'>am</span>
  <span m='519809'>now.</span> <span m='521070'>By</span> <span m='521340'>crossing</span>
  <span m='522030'>this</span> <span m='522809'>edge,</span> <span m='523440'>I</span>
  <span m='523559'>know</span> <span m='523740'>that</span> <span m='523890'>this</span>
  <span m='524039'>point</span> <span m='524280'>is</span> <span m='524370'>actually</span>
  <span m='524700'>in</span> <span m='524820'>my</span> <span m='524970'>answer.</span>
  <span m='525960'>And</span> <span m='526110'>then</span> <span m='526320'>I</span>
  <span m='526650'>cross</span> <span m='527040'>this</span> <span m='527280'>edge,
  so</span> <span m='527590'>I</span> <span m='527670'>know</span> <span m='527790'>that</span>
  <span m='527940'>this</span> <span m='528090'>point</span> <span m='528330'>is</span>
  <span m='528450'>in</span> <span m='528540'>my</span> <span m='528720'>answer.</span>
  <span m='529490'>Then</span> <span m='529680'>I</span> <span m='529770'>cross</span>
  <span m='531240'>this</span> <span m='531480'>ray,</span> <span m='531960'>so</span>
  <span m='532140'>I</span> <span m='532200'>know</span> <span m='532350'>that</span>
  <span m='532440'>this</span> <span m='532620'>point</span> <span m='532800'>is</span>
  <span m='532920'>in</span> <span m='532980'>my</span> <span m='533160'>answer.</span>
  <span m='533530'>Then I</span> <span m='534020'>say,</span> <span m='534110'>OK,</span>
  <span m='534330'>I</span> <span m='534390'>reached</span> <span m='534720'>my</span>
  <span m='534930'>desired</span> <span m='535290'>y-coordinate.</span> <span m='535860'>Stop.</span>
  </p><p><span m='537060'>So</span> <span m='537150'>if</span> <span m='537270'>I</span>
  <span m='537360'>can</span> <span m='537510'>do</span> <span m='537630'>each</span>
  <span m='537900'>of</span> <span m='537960'>these</span> <span m='538170'>traversals</span>
  <span m='538830'>in</span> <span m='539010'>constant</span> <span m='539490'>time,</span>
  <span m='541650'>I'd</span> <span m='541830'>be</span> <span m='541980'>all</span>
  <span m='542100'>set.</span> <span m='543820'>So</span> <span m='543840'>I</span>
  <span m='543900'>do</span> <span m='544110'>one</span> <span m='544320'>search</span>
  <span m='544580'>at</span> <span m='544620'>the</span> <span m='544710'>beginning,</span>
  <span m='545280'>then</span> <span m='545430'>constant</span> <span m='545810'>time</span>
  <span m='546180'>per</span> <span m='546480'>query.</span> <span m='546900'>We</span>
  <span m='547020'>know</span> <span m='547170'>how</span> <span m='547260'>to</span>
  <span m='547380'>solve</span> <span m='547590'>this</span> <span m='547740'>problem.</span>
  <span m='548290'>We</span> <span m='548400'>can</span> <span m='548550'>do</span>
  <span m='548700'>it</span> <span m='548790'>with</span> <span m='548910'>range</span>
  <span m='549150'>trees</span> <span m='550110'>and</span> <span m='550380'>log</span>
  <span m='550680'>n</span> <span m='550800'>time</span> <span m='551010'>preparation.</span>
  <span m='551610'>But</span> <span m='551760'>this</span> <span m='552840'>is</span>
  <span m='552990'>a</span> <span m='553290'>particular</span> <span m='553800'>way</span>
  <span m='553920'>to</span> <span m='554010'>solve</span> <span m='554280'>it</span>
  <span m='554370'>that</span> <span m='554520'>will</span> <span m='554670'>work</span>
  <span m='554880'>with</span> <span m='555000'>fractional</span> <span m='555390'>cascading</span>
  <span m='555930'>when</span> <span m='556050'>we</span> <span m='556170'>do</span>
  <span m='556290'>many</span> <span m='556530'>of</span> <span m='556650'>them.</span>
  </p><p><span m='558540'>OK.</span> <span m='559560'>Cool.</span> <span m='561450'>Can</span>
  <span m='561660'>I</span> <span m='561720'>do</span> <span m='561840'>this</span>
  <span m='562020'>in</span> <span m='562410'>constant</span> <span m='562830'>time?</span>
  <span m='567320'>Maybe</span> <span m='567590'>not,</span> <span m='569180'>because</span>
  <span m='570230'>it's</span> <span m='570800'>this</span> <span m='570930'>sort</span>
  <span m='571190'>of</span> <span m='571280'>scenario.</span> <span m='572150'>If</span>
  <span m='572840'>I</span> <span m='572930'>draw</span> <span m='573080'>a</span>
  <span m='573110'>whole</span> <span m='573290'>bunch</span> <span m='573530'>of</span>
  <span m='573590'>points</span> <span m='573890'>like</span> <span m='574100'>this,</span>
  <span m='574460'>they'll</span> <span m='574940'>each</span> <span m='575450'>have</span>
  <span m='575660'>a</span> <span m='575720'>segment.</span> <span m='576140'>And
  in</span> <span m='576260'>general,</span> <span m='577640'>this</span> <span m='577940'>face</span>
  <span m='578480'>will</span> <span m='578750'>have</span> <span m='579050'>large</span>
  <span m='579410'>degree.</span> <span m='580300'>And</span> <span m='580340'>so</span>
  <span m='580460'>I</span> <span m='580610'>need</span> <span m='583040'>to</span>
  <span m='583310'>sort</span> <span m='583520'>of</span> <span m='583580'>find</span>
  <span m='584000'>my</span> <span m='584180'>z-coordinate</span> <span m='584780'>again,</span>
  <span m='585650'>somewhere</span> <span m='585950'>in</span> <span m='586040'>here.</span>
  </p><p><span m='586980'>It</span> <span m='587330'>turns</span> <span m='587630'>out,</span>
  <span m='588560'>with,</span> <span m='588740'>essentially,</span> <span m='589280'>fractional</span>
  <span m='589700'>cascading</span> <span m='590180'>again,</span> <span m='590960'>you</span>
  <span m='591110'>can</span> <span m='591230'>avoid</span> <span m='591530'>that.</span>
  <span m='593270'>If</span> <span m='593420'>you</span> <span m='593540'>have</span>
  <span m='594320'>many</span> <span m='595070'>segments</span> <span m='595550'>here,</span>
  <span m='596540'>just</span> <span m='596960'>extend</span> <span m='597470'>half</span>
  <span m='597770'>of</span> <span m='597860'>them.</span> <span m='598400'>So</span>
  <span m='598760'>maybe</span> <span m='598980'>I'll</span> <span m='599030'>extend</span>
  <span m='599390'>this</span> <span m='599570'>one</span> <span m='599780'>over</span>
  <span m='600830'>and</span> <span m='601010'>this</span> <span m='601190'>one</span>
  <span m='601370'>over.</span> <span m='603560'>It looks</span> <span m='603770'>like</span>
  <span m='603920'>fractional</span> <span m='604370'>cascading.</span> </p><p><span
  m='604880'>I'm</span> <span m='605000'>taking</span> <span m='605390'>half</span>
  <span m='605720'>of</span> <span m='605840'>the</span> <span m='605960'>elements</span>
  <span m='606380'>here,</span> <span m='606980'>inserting</span> <span m='607400'>them</span>
  <span m='607550'>into</span> <span m='607730'>the</span> <span m='607850'>previous</span>
  <span m='608450'>list,</span> <span m='608990'>which</span> <span m='609200'>is</span>
  <span m='609320'>the</span> <span m='609440'>left</span> <span m='609650'>side</span>
  <span m='609890'>of</span> <span m='609980'>the</span> <span m='610100'>face.</span>
  <span m='611390'>If</span> <span m='611480'>this</span> <span m='611660'>now</span>
  <span m='611870'>has</span> <span m='612080'>too</span> <span m='612230'>many,</span>
  <span m='612560'>well,</span> <span m='612890'>half</span> <span m='613190'>of</span>
  <span m='613280'>them</span> <span m='613490'>get</span> <span m='613640'>promoted.</span>
  <span m='614390'>But</span> <span m='614960'>it</span> <span m='615350'>decreases</span>
  <span m='616040'>exponentially.</span> <span m='616910'>And</span> <span m='617030'>so</span>
  <span m='617240'>the</span> <span m='617330'>total</span> <span m='617660'>amount</span>
  <span m='617960'>of</span> <span m='618140'>extra</span> <span m='618470'>edges</span>
  <span m='618800'>I'm</span> <span m='618920'>adding</span> <span m='619190'>here</span>
  <span m='619430'>is</span> <span m='619610'>only</span> <span m='620210'>linear.</span>
  <span m='621560'>So</span> <span m='621770'>linear</span> <span m='622160'>space--</span>
  <span m='624890'>I'm</span> <span m='624980'>not</span> <span m='625100'>going</span>
  <span m='625220'>to</span> <span m='625280'>prove</span> <span m='625550'>this</span>
  <span m='625730'>formally</span> <span m='626150'>here,</span> <span m='626540'>but</span>
  <span m='626720'>it's</span> <span m='626810'>the</span> <span m='626900'>same</span>
  <span m='627170'>idea</span> <span m='627380'>as</span> <span m='627500'>fractional</span>
  <span m='627860'>cascading.</span> <span m='629030'>We</span> <span m='629150'>just</span>
  <span m='629300'>need</span> <span m='629520'>it</span> <span m='629600'>as</span>
  <span m='629780'>a</span> <span m='629870'>tool</span> <span m='630260'>to</span>
  <span m='630410'>get</span> <span m='630620'>to</span> <span m='630740'>3D.</span>
  </p><p><span m='632690'>You</span> <span m='632870'>can</span> <span m='633080'>extend</span>
  <span m='633410'>these</span> <span m='633560'>things,</span> <span m='634040'>and</span>
  <span m='634190'>then</span> <span m='634400'>every</span> <span m='634910'>face</span>
  <span m='635270'>will</span> <span m='635390'>have</span> <span m='635510'>bounded</span>
  <span m='635730'>degree.</span> <span m='636340'>And</span> <span m='636470'>so</span>
  <span m='636590'>you</span> <span m='636680'>can</span> <span m='636800'>just</span>
  <span m='636950'>look</span> <span m='637190'>at</span> <span m='637310'>every</span>
  <span m='637640'>single</span> <span m='638420'>rightward</span> <span m='638900'>edge</span>
  <span m='639170'>in</span> <span m='639290'>constant</span> <span m='639670'>time,
  and</span> <span m='640010'>figure</span> <span m='640250'>out</span> <span m='640370'>which</span>
  <span m='640610'>one</span> <span m='641210'>has</span> <span m='641510'>your</span>
  <span m='641750'>z-coordinate.</span> <span m='642860'>Follow</span> <span m='643160'>that</span>
  <span m='643370'>edge.</span> <span m='643820'>And</span> <span m='643910'>so</span>
  <span m='644060'>every</span> <span m='644330'>time</span> <span m='644600'>you're</span>
  <span m='644720'>crossing</span> <span m='645220'>a</span> <span m='646220'>ray</span>
  <span m='646520'>and</span> <span m='646610'>getting</span> <span m='646850'>an</span>
  <span m='646940'>output,</span> <span m='647480'>you</span> <span m='647720'>can</span>
  <span m='647900'>pay</span> <span m='648380'>only</span> <span m='648650'>constant</span>
  <span m='649010'>time</span> <span m='649250'>to</span> <span m='649370'>get</span>
  <span m='649520'>it.</span> <span m='650840'>Pretty</span> <span m='650990'>cool.</span>
  <span m='652700'>That's</span> <span m='652940'>the</span> <span m='653480'>first</span>
  <span m='653690'>step.</span> <span m='654380'>Question.</span> </p><p><span m='655323'>AUDIENCE:</span>
  <span m='655487'>So</span> <span m='655651'>when</span> <span m='655816'>you say</span>
  <span m='656309'>that</span> <span m='656802'>a particular face</span> <span m='657295'>has
  too</span> <span m='657788'>many crossings,</span> <span m='658281'>what</span>
  <span m='658774'>do you</span> <span m='659267'>define</span> <span m='659760'>too
  many?</span> </p><p><span m='661250'>ERIK DEMAINE:</span> <span m='661385'>More</span>
  <span m='661520'>than</span> <span m='661700'>a</span> <span m='661790'>constant.</span>
  <span m='662450'>In</span> <span m='662720'>general,</span> <span m='663110'>you</span>
  <span m='663200'>just</span> <span m='663350'>look</span> <span m='663530'>at</span>
  <span m='663620'>the</span> <span m='663740'>right</span> <span m='663950'>side</span>
  <span m='665360'>of</span> <span m='665540'>a</span> <span m='665600'>face,</span>
  <span m='666900'>and</span> <span m='667730'>just</span> <span m='667970'>take</span>
  <span m='668210'>half</span> <span m='668510'>of</span> <span m='668630'>those</span>
  <span m='669050'>things</span> <span m='669350'>and</span> <span m='669500'>propagate</span>
  <span m='669920'>it</span> <span m='669980'>to the</span> <span m='670100'>left.</span>
  <span m='670340'>Just</span> <span m='670520'>do</span> <span m='670670'>that</span>
  <span m='670850'>right</span> <span m='671030'>to</span> <span m='671150'>left</span>
  <span m='671420'>in</span> <span m='671630'>one</span> <span m='671810'>pass.</span>
  <span m='672560'>I</span> <span m='672590'>think</span> <span m='672770'>you</span>
  <span m='672860'>might</span> <span m='673010'>also</span> <span m='673220'>need</span>
  <span m='673340'>to</span> <span m='673400'>do</span> <span m='673550'>it</span>
  <span m='673610'>left</span> <span m='673820'>to</span> <span m='673940'>right,</span>
  <span m='674960'>if</span> <span m='675080'>you</span> <span m='675200'>want</span>
  <span m='675320'>to</span> <span m='675410'>have</span> <span m='675830'>bounded</span>
  <span m='676310'>leftward</span> <span m='676880'>degree.</span> <span m='677210'>But</span>
  <span m='677560'>I'm</span> <span m='677840'>not</span> <span m='677990'>sure</span>
  <span m='678140'>that</span> <span m='678260'>really</span> <span m='678440'>matters.</span>
  </p><p><span m='680510'>I</span> <span m='680570'>think</span> <span m='680810'>you</span>
  <span m='680900'>just</span> <span m='681230'>do</span> <span m='681410'>one</span>
  <span m='681590'>pass</span> <span m='681890'>right</span> <span m='682070'>to</span>
  <span m='682190'>left,</span> <span m='683450'>and</span> <span m='683570'>half</span>
  <span m='683840'>the</span> <span m='683930'>guys</span> <span m='684260'>keep</span>
  <span m='684680'>getting</span> <span m='684920'>promoted.</span> <span m='685890'>And</span>
  <span m='686080'>it's</span> <span m='686210'>the</span> <span m='686330'>same</span>
  <span m='686570'>thing,</span> <span m='686820'>where you're</span> <span m='686930'>promoting</span>
  <span m='687470'>from</span> <span m='687710'>the</span> <span m='687830'>LI</span>
  <span m='688130'>primes,</span> <span m='688640'>not</span> <span m='688790'>from</span>
  <span m='688970'>the</span> <span m='689060'>LI.</span> <span m='689510'>So</span>
  <span m='689630'>it's</span> <span m='689780'>everybody</span> <span m='690290'>who</span>
  <span m='690890'>came</span> <span m='691100'>from</span> <span m='691190'>the</span>
  <span m='691280'>right</span> <span m='691490'>plus</span> <span m='691820'>whatever</span>
  <span m='692180'>you</span> <span m='692300'>originally</span> <span m='692720'>had.</span>
  <span m='693440'>Half</span> <span m='693710'>of</span> <span m='693770'>them</span>
  <span m='693890'>get</span> <span m='694040'>promoted</span> <span m='694470'>to
  the left,</span> <span m='694820'>but</span> <span m='695000'>because it's</span>
  <span m='695450'>geometrically</span> <span m='695990'>decreasing,</span> <span
  m='696830'>all</span> <span m='697090'>is</span> <span m='697220'>OK.</span> <span
  m='697850'>This</span> <span m='699480'>is</span> <span m='699710'>earlier</span>
  <span m='700100'>than</span> <span m='700610'>fractional</span> <span m='700970'>cascading,</span>
  <span m='701420'>but</span> <span m='701570'>I</span> <span m='701660'>would</span>
  <span m='701780'>guess</span> <span m='702020'>it's</span> <span m='702260'>what</span>
  <span m='702950'>motivated</span> <span m='703490'>them</span> <span m='703670'>to</span>
  <span m='703820'>then</span> <span m='704060'>do</span> <span m='704300'>general</span>
  <span m='705320'>fractional</span> <span m='705710'>cascading.</span> </p><p><span
  m='709020'>Other</span> <span m='709170'>questions?</span> <span m='711210'>I</span>
  <span m='711360'>know</span> <span m='711540'>this</span> <span m='711730'>is a</span>
  <span m='711780'>little</span> <span m='712020'>bit</span> <span m='712140'>vague.</span>
  <span m='712500'>But</span> <span m='712660'>the</span> <span m='712980'>more</span>
  <span m='713220'>exciting</span> <span m='713580'>stuff,</span> <span m='713850'>to</span>
  <span m='713970'>me,</span> <span m='714150'>is</span> <span m='714480'>the</span>
  <span m='714870'>next</span> <span m='715650'>three</span> <span m='715830'>steps.</span>
  <span m='717360'>So</span> <span m='717660'>let's</span> <span m='717870'>move</span>
  <span m='718110'>on</span> <span m='719160'>to</span> <span m='719340'>those.</span>
  <span m='719625'>.</span> </p><p><span m='724310'>So</span> <span m='734770'>this</span>
  <span m='735080'>is</span> <span m='735150'>a</span> <span m='735210'>tool</span>
  <span m='735510'>for</span> <span m='735630'>doing</span> <span m='736350'>two dimensional</span>
  <span m='739530'>quarter</span> <span m='739830'>plane</span> <span m='740100'>searching.</span>
  <span m='742290'>The</span> <span m='742710'>next</span> <span m='742950'>thing</span>
  <span m='743100'>we're</span> <span m='743160'>going</span> <span m='743310'>to</span>
  <span m='743370'>do</span> <span m='743580'>is</span> <span m='743670'>make</span>
  <span m='743850'>it</span> <span m='743970'>three dimensional.</span> <span m='745830'>This</span>
  <span m='746040'>is</span> <span m='746190'>actually</span> <span m='746520'>something</span>
  <span m='746850'>we</span> <span m='746970'>already</span> <span m='747180'>know</span>
  <span m='747330'>how</span> <span m='747450'>to</span> <span m='747540'>do.</span>
  <span m='748210'>And</span> <span m='748290'>we're</span> <span m='748410'>going</span>
  <span m='748560'>to</span> <span m='748620'>do</span> <span m='748770'>it</span>
  <span m='748860'>in</span> <span m='748950'>exactly</span> <span m='749430'>the</span>
  <span m='749490'>same</span> <span m='749730'>way</span> <span m='751050'>we</span>
  <span m='751200'>knew</span> <span m='751350'>how</span> <span m='751560'>to</span>
  <span m='751710'>before.</span> </p><p><span m='753660'>Suppose</span> <span m='753930'>you</span>
  <span m='753990'>have</span> <span m='754080'>a</span> <span m='754140'>three dimensional</span>
  <span m='754950'>query,</span> <span m='756750'>and</span> <span m='757290'>two</span>
  <span m='757590'>of</span> <span m='757710'>the</span> <span m='758250'>intervals</span>
  <span m='758900'>start</span> <span m='759110'>at</span> <span m='759270'>minus</span>
  <span m='759550'>infinity,</span> <span m='760440'>but</span> <span m='760770'>the</span>
  <span m='760970'>new</span> <span m='761190'>x-coordinate</span> <span m='762390'>is</span>
  <span m='762570'>a</span> <span m='762630'>regular</span> <span m='763140'>interval.</span>
  <span m='763590'>You</span> <span m='764100'>can</span> <span m='764250'>specify</span>
  <span m='764640'>both</span> <span m='764910'>endpoints.</span> <span m='766810'>I</span>
  <span m='767130'>want</span> <span m='767280'>to</span> <span m='767370'>do</span>
  <span m='767550'>this</span> <span m='767820'>in</span> <span m='771890'>log</span>
  <span m='772460'>n</span> <span m='772830'>searches</span> <span m='776130'>plus</span>
  <span m='776400'>k.</span> <span m='777530'>k</span> <span m='777950'>is the</span>
  <span m='778310'>size of</span> <span m='778560'>the</span> <span m='778650'>output.</span>
  <span m='780990'>How</span> <span m='781140'>do</span> <span m='781260'>I</span>
  <span m='781320'>do</span> <span m='781470'>this</span> <span m='782070'>using</span>
  <span m='782730'>one?</span> </p><p><span m='785760'>Two words--</span> <span m='789150'>range</span>
  <span m='789730'>tree.</span> <span m='791500'>Yep.</span> <span m='792570'>Easy.</span>
  <span m='793020'>Just</span> <span m='793170'>do</span> <span m='793360'>1D</span>
  <span m='793690'>range</span> <span m='793990'>tree</span> <span m='797550'>on</span>
  <span m='797850'>x.</span> <span m='799740'>And</span> <span m='799890'>then</span>
  <span m='800130'>each</span> <span m='800370'>node</span> <span m='804030'>stores</span>
  <span m='806430'>that</span> <span m='806640'>data</span> <span m='806880'>structure--</span>
  <span m='808560'>one--</span> <span m='811580'>on</span> <span m='812310'>points</span>
  <span m='812820'>in</span> <span m='813000'>the</span> <span m='813090'>subtree.</span>
  <span m='819110'>And</span> <span m='819240'>so</span> <span m='819420'>just</span>
  <span m='819660'>like</span> <span m='819840'>before,</span> <span m='823650'>you</span>
  <span m='823830'>get</span> <span m='824150'>log</span> <span m='824490'>n</span>
  <span m='824650'>subtrees</span> <span m='825120'>that</span> <span m='825240'>represent</span>
  <span m='825660'>your</span> <span m='825810'>x</span> <span m='826080'>interval.</span>
  <span m='832580'>You</span> <span m='832700'>look</span> <span m='832940'>at</span>
  <span m='833120'>the</span> <span m='833270'>root</span> <span m='833480'>of</span>
  <span m='833570'>each</span> <span m='833750'>one,</span> <span m='835910'>and</span>
  <span m='836060'>it</span> <span m='836150'>stores</span> <span m='836570'>a</span>
  <span m='836870'>one</span> <span m='837170'>data</span> <span m='837380'>structure.</span>
  <span m='837890'>You</span> <span m='838050'>query</span> <span m='838400'>each</span>
  <span m='838640'>of</span> <span m='838700'>them</span> <span m='839540'>for</span>
  <span m='841240'>b2</span> <span m='842010'>and</span> <span m='842180'>b3</span>
  <span m='842810'>for</span> <span m='842960'>that</span> <span m='843170'>interval</span>
  <span m='843950'>among</span> <span m='844220'>the</span> <span m='844310'>y-</span>
  <span m='844490'>and</span> <span m='844580'>z-coordinates.</span> </p><p><span
  m='846170'>And</span> <span m='846380'>each</span> <span m='846620'>of</span> <span
  m='846680'>them</span> <span m='846860'>costs</span> <span m='847310'>a</span> <span
  m='847370'>search</span> <span m='847940'>plus</span> <span m='848240'>order</span>
  <span m='848470'>k.</span> <span m='849250'>The</span> <span m='849370'>k's</span>
  <span m='849680'>sum</span> <span m='849980'>up</span> <span m='850130'>to</span>
  <span m='850250'>order</span> <span m='850460'>k.</span> <span m='851660'>So</span>
  <span m='851840'>we</span> <span m='851930'>end</span> <span m='852050'>up</span>
  <span m='852140'>doing</span> <span m='852380'>log</span> <span m='852650'>n</span>
  <span m='852800'>searches</span> <span m='854060'>of</span> <span m='854210'>that</span>
  <span m='854420'>type</span> <span m='856220'>plus</span> <span m='856580'>k</span>
  <span m='857150'>time.</span> <span m='858100'>And</span> <span m='858220'>we</span>
  <span m='858290'>can</span> <span m='858440'>now</span> <span m='858650'>solve</span>
  <span m='858920'>this</span> <span m='859100'>kind</span> <span m='859280'>of</span>
  <span m='859370'>3D</span> <span m='859600'>query.</span> <span m='860330'>This</span>
  <span m='860540'>is</span> <span m='860630'>really</span> <span m='860840'>easy.</span>
  <span m='861080'>This</span> <span m='861260'>is</span> <span m='861320'>what</span>
  <span m='861440'>we</span> <span m='861560'>did</span> <span m='861680'>last</span>
  <span m='861920'>class.</span> </p><p><span m='863570'>The</span> <span m='863750'>cool</span>
  <span m='863990'>thing,</span> <span m='864300'>of</span> <span m='864320'>course,</span>
  <span m='864720'>is</span> <span m='864740'>that,</span> <span m='864920'>by</span>
  <span m='865100'>doing</span> <span m='865310'>log</span> <span m='865550'>n</span>
  <span m='865700'>searches,</span> <span m='866210'>it's</span> <span m='866330'>always</span>
  <span m='866630'>searching</span> <span m='867470'>for</span> <span m='867620'>the</span>
  <span m='867740'>same</span> <span m='868280'>thing--</span> <span m='868670'>b3--</span>
  <span m='870140'>in</span> <span m='870920'>various</span> <span m='871380'>c lists.</span>
  <span m='871880'>We</span> <span m='872000'>know</span> <span m='872150'>by</span>
  <span m='872300'>fractional</span> <span m='872690'>cascading</span> <span m='873150'>this</span>
  <span m='873290'>is</span> <span m='873380'>actually</span> <span m='873680'>log</span>
  <span m='873970'>n</span> <span m='874100'>time.</span> <span m='874910'>We're</span>
  <span m='875390'>doing</span> <span m='875600'>log</span> <span m='875840'>n</span>
  <span m='875990'>searches</span> <span m='877880'>in</span> <span m='878060'>k lists--</span>
  <span m='880330'>and</span> <span m='880700'>slightly</span> <span m='881060'>different</span>
  <span m='881360'>k</span> <span m='881630'>here,</span> <span m='881970'>sorry.</span>
  <span m='885730'>It's</span> <span m='885910'>actually</span> <span m='886180'>log</span>
  <span m='886630'>n</span> <span m='886915'>lists.</span> <span m='887200'>But</span>
  <span m='887350'>we</span> <span m='887470'>know</span> <span m='887740'>from</span>
  <span m='887950'>this</span> <span m='888130'>bound,</span> <span m='889420'>we're</span>
  <span m='889630'>going</span> <span m='889750'>to</span> <span m='889870'>get</span>
  <span m='890020'>order</span> <span m='890230'>log</span> <span m='890470'>n</span>
  <span m='890620'>plus</span> <span m='890830'>k.</span> </p><p><span m='891160'>But</span>
  <span m='891310'>I</span> <span m='891340'>don't</span> <span m='891460'>want</span>
  <span m='891580'>to</span> <span m='891790'>do</span> <span m='891970'>fractional</span>
  <span m='892360'>cascading</span> <span m='892820'>yet,</span> <span m='892960'>because</span>
  <span m='893140'>we're</span> <span m='893230'>not</span> <span m='893410'>done.</span>
  <span m='894130'>This</span> <span m='894520'>is</span> <span m='895840'>a</span>
  <span m='895900'>sort</span> <span m='896170'>of</span> <span m='896260'>three</span>
  <span m='896470'>dimensional</span> <span m='897310'>orthogonal</span> <span m='897790'>range</span>
  <span m='898000'>query.</span> <span m='898270'>But</span> <span m='898390'>I</span>
  <span m='898480'>want</span> <span m='898660'>to</span> <span m='898720'>put</span>
  <span m='899380'>a2</span> <span m='899830'>here</span> <span m='900550'>and</span>
  <span m='900730'>a3</span> <span m='901150'>here.</span> <span m='901960'>We're</span>
  <span m='902080'>going</span> <span m='902200'>to</span> <span m='902260'>do</span>
  <span m='902380'>that</span> <span m='902740'>step</span> <span m='903040'>by</span>
  <span m='903160'>step.</span> <span m='904030'>First</span> <span m='904240'>step</span>
  <span m='904510'>is</span> <span m='905130'>a2.</span> <span m='906730'>We're</span>
  <span m='906790'>going</span> <span m='906910'>to</span> <span m='906970'>do</span>
  <span m='907090'>it in</span> <span m='907170'>exactly</span> <span m='907630'>the</span>
  <span m='907750'>same</span> <span m='908020'>way,</span> <span m='908620'>twice.</span>
  </p><p><span m='927630'>Again,</span> <span m='928140'>I</span> <span m='928260'>want</span>
  <span m='928440'>to</span> <span m='928500'>do</span> <span m='928710'>it</span>
  <span m='928910'>in</span> <span m='929130'>log n</span> <span m='929610'>searches</span>
  <span m='931920'>plus</span> <span m='932290'>k.</span> <span m='934620'>It's</span>
  <span m='935040'>the</span> <span m='935180'>same</span> <span m='935460'>time</span>
  <span m='935700'>bound</span> <span m='936130'>I</span> <span m='936230'>want</span>
  <span m='936270'>to</span> <span m='936330'>put</span> <span m='936510'>into</span>
  <span m='936690'>a2.</span> <span m='937890'>The</span> <span m='937980'>cost</span>
  <span m='938400'>will</span> <span m='938520'>be</span> <span m='938700'>a</span>
  <span m='938790'>log</span> <span m='939120'>n</span> <span m='939270'>factor</span>
  <span m='939630'>in</span> <span m='939750'>space.</span> <span m='941650'>And</span>
  <span m='942900'>it's</span> <span m='943160'>a</span> <span m='943230'>cool</span>
  <span m='943440'>transformation.</span> <span m='944190'>It's</span> <span m='944400'>a</span>
  <span m='944490'>general</span> <span m='944850'>transformation.</span> <span m='945510'>Whenever</span>
  <span m='945840'>you</span> <span m='945960'>have</span> <span m='946770'>a</span>
  <span m='946830'>data</span> <span m='947040'>structure</span> <span m='947430'>has</span>
  <span m='947610'>a</span> <span m='947670'>minus</span> <span m='947970'>infinity,</span>
  <span m='949330'>you</span> <span m='949380'>can</span> <span m='949530'>turn</span>
  <span m='949770'>it</span> <span m='949890'>into</span> <span m='951090'>a</span>
  <span m='951180'>lower</span> <span m='951390'>bound,</span> <span m='953180'>magically--</span>
  <span m='955260'>almost</span> <span m='955950'>the</span> <span m='956070'>same</span>
  <span m='956400'>way</span> <span m='956610'>as</span> <span m='956910'>we</span>
  <span m='957030'>did</span> <span m='957210'>here,</span> <span m='958030'>except</span>
  <span m='958230'>we're</span> <span m='958320'>not</span> <span m='958500'>going</span>
  <span m='958650'>to</span> <span m='958710'>lose</span> <span m='958920'>a</span>
  <span m='958980'>log</span> <span m='959190'>factor</span> <span m='959490'>in</span>
  <span m='959580'>time--</span> <span m='960450'>only</span> <span m='960750'>in</span>
  <span m='960870'>space.</span> </p><p><span m='962730'>So</span> <span m='965100'>I'm</span>
  <span m='965160'>going</span> <span m='965310'>to</span> <span m='965400'>say</span>
  <span m='965970'>it's</span> <span m='966240'>kind</span> <span m='966720'>of</span>
  <span m='966810'>like</span> <span m='967920'>a</span> <span m='968110'>range</span>
  <span m='968530'>tree</span> <span m='970440'>on</span> <span m='970950'>the</span>
  <span m='971070'>y-coordinate.</span> <span m='971820'>y-coordinate</span> <span
  m='972000'>is</span> <span m='972450'>the</span> <span m='972540'>one</span> <span
  m='972690'>that</span> <span m='972780'>we</span> <span m='972930'>want</span> <span
  m='973080'>to</span> <span m='973200'>extend.</span> <span m='977250'>And</span>
  <span m='977430'>you</span> <span m='977610'>may</span> <span m='977850'>remember</span>
  <span m='982080'>there</span> <span m='982200'>was</span> <span m='982440'>this</span>
  <span m='983670'>brief</span> <span m='983910'>question</span> <span m='984390'>last</span>
  <span m='984630'>time.</span> <span m='985140'>In</span> <span m='985340'>a</span>
  <span m='985380'>1D</span> <span m='985700'>range</span> <span m='986010'>tree,</span>
  <span m='986730'>what</span> <span m='987060'>key</span> <span m='987360'>does</span>
  <span m='987540'>a</span> <span m='987630'>node</span> <span m='987900'>store?</span>
  <span m='988590'>It</span> <span m='988680'>just</span> <span m='988890'>has</span>
  <span m='989070'>to</span> <span m='989160'>store</span> <span m='989400'>something</span>
  <span m='989850'>that's</span> <span m='990060'>in</span> <span m='990330'>between</span>
  <span m='991080'>what's</span> <span m='991290'>in</span> <span m='991380'>the</span>
  <span m='991470'>left</span> <span m='991680'>subtree</span> <span m='992070'>and</span>
  <span m='992160'>what's</span> <span m='992310'>in</span> <span m='992400'>the</span>
  <span m='992490'>right</span> <span m='992670'>subtree.</span> </p><p><span m='993820'>So</span>
  <span m='994650'>I</span> <span m='995040'>proposed</span> <span m='995700'>you</span>
  <span m='995850'>could</span> <span m='996000'>store</span> <span m='997410'>max</span>
  <span m='998100'>of</span> <span m='998640'>left</span> <span m='998940'>subtree.</span>
  <span m='1001770'>And</span> <span m='1002300'>that's</span> <span m='1002510'>enough</span>
  <span m='1002750'>to</span> <span m='1002870'>do</span> <span m='1003020'>a</span>
  <span m='1003080'>search.</span> <span m='1003600'>Then</span> <span m='1003710'>you</span>
  <span m='1003830'>know</span> <span m='1004010'>whether</span> <span m='1004220'>you</span>
  <span m='1004310'>should</span> <span m='1004460'>go</span> <span m='1004550'>in</span>
  <span m='1004610'>the</span> <span m='1004670'>left</span> <span m='1004850'>subtree</span>
  <span m='1005300'>or</span> <span m='1005540'>the</span> <span m='1005660'>right</span>
  <span m='1005840'>subtree.</span> <span m='1006390'>Just</span> <span m='1006560'>compare</span>
  <span m='1006920'>with</span> <span m='1007040'>that</span> <span m='1007220'>key.</span>
  <span m='1008160'>So</span> <span m='1008240'>same</span> <span m='1008510'>as</span>
  <span m='1008600'>before--</span> <span m='1009030'>we're going</span> <span m='1009170'>to</span>
  <span m='1009230'>store</span> <span m='1009440'>that</span> <span m='1009590'>key.</span>
  <span m='1009900'>Except</span> <span m='1010010'>now,</span> <span m='1010780'>I'm</span>
  <span m='1010880'>making</span> <span m='1011120'>it</span> <span m='1011240'>explicit,</span>
  <span m='1011660'>because</span> <span m='1011840'>we</span> <span m='1012050'>really</span>
  <span m='1012290'>need</span> <span m='1012440'>to</span> <span m='1012560'>know</span>
  <span m='1012680'>what</span> <span m='1012800'>that</span> <span m='1012950'>key</span>
  <span m='1013190'>is.</span> </p><p><span m='1015760'>A</span> <span m='1016125'>node</span>
  <span m='1016490'>v</span> <span m='1016970'>will</span> <span m='1017180'>also</span>
  <span m='1017540'>store</span> <span m='1021860'>two</span> <span m='1022070'>of</span>
  <span m='1022190'>these.</span> <span m='1023730'>So</span> <span m='1023780'>it's</span>
  <span m='1023900'>going</span> <span m='1024050'>to</span> <span m='1024109'>store</span>
  <span m='1024770'>the</span> <span m='1024950'>two</span> <span m='1025349'>data</span>
  <span m='1025640'>structure</span> <span m='1028220'>on</span> <span m='1028460'>the</span>
  <span m='1028550'>points</span> <span m='1029599'>in</span> <span m='1029810'>the</span>
  <span m='1029960'>right</span> <span m='1030380'>subtree--</span> <span m='1033859'>not</span>
  <span m='1034130'>the</span> <span m='1034220'>entire</span> <span m='1034550'>subtree,</span>
  <span m='1034880'>just</span> <span m='1035150'>the</span> <span m='1035270'>right</span>
  <span m='1035510'>subtree.</span> <span m='1036740'>And</span> <span m='1037670'>it's</span>
  <span m='1037849'>going</span> <span m='1038060'>to</span> <span m='1038180'>store</span>
  <span m='1038630'>a</span> <span m='1038839'>y-inverted</span> <span m='1041020'>two</span>
  <span m='1041240'>structure</span> <span m='1045920'>on</span> <span m='1047829'>points</span>
  <span m='1049460'>in</span> <span m='1049760'>the</span> <span m='1049850'>left</span>
  <span m='1050150'>subtree.</span> </p><p><span m='1052860'>So</span> <span m='1052940'>this</span>
  <span m='1053180'>is</span> <span m='1053300'>the</span> <span m='1053450'>new</span>
  <span m='1054770'>part.</span> <span m='1056840'>And</span> <span m='1056990'>what</span>
  <span m='1057170'>does</span> <span m='1057290'>y-inverted</span> <span m='1058040'>mean?</span>
  <span m='1059480'>It</span> <span m='1059600'>means</span> <span m='1059870'>that</span>
  <span m='1059990'>you</span> <span m='1060140'>can</span> <span m='1060290'>search</span>
  <span m='1060650'>for</span> <span m='1073200'>boxes</span> <span m='1073800'>like</span>
  <span m='1074070'>this.</span> <span m='1075130'>So</span> <span m='1076150'>regularly,</span>
  <span m='1076470'>a</span> <span m='1076790'>two</span> <span m='1077130'>structure</span>
  <span m='1077610'>is</span> <span m='1077790'>sort</span> <span m='1077970'>of</span>
  <span m='1078570'>left-centered,</span> <span m='1079700'>and</span> <span m='1080250'>the</span>
  <span m='1080370'>left</span> <span m='1080610'>end</span> <span m='1080730'>point</span>
  <span m='1080940'>is</span> <span m='1081030'>undefined,</span> <span m='1081510'>and</span>
  <span m='1081600'>it</span> <span m='1081660'>goes</span> <span m='1081870'>up</span>
  <span m='1081990'>to</span> <span m='1082140'>b3.</span> <span m='1082980'>Now,</span>
  <span m='1083140'>I</span> <span m='1083220'>want</span> <span m='1083400'>something</span>
  <span m='1083790'>that's</span> <span m='1083970'>right-centered.</span> <span m='1085230'>It</span>
  <span m='1085320'>goes</span> <span m='1085530'>up</span> <span m='1085650'>to</span>
  <span m='1085740'>infinity</span> <span m='1086370'>on</span> <span m='1086580'>the</span>
  <span m='1086640'>right</span> <span m='1086850'>side.</span> <span m='1087240'>But</span>
  <span m='1087660'>you</span> <span m='1087720'>can</span> <span m='1087870'>start</span>
  <span m='1088140'>at an</span> <span m='1088290'>arbitrary</span> <span m='1088565'>a2.</span>
  </p><p><span m='1089640'>How</span> <span m='1089790'>do</span> <span m='1089880'>I</span>
  <span m='1089970'>make</span> <span m='1090150'>such</span> <span m='1090360'>a</span>
  <span m='1090390'>data</span> <span m='1090570'>structure</span> <span m='1091440'>do</span>
  <span m='1091560'>exactly</span> <span m='1092010'>the</span> <span m='1092130'>same</span>
  <span m='1092370'>thing,</span> <span m='1092610'>but</span> <span m='1092730'>with</span>
  <span m='1092850'>this</span> <span m='1093000'>inverted,</span> <span m='1093450'>which</span>
  <span m='1093630'>means,</span> <span m='1093900'>do</span> <span m='1093990'>exactly</span>
  <span m='1094470'>this,</span> <span m='1094740'>but</span> <span m='1094950'>with</span>
  <span m='1096210'>this</span> <span m='1096780'>inverted?</span> <span m='1100260'>Easy</span>
  <span m='1100590'>to</span> <span m='1100800'>do--</span> <span m='1101190'>just</span>
  <span m='1101430'>twice</span> <span m='1101790'>as</span> <span m='1101880'>many</span>
  <span m='1102090'>data</span> <span m='1102330'>structures.</span> <span m='1102585'>So</span>
  <span m='1102840'>you</span> <span m='1103010'>can</span> <span m='1103200'>think</span>
  <span m='1103410'>of</span> <span m='1103500'>that</span> <span m='1103620'>as</span>
  <span m='1103710'>one</span> <span m='1103920'>prime</span> <span m='1104790'>and</span>
  <span m='1104940'>two</span> <span m='1105150'>prime.</span> <span m='1105480'>I'll</span>
  <span m='1105570'>call</span> <span m='1105780'>this</span> <span m='1105990'>two</span>
  <span m='1106230'>prime,</span> <span m='1107160'>explicitly.</span> <span m='1110330'>OK,</span>
  <span m='1110760'>now,</span> <span m='1110970'>the</span> <span m='1111060'>big</span>
  <span m='1111210'>question</span> <span m='1111540'>is,</span> <span m='1111690'>why</span>
  <span m='1112050'>is</span> <span m='1112200'>this</span> <span m='1112350'>enough?</span>
  <span m='1113260'>So</span> <span m='1113430'>let's</span> <span m='1114200'>do</span>
  <span m='1114330'>that.</span> </p><p><span m='1122010'>How</span> <span m='1122340'>do</span>
  <span m='1122550'>I</span> <span m='1122670'>do</span> <span m='1122940'>a</span>
  <span m='1123030'>query</span> <span m='1125600'>in</span> <span m='1125790'>data</span>
  <span m='1125970'>structure</span> <span m='1126390'>three?</span> <span m='1129920'>The</span>
  <span m='1130350'>basic</span> <span m='1130680'>idea</span> <span m='1131070'>is</span>
  <span m='1131280'>simple.</span> <span m='1132590'>We're</span> <span m='1132930'>going</span>
  <span m='1133090'>to</span> <span m='1133230'>walk</span> <span m='1133560'>down</span>
  <span m='1133770'>the</span> <span m='1133860'>tree.</span> </p><p><span m='1134410'>Now,</span>
  <span m='1134460'>before</span> <span m='1134970'>we</span> <span m='1135120'>walk</span>
  <span m='1135360'>down</span> <span m='1135570'>the</span> <span m='1135630'>tree,</span>
  <span m='1136500'>and</span> <span m='1136710'>the</span> <span m='1136860'>interval</span>
  <span m='1137310'>is</span> <span m='1137430'>represented</span> <span m='1137970'>by</span>
  <span m='1138140'>log</span> <span m='1138480'>n</span> <span m='1138630'>different</span>
  <span m='1138900'>subtrees--</span> <span m='1139320'>we</span> <span m='1139470'>can't</span>
  <span m='1139680'>afford</span> <span m='1139980'>that</span> <span m='1140160'>anymore.</span>
  <span m='1141250'>We</span> <span m='1141270'>can</span> <span m='1141420'>really</span>
  <span m='1141690'>only</span> <span m='1141900'>afford</span> <span m='1142260'>a</span>
  <span m='1142320'>constant</span> <span m='1142920'>number</span> <span m='1143160'>of</span>
  <span m='1143280'>calls</span> <span m='1143670'>to</span> <span m='1143850'>this</span>
  <span m='1144020'>data</span> <span m='1144270'>structure,</span> <span m='1144720'>if</span>
  <span m='1145160'>we're</span> <span m='1145260'>not</span> <span m='1145380'>going</span>
  <span m='1145500'>to</span> <span m='1145590'>get</span> <span m='1146250'>an</span>
  <span m='1146340'>extra</span> <span m='1146550'>log</span> <span m='1146830'>blowup.</span>
  <span m='1147810'>So</span> <span m='1147960'>I</span> <span m='1148020'>don't</span>
  <span m='1148290'>want</span> <span m='1148470'>to</span> <span m='1148560'>walk</span>
  <span m='1148920'>and</span> <span m='1149040'>then</span> <span m='1149190'>fork</span>
  <span m='1149610'>and</span> <span m='1149890'>then</span> <span m='1150240'>visit</span>
  <span m='1150570'>all</span> <span m='1150660'>these</span> <span m='1150810'>subtrees.</span>
  <span m='1151350'>I</span> <span m='1151470'>could</span> <span m='1151740'>do</span>
  <span m='1151890'>that.</span> </p><p><span m='1152950'>But</span> <span m='1152970'>it</span>
  <span m='1153030'>turns</span> <span m='1153300'>out,</span> <span m='1153420'>with</span>
  <span m='1153600'>this</span> <span m='1154020'>structure,</span> <span m='1154530'>I</span>
  <span m='1154650'>can</span> <span m='1154830'>be</span> <span m='1154950'>a</span>
  <span m='1154980'>little</span> <span m='1155190'>bit</span> <span m='1155340'>more</span>
  <span m='1155490'>efficient.</span> <span m='1156990'>Because,</span> <span m='1157830'>essentially,</span>
  <span m='1158580'>I</span> <span m='1158850'>want</span> <span m='1159140'>to</span>
  <span m='1159240'>do</span> <span m='1160140'>an</span> <span m='1160290'>interval</span>
  <span m='1161490'>like</span> <span m='1161700'>this.</span> <span m='1165060'>The</span>
  <span m='1165180'>queries</span> <span m='1165510'>I'm</span> <span m='1165630'>allowed</span>
  <span m='1166550'>is,</span> <span m='1166680'>I</span> <span m='1166770'>can</span>
  <span m='1166920'>do</span> <span m='1167070'>a</span> <span m='1167130'>query</span>
  <span m='1168360'>that's</span> <span m='1168930'>infinite</span> <span m='1169290'>to</span>
  <span m='1169380'>the</span> <span m='1169470'>left,</span> <span m='1169860'>and</span>
  <span m='1169980'>I</span> <span m='1170070'>can</span> <span m='1170190'>do</span>
  <span m='1170280'>a</span> <span m='1170310'>query</span> <span m='1170650'>that's</span>
  <span m='1170850'>infinite</span> <span m='1171240'>to</span> <span m='1171360'>the</span>
  <span m='1171480'>right.</span> <span m='1172510'>So</span> <span m='1172560'>the</span>
  <span m='1172710'>intersection</span> <span m='1173280'>of</span> <span m='1173340'>those</span>
  <span m='1173610'>would</span> <span m='1173760'>be</span> <span m='1173940'>what</span>
  <span m='1174090'>I</span> <span m='1174180'>want.</span> <span m='1174530'>I</span>
  <span m='1174630'>can't</span> <span m='1174870'>really</span> <span m='1175080'>compute</span>
  <span m='1175380'>intersection.</span> <span m='1176390'>So</span> <span m='1176560'>it</span>
  <span m='1176630'>take</span> <span m='1176820'>too</span> <span m='1177000'>much</span>
  <span m='1177330'>time</span> <span m='1177600'>to</span> <span m='1178110'>list</span>
  <span m='1178350'>those.</span> </p><p><span m='1179460'>But</span> <span m='1179670'>if,</span>
  <span m='1179790'>somehow,</span> <span m='1180210'>I</span> <span m='1180300'>could</span>
  <span m='1180450'>get</span> <span m='1180600'>this</span> <span m='1180750'>left</span>
  <span m='1181020'>endpoint</span> <span m='1181410'>in</span> <span m='1181560'>another</span>
  <span m='1181920'>way,</span> <span m='1182130'>using</span> <span m='1182460'>the</span>
  <span m='1182580'>tree,</span> <span m='1183550'>then</span> <span m='1183630'>I</span>
  <span m='1183690'>can</span> <span m='1183870'>do</span> <span m='1184110'>a</span>
  <span m='1184220'>leftward</span> <span m='1184680'>infinity</span> <span m='1185250'>query.</span>
  <span m='1186450'>So</span> <span m='1186660'>that's</span> <span m='1186870'>what</span>
  <span m='1186960'>we're</span> <span m='1187030'>going</span> <span m='1187170'>to</span>
  <span m='1187230'>do.</span> <span m='1190590'>And</span> <span m='1191430'>once</span>
  <span m='1191670'>I</span> <span m='1191760'>say</span> <span m='1191940'>walk</span>
  <span m='1192210'>down</span> <span m='1192390'>the</span> <span m='1192480'>tree,</span>
  <span m='1192720'>it's</span> <span m='1192840'>pretty</span> <span m='1193230'>clear</span>
  <span m='1193710'>what</span> <span m='1193890'>you</span> <span m='1194070'>have</span>
  <span m='1194280'>to</span> <span m='1194400'>do.</span> </p><p><span m='1195360'>When</span>
  <span m='1195480'>you</span> <span m='1195570'>visit</span> <span m='1195900'>a</span>
  <span m='1195960'>node,</span> <span m='1198090'>if</span> <span m='1200130'>the</span>
  <span m='1200220'>key</span> <span m='1200790'>of</span> <span m='1201060'>the</span>
  <span m='1201150'>node</span> <span m='1202950'>is</span> <span m='1203190'>less</span>
  <span m='1203670'>than--</span> <span m='1204870'>what</span> <span m='1204960'>are</span>
  <span m='1205020'>you</span> <span m='1205080'>searching</span> <span m='1205470'>for--</span>
  <span m='1205740'>a2,</span> <span m='1206310'>b2--</span> <span m='1207930'>so</span>
  <span m='1208110'>a2</span> <span m='1208560'>is</span> <span m='1208680'>less</span>
  <span m='1208950'>than</span> <span m='1209330'>b2.</span> <span m='1210870'>And</span>
  <span m='1211110'>if</span> <span m='1211260'>the</span> <span m='1211380'>key</span>
  <span m='1211620'>of</span> <span m='1211710'>the</span> <span m='1211800'>node</span>
  <span m='1212640'>is</span> <span m='1212850'>to</span> <span m='1213000'>the</span>
  <span m='1213060'>left,</span> <span m='1213610'>that</span> <span m='1213690'>means</span>
  <span m='1214020'>that the</span> <span m='1214170'>stuff</span> <span m='1214410'>we're</span>
  <span m='1214500'>interested</span> <span m='1214850'>to</span> <span m='1215250'>is</span>
  <span m='1216150'>to</span> <span m='1216270'>the</span> <span m='1216390'>right.</span>
  <span m='1217810'>So</span> <span m='1218040'>walk</span> <span m='1218400'>right.</span>
  <span m='1223710'>If</span> <span m='1225180'>the</span> <span m='1225300'>key</span>
  <span m='1225810'>of</span> <span m='1226110'>the</span> <span m='1226270'>node</span>
  <span m='1227490'>is</span> <span m='1227670'>greater</span> <span m='1228060'>than</span>
  <span m='1228600'>the</span> <span m='1228720'>interval,</span> <span m='1231240'>then</span>
  <span m='1231510'>walk</span> <span m='1231810'>left.</span> <span m='1233820'>That's</span>
  <span m='1233990'>sort</span> <span m='1234130'>of</span> <span m='1234210'>the</span>
  <span m='1234300'>easy</span> <span m='1234570'>case.</span> </p><p><span m='1235950'>And</span>
  <span m='1236070'>then</span> <span m='1236340'>the</span> <span m='1236460'>interesting</span>
  <span m='1236850'>case</span> <span m='1237060'>is</span> <span m='1237270'>this</span>
  <span m='1237450'>fork.</span> <span m='1237960'>Before,</span> <span m='1238380'>we</span>
  <span m='1238530'>had</span> <span m='1238680'>to</span> <span m='1238770'>do</span>
  <span m='1238920'>a</span> <span m='1238980'>lot</span> <span m='1239160'>of</span>
  <span m='1239220'>work</span> <span m='1239460'>at</span> <span m='1239520'>the</span>
  <span m='1239640'>fork.</span> <span m='1240270'>Now,</span> <span m='1240420'>I</span>
  <span m='1240510'>claim</span> <span m='1240840'>we</span> <span m='1240960'>only</span>
  <span m='1241140'>need</span> <span m='1241290'>to</span> <span m='1241410'>do</span>
  <span m='1241560'>constant</span> <span m='1242100'>work</span> <span m='1242820'>at</span>
  <span m='1242970'>the</span> <span m='1243060'>fork.</span> </p><p><span m='1244500'>So</span>
  <span m='1244770'>if</span> <span m='1245940'>the</span> <span m='1246060'>key</span>
  <span m='1246390'>falls</span> <span m='1246750'>between</span> <span m='1247470'>a2</span>
  <span m='1247680'>and</span> <span m='1248070'>b2,</span> <span m='1249720'>so</span>
  <span m='1249840'>our</span> <span m='1249960'>interval</span> <span m='1250440'>is</span>
  <span m='1250560'>stabbed</span> <span m='1251100'>by</span> <span m='1251340'>the</span>
  <span m='1251490'>key</span> <span m='1251790'>of</span> <span m='1251940'>the</span>
  <span m='1252030'>node,</span> <span m='1253410'>then</span> <span m='1256020'>I</span>
  <span m='1256140'>want</span> <span m='1256380'>to</span> <span m='1256500'>query</span>
  <span m='1259170'>the</span> <span m='1259290'>two</span> <span m='1259860'>data</span>
  <span m='1260130'>structure--</span> <span m='1260430'>two</span> <span m='1260730'>is</span>
  <span m='1261220'>the right</span> <span m='1261490'>number--</span> <span m='1261720'>yeah--</span>
  <span m='1262590'>and</span> <span m='1262890'>I</span> <span m='1262950'>want</span>
  <span m='1263100'>to</span> <span m='1263160'>query</span> <span m='1263610'>the</span>
  <span m='1263730'>two</span> <span m='1263940'>prime</span> <span m='1264390'>data</span>
  <span m='1264600'>structure.</span> <span m='1265450'>So</span> <span m='1265470'>I'm</span>
  <span m='1265530'>going</span> <span m='1265650'>to</span> <span m='1265710'>do</span>
  <span m='1265890'>two</span> <span m='1266130'>calls</span> <span m='1266760'>to</span>
  <span m='1267120'>data</span> <span m='1267440'>structure</span> <span m='1267720'>two.</span>
  <span m='1267890'>And</span> <span m='1267980'>so</span> <span m='1268080'>I</span>
  <span m='1268110'>only</span> <span m='1268290'>get</span> <span m='1268410'>a</span>
  <span m='1268470'>constant</span> <span m='1268830'>factor</span> <span m='1269580'>blowup.</span>
  </p><p><span m='1271530'>And</span> <span m='1271920'>what</span> <span m='1272190'>could</span>
  <span m='1272430'>I</span> <span m='1272520'>possibly</span> <span m='1273060'>search</span>
  <span m='1273330'>for?</span> <span m='1273670'>Well,</span> <span m='1277400'>two--</span>
  <span m='1278730'>I'm</span> <span m='1278970'>able</span> <span m='1279180'>to</span>
  <span m='1279330'>do--</span> <span m='1280780'>what</span> <span m='1281070'>is
  it--</span> <span m='1281660'>a1,</span> <span m='1282130'>b1,</span> <span m='1286290'>minus</span>
  <span m='1286830'>infinity</span> <span m='1288020'>b2,</span> <span m='1289920'>and</span>
  <span m='1290430'>minus</span> <span m='1290760'>infinity</span> <span m='1291350'>b3.</span>
  <span m='1291780'>We're</span> <span m='1291900'>not</span> <span m='1292050'>fixing</span>
  <span m='1292500'>the</span> <span m='1292620'>z-coordinate</span> <span m='1293250'>yet.</span>
  <span m='1294720'>And</span> <span m='1295110'>with</span> <span m='1295200'>two</span>
  <span m='1295410'>prime,</span> <span m='1296040'>I</span> <span m='1296250'>can</span>
  <span m='1296520'>do</span> <span m='1297030'>the</span> <span m='1297390'>left</span>
  <span m='1297720'>endpoint</span> <span m='1298110'>bounded.</span> <span m='1301080'>Once</span>
  <span m='1301320'>I've</span> <span m='1301400'>set</span> <span m='1301590'>things</span>
  <span m='1301830'>up,</span> <span m='1301980'>this</span> <span m='1302160'>is,</span>
  <span m='1302250'>like,</span> <span m='1302430'>the</span> <span m='1302520'>only</span>
  <span m='1302790'>thing</span> <span m='1302970'>you</span> <span m='1303090'>could</span>
  <span m='1303240'>possibly</span> <span m='1303690'>do.</span> <span m='1304740'>But</span>
  <span m='1304890'>I</span> <span m='1304950'>claim</span> <span m='1305220'>it's</span>
  <span m='1305340'>actually</span> <span m='1305640'>the</span> <span m='1305760'>right</span>
  <span m='1305910'>answer.</span> </p><p><span m='1312210'>OK,</span> <span m='1312450'>what</span>
  <span m='1312600'>does</span> <span m='1312750'>this</span> <span m='1312930'>mean?</span>
  <span m='1313590'>Two</span> <span m='1313800'>prime</span> <span m='1314610'>is--</span>
  <span m='1315660'>we're</span> <span m='1315780'>doing</span> <span m='1316350'>rightward</span>
  <span m='1316910'>infinity</span> <span m='1318390'>searches</span> <span m='1319350'>in</span>
  <span m='1319500'>the</span> <span m='1319590'>left</span> <span m='1319980'>subtree.</span>
  <span m='1320650'>So</span> <span m='1320730'>here's</span> <span m='1321000'>v.</span>
  <span m='1322150'>Here</span> <span m='1322370'>is</span> <span m='1322530'>the</span>
  <span m='1322650'>left</span> <span m='1322890'>subtree</span> <span m='1323340'>of</span>
  <span m='1323460'>v,</span> <span m='1324180'>and the</span> <span m='1324510'>right</span>
  <span m='1324780'>subtree</span> <span m='1325200'>of v.</span> <span m='1325540'>So</span>
  <span m='1325590'>this</span> <span m='1325740'>is</span> <span m='1325800'>a</span>
  <span m='1325860'>bunch</span> <span m='1326070'>of</span> <span m='1326130'>points</span>
  <span m='1326400'>down</span> <span m='1326580'>here,</span> <span m='1326790'>a
  bunch</span> <span m='1327030'>of points</span> <span m='1327270'>down</span> <span
  m='1327450'>here.</span> <span m='1328740'>We</span> <span m='1328860'>know</span>
  <span m='1329040'>that</span> <span m='1329190'>the</span> <span m='1329370'>interval</span>
  <span m='1330630'>looks</span> <span m='1330900'>something</span> <span m='1331260'>like</span>
  <span m='1331440'>this.</span> <span m='1331780'>It</span> <span m='1331880'>straddles</span>
  <span m='1333030'>this</span> <span m='1333270'>node.</span> <span m='1335160'>That's</span>
  <span m='1335820'>what</span> <span m='1336000'>this</span> <span m='1336210'>means.</span>
  </p><p><span m='1337840'>And</span> <span m='1337890'>so</span> <span m='1338070'>what</span>
  <span m='1338190'>we'd</span> <span m='1338340'>really</span> <span m='1338550'>like</span>
  <span m='1338760'>is</span> <span m='1338880'>this</span> <span m='1339090'>stuff</span>
  <span m='1339860'>plus</span> <span m='1340260'>this</span> <span m='1340470'>stuff.</span>
  <span m='1341850'>That</span> <span m='1342000'>looks</span> <span m='1342180'>good.</span>
  <span m='1342390'>Because</span> <span m='1342570'>this</span> <span m='1342720'>goes</span>
  <span m='1342990'>to</span> <span m='1343170'>infinity</span> <span m='1343650'>on</span>
  <span m='1343740'>the</span> <span m='1343830'>right.</span> <span m='1344580'>That's</span>
  <span m='1344790'>the</span> <span m='1344910'>two</span> <span m='1345090'>prime</span>
  <span m='1345360'>search.</span> <span m='1346140'>And</span> <span m='1346230'>this</span>
  <span m='1346350'>goes</span> <span m='1346530'>to</span> <span m='1346590'>infinity</span>
  <span m='1347210'>on</span> <span m='1347370'>the</span> <span m='1347460'>left.</span>
  <span m='1348240'>That's</span> <span m='1348450'>the</span> <span m='1348540'>two</span>
  <span m='1348720'>search.</span> </p><p><span m='1348990'>As</span> <span m='1349080'>long</span>
  <span m='1349260'>as</span> <span m='1349320'>you</span> <span m='1349410'>restrict</span>
  <span m='1349800'>to</span> <span m='1349920'>this</span> <span m='1350060'>subtree,</span>
  <span m='1350520'>which</span> <span m='1350700'>is</span> <span m='1350790'>what</span>
  <span m='1350940'>we've</span> <span m='1351090'>always</span> <span m='1351300'>been</span>
  <span m='1351450'>doing,</span> <span m='1352200'>and,</span> <span m='1352320'>in</span>
  <span m='1352380'>particular,</span> <span m='1352860'>here,</span> <span m='1353100'>too,</span>
  <span m='1353610'>it's</span> <span m='1353790'>only</span> <span m='1354150'>on</span>
  <span m='1354270'>the</span> <span m='1355860'>points</span> <span m='1356160'>that</span>
  <span m='1356250'>are</span> <span m='1356340'>in</span> <span m='1356490'>the</span>
  <span m='1356580'>right</span> <span m='1356730'>subtree.</span> <span m='1357480'>Two</span>
  <span m='1357630'>prime</span> <span m='1357990'>is</span> <span m='1358110'>only</span>
  <span m='1358410'>on</span> <span m='1358500'>the</span> <span m='1358590'>points</span>
  <span m='1358860'>in</span> <span m='1358920'>the</span> <span m='1358980'>left</span>
  <span m='1359190'>subtree.</span> <span m='1360290'>And</span> <span m='1360450'>so</span>
  <span m='1360570'>that's</span> <span m='1360780'>it.</span> <span m='1360900'>We're</span>
  <span m='1361020'>golden.</span> <span m='1362220'>Actually,</span> <span m='1362640'>we</span>
  <span m='1362820'>only</span> <span m='1363060'>need</span> <span m='1363210'>to</span>
  <span m='1363360'>do</span> <span m='1364260'>a</span> <span m='1364320'>rightward</span>
  <span m='1364740'>infinity</span> <span m='1365160'>search,</span> <span m='1365430'>and
  a</span> <span m='1365700'>leftward</span> <span m='1365850'>infinity</span> <span
  m='1366330'>search.</span> <span m='1367860'>So</span> <span m='1370230'>that</span>
  <span m='1370440'>is</span> <span m='1370760'>data</span> <span m='1370980'>structure</span>
  <span m='1371120'>three.</span> </p><p><span m='1373570'>And</span> <span m='1373670'>it's</span>
  <span m='1373790'>really</span> <span m='1374000'>easy.</span> <span m='1374450'>Once</span>
  <span m='1374780'>you</span> <span m='1374900'>have</span> <span m='1375560'>the</span>
  <span m='1375680'>ability</span> <span m='1376160'>to</span> <span m='1376310'>do</span>
  <span m='1376430'>a</span> <span m='1376520'>3D</span> <span m='1376850'>search--</span>
  <span m='1382500'>even</span> <span m='1382760'>if</span> <span m='1382880'>this</span>
  <span m='1383060'>one</span> <span m='1383330'>was</span> <span m='1383510'>minus</span>
  <span m='1383840'>infinity</span> <span m='1384660'>b1--</span> <span m='1385370'>if</span>
  <span m='1385520'>we</span> <span m='1385640'>just</span> <span m='1385940'>could</span>
  <span m='1386120'>do--</span> <span m='1387200'>would</span> <span m='1387350'>you</span>
  <span m='1387440'>call</span> <span m='1387620'>that--</span> <span m='1387770'>octants--</span>
  <span m='1388760'>octant</span> <span m='1389120'>search</span> <span m='1389540'>in</span>
  <span m='1389630'>3D,</span> <span m='1391250'>then</span> <span m='1391670'>we</span>
  <span m='1391880'>could</span> <span m='1392000'>just</span> <span m='1392180'>sit</span>
  <span m='1392390'>there</span> <span m='1392720'>and</span> <span m='1393050'>apply</span>
  <span m='1393380'>this</span> <span m='1393560'>transformation,</span> <span m='1394280'>and</span>
  <span m='1394370'>turn</span> <span m='1394670'>each</span> <span m='1394880'>one</span>
  <span m='1395090'>of</span> <span m='1395150'>them</span> <span m='1395900'>into</span>
  <span m='1396560'>double-sided,</span> <span m='1397850'>with</span> <span m='1398000'>a</span>
  <span m='1398060'>log</span> <span m='1398420'>n</span> <span m='1398690'>penalty</span>
  <span m='1399710'>each</span> <span m='1399890'>time</span> <span m='1400130'>in</span>
  <span m='1400280'>space,</span> <span m='1401330'>but</span> <span m='1401510'>no</span>
  <span m='1401720'>extra</span> <span m='1401990'>query</span> <span m='1402260'>time.</span>
  <span m='1402500'>We</span> <span m='1402620'>do</span> <span m='1403520'>a</span>
  <span m='1403550'>single</span> <span m='1404690'>log</span> <span m='1405110'>n</span>
  <span m='1405260'>traversal</span> <span m='1405830'>of</span> <span m='1405920'>this</span>
  <span m='1406100'>tree.</span> <span m='1407210'>So</span> <span m='1407450'>this</span>
  <span m='1407630'>part</span> <span m='1407950'>costs</span> <span m='1408760'>log</span>
  <span m='1409140'>n.</span> <span m='1413150'>And</span> <span m='1413330'>then</span>
  <span m='1413720'>we</span> <span m='1413870'>reduce</span> <span m='1414230'>to</span>
  <span m='1414350'>the</span> <span m='1414470'>previous</span> <span m='1415160'>problem--</span>
  <span m='1415935'>it's</span> <span m='1416410'>constant</span> <span m='1416840'>number</span>
  <span m='1417050'>of</span> <span m='1417140'>calls.</span> </p><p><span m='1418930'>So</span>
  <span m='1419090'>I</span> <span m='1419150'>could</span> <span m='1419360'>have</span>
  <span m='1419480'>written</span> <span m='1419690'>minus</span> <span m='1419990'>infinity</span>
  <span m='1420440'>here.</span> <span m='1420620'>But</span> <span m='1420740'>I</span>
  <span m='1420800'>pay</span> <span m='1420920'>an</span> <span m='1421010'>extra</span>
  <span m='1421280'>log</span> <span m='1421520'>factor</span> <span m='1421790'>in</span>
  <span m='1421880'>space.</span> <span m='1422270'>So</span> <span m='1423230'>this</span>
  <span m='1423410'>one</span> <span m='1423560'>we</span> <span m='1423650'>get</span>
  <span m='1423800'>for</span> <span m='1423920'>free,</span> <span m='1424280'>because</span>
  <span m='1424770'>we're using</span> <span m='1425150'>range</span> <span m='1425390'>trees.</span>
  <span m='1426650'>We</span> <span m='1426770'>do</span> <span m='1427040'>one</span>
  <span m='1427250'>transformation.</span> <span m='1428450'>We</span> <span m='1428570'>get</span>
  <span m='1428690'>this</span> <span m='1428870'>one.</span> <span m='1429350'>And</span>
  <span m='1429440'>now</span> <span m='1429620'>we're</span> <span m='1429710'>basically</span>
  <span m='1430040'>done,</span> <span m='1430300'>because</span> <span m='1430520'>we</span>
  <span m='1430670'>just</span> <span m='1430820'>do</span> <span m='1430940'>this</span>
  <span m='1431090'>again</span> <span m='1431890'>on</span> <span m='1432050'>the</span>
  <span m='1432110'>z-coordinate,</span> <span m='1435650'>and</span> <span m='1435830'>we</span>
  <span m='1435920'>get</span> <span m='1436420'>a1,</span> <span m='1437780'>b1,</span>
  <span m='1438650'>a2,</span> <span m='1439010'>b2,</span> <span m='1440060'>a3,</span>
  <span m='1440500'>b3,</span> <span m='1441380'>as</span> <span m='1441560'>desired.</span>
  <span m='1443860'>For our</span> <span m='1444030'>queries,</span> <span m='1449490'>just</span>
  <span m='1450120'>ditto</span> <span m='1453930'>on</span> <span m='1455190'>z,</span>
  <span m='1457890'>and</span> <span m='1458280'>using</span> <span m='1458670'>three</span>
  <span m='1459210'>in</span> <span m='1459330'>place</span> <span m='1459630'>of</span>
  <span m='1459780'>two.</span> </p><p><span m='1462050'>So</span> <span m='1462260'>we</span>
  <span m='1462380'>want</span> <span m='1462530'>to</span> <span m='1462620'>add</span>
  <span m='1462830'>in</span> <span m='1462920'>this</span> <span m='1463120'>a3.</span>
  <span m='1464000'>We</span> <span m='1464150'>build</span> <span m='1464360'>a</span>
  <span m='1464390'>three</span> <span m='1464660'>data</span> <span m='1464870'>structure.</span>
  <span m='1465320'>We</span> <span m='1465410'>build</span> <span m='1465590'>three</span>
  <span m='1465800'>prime</span> <span m='1466100'>data</span> <span m='1466310'>structures</span>
  <span m='1466750'>in</span> <span m='1466840'>exactly</span> <span m='1467210'>the</span>
  <span m='1467330'>same</span> <span m='1467570'>way.</span> <span m='1468400'>Three</span>
  <span m='1468620'>primes</span> <span m='1469040'>are</span> <span m='1469160'>on</span>
  <span m='1469400'>the</span> <span m='1469490'>left.</span> <span m='1469850'>Threes</span>
  <span m='1470300'>are</span> <span m='1470420'>on</span> <span m='1470600'>the</span>
  <span m='1470690'>right.</span> <span m='1472520'>Every</span> <span m='1473120'>node</span>
  <span m='1473720'>in</span> <span m='1473960'>this</span> <span m='1474590'>range</span>
  <span m='1474980'>tree</span> <span m='1475260'>on</span> <span m='1475430'>z.</span>
  <span m='1477200'>And</span> <span m='1477320'>we</span> <span m='1477410'>do</span>
  <span m='1477690'>a</span> <span m='1477770'>log</span> <span m='1478130'>n</span>
  <span m='1478250'>search</span> <span m='1478520'>at the</span> <span m='1478640'>beginning.</span>
  <span m='1479540'>Then</span> <span m='1479690'>we</span> <span m='1479750'>do</span>
  <span m='1479870'>a</span> <span m='1479900'>constant</span> <span m='1480440'>of</span>
  <span m='1480500'>calls to</span> <span m='1480780'>the</span> <span m='1480860'>data</span>
  <span m='1481070'>structure</span> <span m='1481430'>three.</span> <span m='1481760'>Data</span>
  <span m='1482150'>structure</span> <span m='1482270'>three</span> <span m='1482480'>does</span>
  <span m='1482660'>a</span> <span m='1482720'>log n</span> <span m='1482990'>search</span>
  <span m='1483230'>at</span> <span m='1483350'>the</span> <span m='1483470'>beginning--</span>
  <span m='1483755'>constant</span> <span m='1484040'>number</span> <span m='1484640'>of</span>
  <span m='1484700'>calls</span> <span m='1485000'>to</span> <span m='1485090'>data</span>
  <span m='1485300'>structure</span> <span m='1485660'>two.</span> </p><p><span m='1486260'>Data</span>
  <span m='1486560'>structure</span> <span m='1486770'>two</span> <span m='1488270'>does</span>
  <span m='1488540'>our</span> <span m='1488630'>usual</span> <span m='1488990'>range</span>
  <span m='1489440'>tree thing--</span> <span m='1489650'>identifies</span> <span
  m='1490280'>log</span> <span m='1490700'>n</span> <span m='1490880'>different</span>
  <span m='1491180'>calls</span> <span m='1491890'>to</span> <span m='1492020'>data</span>
  <span m='1492200'>structure</span> <span m='1492530'>one.</span> <span m='1493205'>Data</span>
  <span m='1493520'>structure</span> <span m='1493880'>one</span> <span m='1494090'>is</span>
  <span m='1494180'>a</span> <span m='1494240'>search</span> <span m='1494510'>and</span>
  <span m='1494600'>a</span> <span m='1494660'>list,</span> <span m='1495350'>plus</span>
  <span m='1495770'>every</span> <span m='1496070'>time</span> <span m='1496370'>I</span>
  <span m='1496460'>walk</span> <span m='1496730'>to</span> <span m='1496850'>the</span>
  <span m='1496940'>right</span> <span m='1497120'>and</span> <span m='1497750'>spend</span>
  <span m='1498020'>constant</span> <span m='1498350'>time,</span> <span m='1499040'>that</span>
  <span m='1499250'>is</span> <span m='1499370'>an</span> <span m='1499460'>element</span>
  <span m='1499790'>of</span> <span m='1499940'>my</span> <span m='1500120'>output.</span>
  <span m='1502190'>How</span> <span m='1502370'>much</span> <span m='1502550'>time</span>
  <span m='1502740'>has</span> <span m='1502830'>this</span> <span m='1503070'>taken</span>
  <span m='1503270'>total?</span> <span m='1504500'>Normally,</span> <span m='1505490'>there's</span>
  <span m='1505730'>log</span> <span m='1506090'>n</span> <span m='1506210'>of</span>
  <span m='1506300'>these,</span> <span m='1507140'>plus</span> <span m='1507330'>order
  of k.</span> <span m='1507700'>Normally,</span> <span m='1508010'>that</span> <span
  m='1508160'>would</span> <span m='1508250'>be</span> <span m='1508340'>log</span>
  <span m='1508620'>squared</span> <span m='1508940'>n</span> <span m='1509120'>plus</span>
  <span m='1509360'>k.</span> <span m='1509630'>But</span> <span m='1509780'>with</span>
  <span m='1509930'>fractional</span> <span m='1510290'>cascading--</span> <span m='1511760'>we</span>
  <span m='1511880'>have</span> <span m='1512000'>to</span> <span m='1512090'>check</span>
  <span m='1512390'>this</span> <span m='1512570'>is</span> <span m='1512900'>valid</span>
  <span m='1513410'>within</span> <span m='1513650'>fractional</span> <span m='1514040'>cascading.</span>
  <span m='1514520'>We've</span> <span m='1514610'>got</span> <span m='1514760'>a</span>
  <span m='1514820'>graph</span> <span m='1515270'>of</span> <span m='1515360'>data</span>
  <span m='1515600'>structures</span> <span m='1516050'>here,</span> <span m='1516830'>but</span>
  <span m='1517010'>each</span> <span m='1517220'>node</span> <span m='1517520'>has</span>
  <span m='1517760'>only</span> <span m='1517970'>constant</span> <span m='1518420'>degree.</span>
  </p><p><span m='1519290'>You</span> <span m='1519440'>can</span> <span m='1519650'>come</span>
  <span m='1519890'>from</span> <span m='1520040'>your</span> <span m='1520160'>parent.</span>
  <span m='1521340'>You</span> <span m='1521440'>can</span> <span m='1521540'>go</span>
  <span m='1521570'>to</span> <span m='1521630'>your</span> <span m='1521750'>left</span>
  <span m='1521960'>child.</span> <span m='1522440'>You</span> <span m='1522530'>can</span>
  <span m='1522620'>go</span> <span m='1522740'>to</span> <span m='1522830'>your</span>
  <span m='1522920'>right</span> <span m='1523100'>child.</span> <span m='1524210'>And</span>
  <span m='1524630'>you</span> <span m='1524780'>can</span> <span m='1524930'>go</span>
  <span m='1525140'>to</span> <span m='1527120'>previous</span> <span m='1527600'>dimension</span>
  <span m='1528020'>data</span> <span m='1528200'>structure,</span> <span m='1528650'>or</span>
  <span m='1528950'>the</span> <span m='1529370'>inverted</span> <span m='1529850'>version</span>
  <span m='1530210'>of</span> <span m='1530360'>it.</span> <span m='1530600'>So</span>
  <span m='1530790'>the</span> <span m='1530840'>degree</span> <span m='1531200'>five--</span>
  <span m='1532400'>if</span> <span m='1532460'>you</span> <span m='1532520'>count</span>
  <span m='1532760'>in</span> <span m='1532910'>and</span> <span m='1533000'>out</span>
  <span m='1533150'>degree.</span> <span m='1536030'>And</span> <span m='1536180'>so</span>
  <span m='1536720'>fractional</span> <span m='1537080'>cascading</span> <span m='1537530'>applies.</span>
  <span m='1537980'>We're</span> <span m='1538070'>always</span> <span m='1538310'>searching</span>
  <span m='1538700'>for</span> <span m='1538910'>the</span> <span m='1539030'>same</span>
  <span m='1539510'>thing--</span> <span m='1541400'>not</span> <span m='1541640'>quite,</span>
  <span m='1542120'>actually--</span> <span m='1542980'>a</span> <span m='1543220'>little</span>
  <span m='1543440'>bit</span> <span m='1543590'>of</span> <span m='1543680'>a</span>
  <span m='1543740'>cheat.</span> </p><p><span m='1544760'>Because</span> <span m='1545120'>of</span>
  <span m='1545210'>this</span> <span m='1545390'>inversion</span> <span m='1545900'>thing,</span>
  <span m='1547140'>we'll</span> <span m='1547370'>sometimes</span> <span m='1547850'>be</span>
  <span m='1548000'>searching</span> <span m='1548510'>for</span> <span m='1549230'>b3</span>
  <span m='1550550'>in</span> <span m='1550670'>the</span> <span m='1550760'>z</span>
  <span m='1550930'>list,</span> <span m='1551390'>but</span> <span m='1551570'>we'll</span>
  <span m='1551690'>also</span> <span m='1551990'>sometimes</span> <span m='1552320'>be</span>
  <span m='1552440'>searching</span> <span m='1552740'>for</span> <span m='1552890'>a3</span>
  <span m='1553760'>in</span> <span m='1553880'>the</span> <span m='1553940'>z</span>
  <span m='1554030'>list.</span> <span m='1554180'>But</span> <span m='1554390'>hey--</span>
  <span m='1555500'>just</span> <span m='1555710'>a</span> <span m='1555740'>factor</span>
  <span m='1556070'>of</span> <span m='1556160'>two.</span> <span m='1556980'>So</span>
  <span m='1557080'>we</span> <span m='1557180'>have</span> <span m='1557240'>two</span>
  <span m='1557510'>fractional</span> <span m='1557900'>cascading</span> <span m='1558320'>data</span>
  <span m='1558500'>structures--</span> <span m='1558860'>one</span> <span m='1559040'>for</span>
  <span m='1559160'>searching</span> <span m='1559520'>for</span> <span m='1559640'>b3,</span>
  <span m='1560570'>one</span> <span m='1560750'>for</span> <span m='1560870'>searching</span>
  <span m='1561200'>for</span> <span m='1561320'>a3.</span> <span m='1562105'>It's</span>
  <span m='1562380'>the</span> <span m='1562550'>inverted</span> <span m='1562940'>versions</span>
  <span m='1563510'>of</span> <span m='1563720'>one,</span> <span m='1564470'>and</span>
  <span m='1564590'>the</span> <span m='1564710'>uninverted</span> <span m='1565190'>versions</span>
  <span m='1565550'>of</span> <span m='1565670'>one--</span> <span m='1566580'>z-inverted.</span>
  </p><p><span m='1568400'>But</span> <span m='1568850'>that's</span> <span m='1569240'>fine.</span>
  <span m='1570050'>And</span> <span m='1570380'>in</span> <span m='1570440'>the</span>
  <span m='1570590'>end,</span> <span m='1570740'>we</span> <span m='1570860'>get</span>
  <span m='1571760'>log</span> <span m='1572120'>n</span> <span m='1572390'>to</span>
  <span m='1572570'>do</span> <span m='1573020'>the</span> <span m='1573110'>first</span>
  <span m='1573380'>search,</span> <span m='1574400'>and</span> <span m='1574520'>then</span>
  <span m='1574670'>plus</span> <span m='1575150'>the</span> <span m='1575330'>number</span>
  <span m='1575600'>of</span> <span m='1575690'>searches.</span> <span m='1576260'>Number</span>
  <span m='1576530'>of</span> <span m='1576620'>searches</span> <span m='1577250'>is</span>
  <span m='1577480'>log</span> <span m='1577800'>n</span> <span m='1578600'>plus</span>
  <span m='1579200'>k,</span> <span m='1579720'>where</span> <span m='1579870'>k</span>
  <span m='1580130'>is the</span> <span m='1580340'>size of the</span> <span m='1580430'>output.</span>
  <span m='1581520'>So</span> <span m='1581570'>total</span> <span m='1581900'>time</span>
  <span m='1589962'>is</span> <span m='1590440'>log</span> <span m='1590870'>n</span>
  <span m='1592190'>plus</span> <span m='1592440'>k.</span> <span m='1594000'>This</span>
  <span m='1594180'>is</span> <span m='1594270'>pretty</span> <span m='1594570'>amazing.</span>
  <span m='1596020'>We</span> <span m='1596160'>can</span> <span m='1596280'>do</span>
  <span m='1596370'>3D</span> <span m='1597480'>orthogonal</span> <span m='1597930'>range</span>
  <span m='1598170'>queries,</span> <span m='1599100'>still</span> <span m='1599580'>in</span>
  <span m='1599760'>log</span> <span m='1600090'>n.</span> </p><p><span m='1601170'>And</span>
  <span m='1601320'>if</span> <span m='1601440'>you</span> <span m='1601830'>go</span>
  <span m='1602040'>to</span> <span m='1602100'>higher</span> <span m='1602310'>dimensions,</span>
  <span m='1602850'>the</span> <span m='1602970'>best</span> <span m='1603240'>we</span>
  <span m='1603390'>know,</span> <span m='1603690'>basically,</span> <span m='1604140'>is</span>
  <span m='1604260'>to</span> <span m='1604440'>use</span> <span m='1604620'>range</span>
  <span m='1604890'>trees.</span> <span m='1605820'>And</span> <span m='1606120'>so</span>
  <span m='1606270'>you</span> <span m='1606450'>get,</span> <span m='1607280'>in</span>
  <span m='1607410'>general,</span> <span m='1607980'>log</span> <span m='1609990'>to</span>
  <span m='1610120'>the</span> <span m='1610260'>d</span> <span m='1610560'>minus</span>
  <span m='1610860'>two</span> <span m='1611570'>n</span> <span m='1612810'>plus</span>
  <span m='1613300'>k.</span> <span m='1613560'>So</span> <span m='1614280'>last</span>
  <span m='1614520'>class,</span> <span m='1614760'>we</span> <span m='1614820'>could</span>
  <span m='1614940'>do</span> <span m='1615060'>one.</span> <span m='1615780'>Now,</span>
  <span m='1615930'>we</span> <span m='1616290'>improved</span> <span m='1616650'>it</span>
  <span m='1616790'>by</span> <span m='1616980'>one</span> <span m='1617190'>more.</span>
  <span m='1620430'>Questions?</span> </p><p><span m='1625430'>AUDIENCE:</span> <span
  m='1625591'>Yeah,</span> <span m='1625752'>I</span> <span m='1625913'>have a quick</span>
  <span m='1626396'>question.</span> <span m='1627050'>[INAUDIBLE]</span> <span m='1627535'>question.</span>
  <span m='1631420'>So</span> <span m='1636200'>we do</span> <span m='1636690'>three,</span>
  <span m='1637180'>and then</span> <span m='1637670'>we do four.</span> <span m='1638160'>And</span>
  <span m='1638650'>it's not</span> <span m='1639140'>hard to imagine</span> <span
  m='1639630'>that</span> <span m='1640120'>same</span> <span m='1640610'>[INAUDIBLE],</span>
  <span m='1641100'>when</span> <span m='1641590'>you</span> <span m='1642080'>might</span>
  <span m='1642570'>try to</span> <span m='1642851'>do</span> <span m='1643120'>the</span>
  <span m='1643170'>same</span> <span m='1643220'>argument</span> <span m='1643610'>for</span>
  <span m='1643850'>step three,</span> <span m='1644240'>step four,</span> <span m='1644630'>step
  five.</span> </p><p><span m='1645410'>ERIK DEMAINE:</span> <span m='1645500'>Why</span>
  <span m='1645590'>can't</span> <span m='1645770'>we</span> <span m='1645860'>keep</span>
  <span m='1646130'>doing</span> <span m='1646490'>this</span> <span m='1646850'>for</span>
  <span m='1647270'>all</span> <span m='1647510'>dimensions?</span> <span m='1648840'>So</span>
  <span m='1649160'>what</span> <span m='1649450'>three</span> <span m='1649850'>is,</span>
  <span m='1650120'>and</span> <span m='1650210'>also</span> <span m='1650540'>four,</span>
  <span m='1651480'>is</span> <span m='1651860'>using</span> <span m='1652130'>the</span>
  <span m='1652190'>same</span> <span m='1652430'>transformation,</span> <span m='1653190'>which</span>
  <span m='1653270'>is,</span> <span m='1653480'>if</span> <span m='1653720'>I</span>
  <span m='1653840'>have</span> <span m='1654170'>a</span> <span m='1654230'>minus</span>
  <span m='1654620'>infinity</span> <span m='1655610'>something</span> <span m='1656660'>interval,</span>
  <span m='1657300'>I</span> <span m='1657400'>can</span> <span m='1657440'>transform</span>
  <span m='1657980'>it</span> <span m='1658070'>into</span> <span m='1658520'>an</span>
  <span m='1658670'>a2,</span> <span m='1659090'>b2</span> <span m='1659540'>interval.</span>
  <span m='1660410'>So</span> <span m='1660560'>I</span> <span m='1660620'>can</span>
  <span m='1660740'>make</span> <span m='1660950'>a</span> <span m='1661010'>one-sided</span>
  <span m='1661580'>interval</span> <span m='1661850'>into</span> <span m='1662060'>two-sided.</span>
  <span m='1663110'>The</span> <span m='1663200'>trouble</span> <span m='1663530'>is</span>
  <span m='1663620'>actually</span> <span m='1663920'>getting</span> <span m='1664280'>the</span>
  <span m='1664400'>one-sided</span> <span m='1664910'>interval.</span> </p><p><span
  m='1666020'>So</span> <span m='1666230'>we</span> <span m='1666350'>started,</span>
  <span m='1667010'>in</span> <span m='1667740'>one</span> <span m='1668010'>and</span>
  <span m='1668240'>two,</span> <span m='1669110'>just</span> <span m='1669350'>getting</span>
  <span m='1669650'>up</span> <span m='1669800'>to</span> <span m='1669920'>three</span>
  <span m='1670100'>dimensions.</span> <span m='1671300'>And</span> <span m='1671450'>that's</span>
  <span m='1671660'>where</span> <span m='1671840'>things</span> <span m='1672080'>are</span>
  <span m='1672170'>hard.</span> <span m='1673100'>So</span> <span m='1673250'>fine,</span>
  <span m='1673520'>in</span> <span m='1673610'>two</span> <span m='1673760'>dimensions,</span>
  <span m='1674240'>we</span> <span m='1674300'>can</span> <span m='1674420'>do</span>
  <span m='1674510'>all</span> <span m='1674660'>sorts</span> <span m='1674930'>of</span>
  <span m='1674990'>fancy</span> <span m='1675290'>tricks.</span> <span m='1675590'>We</span>
  <span m='1675710'>saw</span> <span m='1675890'>one</span> <span m='1676070'>way</span>
  <span m='1676190'>to</span> <span m='1676280'>do</span> <span m='1676400'>it</span>
  <span m='1676460'>last</span> <span m='1676730'>time.</span> <span m='1677390'>This</span>
  <span m='1677600'>is</span> <span m='1677720'>a</span> <span m='1677960'>particularly</span>
  <span m='1678600'>cute</span> <span m='1678860'>way</span> <span m='1679010'>to</span>
  <span m='1679100'>do</span> <span m='1679280'>it</span> <span m='1679450'>that</span>
  <span m='1679610'>lets</span> <span m='1679850'>you</span> <span m='1679940'>fractionally</span>
  <span m='1680360'>cascade.</span> <span m='1681650'>We</span> <span m='1681770'>could</span>
  <span m='1681910'>add</span> <span m='1682090'>a</span> <span m='1682160'>dimension.</span>
  </p><p><span m='1683400'>To</span> <span m='1683630'>add</span> <span m='1683800'>a</span>
  <span m='1683870'>dimension,</span> <span m='1684200'>we</span> <span m='1684310'>just</span>
  <span m='1684450'>use</span> <span m='1684620'>range</span> <span m='1684920'>trees.</span>
  <span m='1685190'>This</span> <span m='1685340'>is</span> <span m='1685460'>kind</span>
  <span m='1685610'>of</span> <span m='1685670'>pathetic.</span> <span m='1686540'>Every</span>
  <span m='1686780'>time</span> <span m='1687020'>we</span> <span m='1687110'>do</span>
  <span m='1687260'>this,</span> <span m='1687470'>we're</span> <span m='1687560'>going</span>
  <span m='1687630'>to</span> <span m='1687770'>pay</span> <span m='1687950'>a</span>
  <span m='1688010'>log</span> <span m='1688280'>n</span> <span m='1688400'>factor.</span>
  <span m='1689750'>So</span> <span m='1689930'>we</span> <span m='1690050'>could</span>
  <span m='1690200'>afford</span> <span m='1690590'>to</span> <span m='1690710'>do</span>
  <span m='1690950'>it</span> <span m='1691130'>once</span> <span m='1691610'>and</span>
  <span m='1691700'>get</span> <span m='1691880'>to</span> <span m='1692030'>3D.</span>
  <span m='1693740'>We</span> <span m='1693920'>paid</span> <span m='1694130'>a</span>
  <span m='1694220'>log</span> <span m='1694430'>n</span> <span m='1694520'>factor</span>
  <span m='1694850'>here,</span> <span m='1695040'>but</span> <span m='1695330'>we</span>
  <span m='1695480'>were</span> <span m='1695600'>lucky</span> <span m='1695960'>fractional</span>
  <span m='1696350'>cascading</span> <span m='1696830'>will</span> <span m='1696920'>remove</span>
  <span m='1697310'>one</span> <span m='1697610'>log</span> <span m='1697850'>factor,</span>
  <span m='1698150'>but</span> <span m='1698300'>only</span> <span m='1698630'>one.</span>
  </p><p><span m='1699530'>If</span> <span m='1699680'>we</span> <span m='1699740'>had</span>
  <span m='1699830'>to</span> <span m='1699890'>go</span> <span m='1700010'>to</span>
  <span m='1700100'>four</span> <span m='1700310'>dimensions,</span> <span m='1700820'>we'd</span>
  <span m='1700970'>have</span> <span m='1701120'>to</span> <span m='1701180'>use</span>
  <span m='1701330'>another</span> <span m='1701630'>level</span> <span m='1701930'>of</span>
  <span m='1701990'>range</span> <span m='1702310'>trees.</span> <span m='1703580'>And</span>
  <span m='1703760'>then</span> <span m='1703940'>we'd</span> <span m='1704090'>get</span>
  <span m='1704600'>a</span> <span m='1704660'>log</span> <span m='1704990'>squared</span>
  <span m='1705440'>searches.</span> <span m='1706950'>And</span> <span m='1707000'>then</span>
  <span m='1707810'>we</span> <span m='1707960'>have</span> <span m='1708110'>to</span>
  <span m='1708200'>pay</span> <span m='1709010'>unit</span> <span m='1709340'>cost</span>
  <span m='1709670'>for</span> <span m='1709790'>every</span> <span m='1710030'>search.</span>
  <span m='1711040'>So</span> <span m='1711200'>we'll</span> <span m='1711290'>get</span>
  <span m='1711440'>log</span> <span m='1711680'>squared</span> <span m='1711950'>for</span>
  <span m='1712160'>four</span> <span m='1712370'>dimensions.</span> <span m='1713340'>So</span>
  <span m='1713360'>it's</span> <span m='1713450'>just</span> <span m='1713630'>getting</span>
  <span m='1713960'>up</span> <span m='1714110'>to</span> <span m='1714200'>the</span>
  <span m='1714290'>right</span> <span m='1714440'>number</span> <span m='1714650'>of</span>
  <span m='1714710'>dimensions</span> <span m='1715180'>that's</span> <span m='1715310'>hard.</span>
  </p><p><span m='1716120'>What</span> <span m='1716360'>you're</span> <span m='1716540'>seeing</span>
  <span m='1716840'>here</span> <span m='1717080'>is</span> <span m='1717230'>that</span>
  <span m='1717530'>one-sided</span> <span m='1718100'>intervals</span> <span m='1718490'>are</span>
  <span m='1718580'>just</span> <span m='1718820'>the</span> <span m='1718910'>same</span>
  <span m='1719210'>as</span> <span m='1719330'>two-sided</span> <span m='1719450'>intervals,</span>
  <span m='1720830'>if</span> <span m='1720980'>you</span> <span m='1721040'>don't</span>
  <span m='1721220'>mind</span> <span m='1721400'>extra</span> <span m='1721610'>space.</span>
  <span m='1721940'>The</span> <span m='1722110'>space</span> <span m='1722540'>here</span>
  <span m='1723260'>is,</span> <span m='1723530'>I</span> <span m='1723620'>think,</span>
  <span m='1723950'>log</span> <span m='1724340'>cubed</span> <span m='1728470'>n</span>
  <span m='1728760'>log</span> <span m='1729050'>cubed</span> <span m='1729500'>n.</span>
  <span m='1732680'>Data</span> <span m='1733040'>structure</span> <span m='1733370'>one</span>
  <span m='1733700'>is</span> <span m='1733850'>linear</span> <span m='1734150'>space,</span>
  <span m='1734480'>but</span> <span m='1734600'>every</span> <span m='1734900'>other</span>
  <span m='1735230'>level,</span> <span m='1736110'>we</span> <span m='1736330'>lost</span>
  <span m='1736670'>a</span> <span m='1736730'>log</span> <span m='1736970'>factor.</span>
  <span m='1738410'>So</span> <span m='1738620'>one</span> <span m='1738800'>of</span>
  <span m='1738860'>those</span> <span m='1739070'>was</span> <span m='1739190'>to</span>
  <span m='1739280'>get</span> <span m='1739430'>up</span> <span m='1739580'>a</span>
  <span m='1739610'>dimension</span> <span m='1740120'>by</span> <span m='1740300'>range</span>
  <span m='1740570'>trees.</span> <span m='1740840'>The</span> <span m='1740960'>other</span>
  <span m='1741140'>two</span> <span m='1741500'>were</span> <span m='1741680'>to</span>
  <span m='1742100'>convert</span> <span m='1742550'>the</span> <span m='1742670'>one-sided</span>
  <span m='1743090'>intervals</span> <span m='1743450'>into</span> <span m='1743630'>two-sided</span>
  <span m='1744050'>intervals.</span> </p><p><span m='1745100'>And</span> <span m='1745220'>that</span>
  <span m='1745430'>generalizes.</span> <span m='1746090'>You</span> <span m='1746210'>could</span>
  <span m='1746330'>do</span> <span m='1746420'>that</span> <span m='1746570'>as</span>
  <span m='1746720'>many</span> <span m='1746930'>times</span> <span m='1747200'>as</span>
  <span m='1747290'>you</span> <span m='1747380'>want.</span> <span m='1748160'>The</span>
  <span m='1748250'>hard</span> <span m='1748460'>part</span> <span m='1748670'>is</span>
  <span m='1748790'>just</span> <span m='1748970'>getting</span> <span m='1749750'>the</span>
  <span m='1749870'>right</span> <span m='1750080'>number</span> <span m='1750500'>of</span>
  <span m='1750590'>intervals</span> <span m='1751670'>in</span> <span m='1751760'>the</span>
  <span m='1751850'>first</span> <span m='1752060'>place.</span> <span m='1752410'>And</span>
  <span m='1752510'>that's</span> <span m='1752570'>where</span> <span m='1752680'>we</span>
  <span m='1752780'>pay</span> <span m='1752960'>log</span> <span m='1753290'>per</span>
  <span m='1753500'>dimension.</span> <span m='1754830'>So</span> <span m='1754990'>kind</span>
  <span m='1755210'>of</span> <span m='1755270'>annoying</span> <span m='1755610'>you</span>
  <span m='1755690'>can't</span> <span m='1756350'>do</span> <span m='1756470'>log</span>
  <span m='1756920'>n</span> <span m='1757040'>for any</span> <span m='1757190'>dimension,</span>
  <span m='1757730'>but--</span> <span m='1758720'>pretty</span> <span m='1758930'>sure</span>
  <span m='1759080'>that's</span> <span m='1759320'>impossible.</span> <span m='1764250'>There</span>
  <span m='1764400'>are</span> <span m='1764470'>models</span> <span m='1764920'>under</span>
  <span m='1765130'>which</span> <span m='1765280'>it's</span> <span m='1765440'>impossible,</span>
  <span m='1766090'>but</span> <span m='1767110'>we're</span> <span m='1767200'>not</span>
  <span m='1767320'>going</span> <span m='1767440'>to</span> <span m='1767500'>get</span>
  <span m='1767590'>into</span> <span m='1767800'>that.</span> <span m='1768010'>Yeah?</span>
  </p><p><span m='1768696'>AUDIENCE:</span> <span m='1768934'>So</span> <span m='1769172'>when</span>
  <span m='1769648'>our</span> <span m='1770124'>query is</span> <span m='1770600'>log
  n</span> <span m='1771076'>plus k,</span> <span m='1771552'>k</span> <span m='1772028'>is
  actually</span> <span m='1772504'>the</span> <span m='1772980'>number of</span>
  <span m='1773932'>points</span> <span m='1774408'>that are</span> <span m='1774884'>coming
  back,</span> <span m='1775360'>because--</span> </p><p><span m='1777740'>ERIK DEMAINE:</span>
  <span m='1777965'>Yeah.</span> <span m='1778190'>Good</span> <span m='1778370'>question.</span>
  <span m='1779710'>Here,</span> <span m='1780110'>k</span> <span m='1780500'>has</span>
  <span m='1780860'>to</span> <span m='1780980'>be--</span> <span m='1781700'>this</span>
  <span m='1781880'>is</span> <span m='1781970'>for</span> <span m='1782150'>what</span>
  <span m='1782270'>we</span> <span m='1782390'>call</span> <span m='1782630'>range</span>
  <span m='1782900'>reporting,</span> <span m='1784940'>where</span> <span m='1785090'>you</span>
  <span m='1785240'>really</span> <span m='1785510'>want</span> <span m='1785660'>to</span>
  <span m='1785720'>list</span> <span m='1786110'>everybody</span> <span m='1786680'>in</span>
  <span m='1786800'>there.</span> <span m='1789560'>And</span> <span m='1790560'>if</span>
  <span m='1791030'>we</span> <span m='1791120'>wanted</span> <span m='1791360'>to</span>
  <span m='1791470'>do range</span> <span m='1791870'>counting</span> <span m='1792530'>queries,</span>
  <span m='1793070'>which</span> <span m='1793310'>just</span> <span m='1793520'>give</span>
  <span m='1793670'>me</span> <span m='1793790'>the</span> <span m='1793910'>number</span>
  <span m='1794210'>of</span> <span m='1794300'>elements</span> <span m='1794750'>that</span>
  <span m='1794900'>match,</span> <span m='1797090'>I</span> <span m='1797120'>don't</span>
  <span m='1797360'>think</span> <span m='1797570'>this</span> <span m='1797750'>will</span>
  <span m='1797870'>work.</span> <span m='1799310'>In</span> <span m='1799460'>particular,</span>
  <span m='1800180'>our</span> <span m='1800360'>seed</span> <span m='1800810'>data</span>
  <span m='1801080'>structure</span> <span m='1801440'>up</span> <span m='1801590'>here</span>
  <span m='1803240'>had</span> <span m='1803540'>to</span> <span m='1803630'>pay</span>
  <span m='1803960'>for</span> <span m='1804110'>everything.</span> <span m='1804980'>It</span>
  <span m='1805100'>doesn't</span> <span m='1805370'>know</span> <span m='1805610'>how</span>
  <span m='1805790'>many</span> <span m='1806030'>times</span> <span m='1806300'>it's</span>
  <span m='1806390'>going</span> <span m='1806510'>to</span> <span m='1806570'>have</span>
  <span m='1806720'>to</span> <span m='1806840'>walk</span> <span m='1807020'>to</span>
  <span m='1807110'>the</span> <span m='1807230'>right.</span> <span m='1807710'>It's
  got to</span> <span m='1807770'>actually</span> <span m='1808100'>do</span> <span
  m='1808280'>it.</span> <span m='1809360'>So</span> <span m='1809630'>range</span>
  <span m='1809930'>counting--</span> <span m='1811220'>not</span> <span m='1811400'>so</span>
  <span m='1811550'>much.</span> </p><p><span m='1812320'>Our</span> <span m='1812450'>previous</span>
  <span m='1812780'>data</span> <span m='1812960'>structures</span> <span m='1813320'>could</span>
  <span m='1813440'>do</span> <span m='1813530'>range</span> <span m='1813770'>counting,</span>
  <span m='1815330'>without</span> <span m='1815660'>the</span> <span m='1815780'>plus</span>
  <span m='1816020'>k,</span> <span m='1817820'>just</span> <span m='1818030'>paying</span>
  <span m='1818360'>log</span> <span m='1818680'>to the d</span> <span m='1818780'>minus</span>
  <span m='1819220'>one.</span> <span m='1820550'>But</span> <span m='1820820'>this</span>
  <span m='1821030'>is</span> <span m='1821150'>just</span> <span m='1821390'>for</span>
  <span m='1821510'>range</span> <span m='1821750'>reporting.</span> <span m='1822320'>Good</span>
  <span m='1822440'>question.</span> <span m='1824810'>I</span> <span m='1824890'>don't</span>
  <span m='1825100'>think</span> <span m='1825340'>anyone</span> <span m='1825670'>knows</span>
  <span m='1825820'>how</span> <span m='1825940'>to</span> <span m='1826030'>do</span>
  <span m='1826110'>range</span> <span m='1826390'>counting</span> <span m='1826750'>faster.</span>
  </p><p><span m='1828160'>AUDIENCE:</span> <span m='1828325'>And</span> <span m='1828490'>the</span>
  <span m='1828655'>reason we're</span> <span m='1829150'>only hitting</span> <span
  m='1829645'>points</span> <span m='1830635'>we know about</span> <span m='1831130'>is</span>
  <span m='1831625'>because</span> <span m='1832120'>the</span> <span m='1832615'>one
  data structure</span> <span m='1833110'>is on the</span> <span m='1833605'>bottom,</span>
  <span m='1834100'>so we never</span> <span m='1834595'>actually--</span> </p><p><span
  m='1835600'>ERIK DEMAINE:</span> <span m='1835690'>Right.</span> <span m='1835780'>So</span>
  <span m='1835900'>you</span> <span m='1836290'>need</span> <span m='1836470'>to</span>
  <span m='1836590'>check,</span> <span m='1838000'>why</span> <span m='1838270'>is</span>
  <span m='1838390'>it</span> <span m='1838540'>only</span> <span m='1838930'>order</span>
  <span m='1839260'>k,</span> <span m='1840160'>where</span> <span m='1840430'>k is</span>
  <span m='1840520'>the</span> <span m='1840610'>actual</span> <span m='1841030'>output</span>
  <span m='1841360'>size?</span> <span m='1842230'>Because</span> <span m='1842560'>by</span>
  <span m='1842770'>the</span> <span m='1842890'>time</span> <span m='1843130'>we</span>
  <span m='1843220'>get</span> <span m='1843370'>down</span> <span m='1843610'>to</span>
  <span m='1843730'>the</span> <span m='1843940'>one</span> <span m='1844180'>data</span>
  <span m='1844420'>structural</span> <span m='1844780'>level,</span> <span m='1845500'>we're</span>
  <span m='1845650'>guaranteed</span> <span m='1846560'>that</span> <span m='1846730'>x</span>
  <span m='1847120'>already</span> <span m='1847480'>matches.</span> <span m='1848110'>It's</span>
  <span m='1848230'>already</span> <span m='1848560'>in</span> <span m='1848740'>our</span>
  <span m='1848860'>interval</span> <span m='1849280'>a1,</span> <span m='1849390'>b1</span>
  <span m='1850060'>by</span> <span m='1850210'>the</span> <span m='1850330'>range</span>
  <span m='1850600'>tree.</span> <span m='1851740'>And</span> <span m='1852190'>we're</span>
  <span m='1852400'>guaranteed</span> <span m='1853150'>that</span> <span m='1853390'>these</span>
  <span m='1853690'>two</span> <span m='1854320'>open</span> <span m='1854650'>intervals--</span>
  <span m='1856720'>the</span> <span m='1856840'>minus</span> <span m='1857140'>infinity</span>
  <span m='1857710'>actually</span> <span m='1858340'>is</span> <span m='1858790'>a2</span>
  <span m='1858970'>here,</span> <span m='1859510'>and</span> <span m='1859600'>it</span>
  <span m='1859690'>actually</span> <span m='1860170'>is</span> <span m='1860350'>a3</span>
  <span m='1860800'>here,</span> <span m='1862420'>or,</span> <span m='1862660'>actually,</span>
  <span m='1862960'>something</span> <span m='1863320'>bigger</span> <span m='1863590'>than</span>
  <span m='1863790'>it.</span> </p><p><span m='1863920'>So</span> <span m='1864040'>we're</span>
  <span m='1864130'>guaranteed</span> <span m='1864640'>whatever</span> <span m='1865000'>this</span>
  <span m='1865180'>thing</span> <span m='1865360'>outputs</span> <span m='1866170'>is</span>
  <span m='1866370'>a</span> <span m='1866490'>result.</span> <span m='1867430'>And</span>
  <span m='1867610'>we're</span> <span m='1867700'>never</span> <span m='1867970'>doing</span>
  <span m='1868270'>overlapping</span> <span m='1868840'>intervals.</span> <span m='1869240'>So</span>
  <span m='1869290'>we</span> <span m='1869350'>never</span> <span m='1869560'>double</span>
  <span m='1869860'>charge.</span> <span m='1871200'>Yeah.</span> <span m='1871660'>You</span>
  <span m='1871750'>do</span> <span m='1871870'>need</span> <span m='1872020'>to</span>
  <span m='1872110'>check</span> <span m='1872350'>that.</span> <span m='1873090'>There's</span>
  <span m='1873250'>a</span> <span m='1873310'>lot</span> <span m='1873550'>of</span>
  <span m='1873880'>pointers</span> <span m='1874270'>to</span> <span m='1874360'>follow</span>
  <span m='1874660'>here,</span> <span m='1875680'>but</span> <span m='1875860'>it</span>
  <span m='1875980'>works.</span> </p><p><span m='1878790'>All</span> <span m='1878900'>right.</span>
  <span m='1879270'>You</span> <span m='1879360'>look</span> <span m='1879530'>convinced.</span>
  <span m='1880610'>Let's</span> <span m='1880850'>move</span> <span m='1881090'>on</span>
  <span m='1882110'>to</span> <span m='1883040'>kinetic</span> <span m='1883520'>data</span>
  <span m='1883730'>structures.</span> </p><p><span m='1914010'>The</span> <span m='1914070'>idea</span>
  <span m='1914340'>with</span> <span m='1914400'>kinetic</span> <span m='1914655'>data</span>
  <span m='1914910'>structures</span> <span m='1915440'>is,</span> <span m='1915690'>you</span>
  <span m='1915810'>have</span> <span m='1916110'>moving</span> <span m='1916470'>data.</span>
  <span m='1918170'>Deal</span> <span m='1918380'>with</span> <span m='1918590'>it.</span>
  <span m='1919460'>So</span> <span m='1919610'>normally,</span> <span m='1920570'>we're</span>
  <span m='1920690'>thinking</span> <span m='1920990'>of</span> <span m='1921080'>data</span>
  <span m='1921550'>that--</span> <span m='1922040'>at</span> <span m='1922220'>best,</span>
  <span m='1922580'>it's</span> <span m='1922760'>dynamic</span> <span m='1923360'>data,</span>
  <span m='1923630'>meaning</span> <span m='1923960'>we</span> <span m='1924080'>can</span>
  <span m='1924230'>delete</span> <span m='1924620'>something</span> <span m='1925040'>and</span>
  <span m='1925130'>then</span> <span m='1925250'>reinsert</span> <span m='1925850'>it.</span>
  <span m='1926360'>But</span> <span m='1926480'>what</span> <span m='1926660'>if</span>
  <span m='1926810'>everything</span> <span m='1927320'>is</span> <span m='1927440'>constantly</span>
  <span m='1928190'>changing?</span> </p><p><span m='1929450'>So</span> <span m='1929630'>normally,</span>
  <span m='1930100'>OK,</span> <span m='1930500'>I've</span> <span m='1930590'>got</span>
  <span m='1930830'>some</span> <span m='1931010'>points</span> <span m='1931370'>in</span>
  <span m='1931460'>my</span> <span m='1931580'>data</span> <span m='1931820'>structure.</span>
  <span m='1932120'>But</span> <span m='1932270'>now,</span> <span m='1932510'>what</span>
  <span m='1932660'>if</span> <span m='1932780'>they</span> <span m='1932930'>also</span>
  <span m='1933230'>have</span> <span m='1933380'>velocities?</span> <span m='1935780'>And</span>
  <span m='1936890'>maybe</span> <span m='1937190'>some</span> <span m='1937400'>guy's</span>
  <span m='1937640'>just</span> <span m='1937850'>sitting</span> <span m='1938150'>there</span>
  <span m='1938330'>stationary,</span> <span m='1939020'>but</span> <span m='1939140'>some</span>
  <span m='1939320'>of</span> <span m='1939380'>them</span> <span m='1939530'>are</span>
  <span m='1939590'>moving</span> <span m='1939950'>relative</span> <span m='1940340'>to</span>
  <span m='1940520'>it.</span> <span m='1941480'>And</span> <span m='1942610'>my</span>
  <span m='1942830'>operations--</span> <span m='1943490'>this is</span> <span m='1943640'>kind</span>
  <span m='1943910'>of</span> <span m='1943970'>like</span> <span m='1944180'>time</span>
  <span m='1944420'>travel,</span> <span m='1944720'>but</span> <span m='1944840'>now</span>
  <span m='1945020'>we're</span> <span m='1945080'>going</span> <span m='1945200'>to</span>
  <span m='1945260'>time</span> <span m='1945530'>travel</span> <span m='1945830'>into</span>
  <span m='1946070'>the</span> <span m='1946220'>future,</span> <span m='1947390'>which</span>
  <span m='1947540'>we</span> <span m='1947630'>do</span> <span m='1947750'>all</span>
  <span m='1947870'>the</span> <span m='1947990'>time.</span> <span m='1948770'>But</span>
  <span m='1948890'>we'd</span> <span m='1949060'>like</span> <span m='1949310'>to</span>
  <span m='1949400'>do</span> <span m='1949550'>it</span> <span m='1949640'>really</span>
  <span m='1949940'>quickly,</span> <span m='1951860'>and</span> <span m='1951980'>say,</span>
  <span m='1952960'>OK,</span> <span m='1954290'>advanced</span> <span m='1954950'>time</span>
  <span m='1955370'>by</span> <span m='1955670'>five</span> <span m='1955970'>units.</span>
  <span m='1957350'>And</span> <span m='1957500'>now,</span> <span m='1958610'>in</span>
  <span m='1958760'>that</span> <span m='1959180'>frame,</span> <span m='1960490'>do</span>
  <span m='1960680'>an</span> <span m='1960770'>orthogonal</span> <span m='1961280'>range</span>
  <span m='1961550'>query</span> <span m='1961880'>or</span> <span m='1961940'>something.</span>
  <span m='1962750'>Do</span> <span m='1962870'>some</span> <span m='1963050'>kind</span>
  <span m='1963170'>of</span> <span m='1963260'>query.</span> </p><p><span m='1964160'>We're</span>
  <span m='1964280'>always</span> <span m='1964520'>going</span> <span m='1964670'>to</span>
  <span m='1964760'>be</span> <span m='1964880'>doing</span> <span m='1965600'>queries</span>
  <span m='1965960'>in</span> <span m='1966110'>the</span> <span m='1966200'>present.</span>
  <span m='1967700'>So</span> <span m='1967880'>this</span> <span m='1968090'>is</span>
  <span m='1969590'>not</span> <span m='1969770'>fancy</span> <span m='1970100'>time</span>
  <span m='1970340'>travel.</span> <span m='1970640'>This</span> <span m='1970740'>is</span>
  <span m='1970860'>regular,</span> <span m='1971270'>forward</span> <span m='1971600'>time</span>
  <span m='1971840'>travel.</span> <span m='1972170'>We</span> <span m='1972290'>just</span>
  <span m='1972410'>want</span> <span m='1972560'>to</span> <span m='1972710'>quickly</span>
  <span m='1973190'>say,</span> <span m='1973910'>jump</span> <span m='1974150'>forward</span>
  <span m='1974600'>10</span> <span m='1974840'>time</span> <span m='1975080'>units,</span>
  <span m='1976070'>do</span> <span m='1976190'>some</span> <span m='1976370'>queries,</span>
  <span m='1976730'>jump</span> <span m='1976970'>forward</span> <span m='1977360'>some</span>
  <span m='1977540'>other</span> <span m='1977720'>time</span> <span m='1977960'>units.</span>
  </p><p><span m='1979220'>There's</span> <span m='1979610'>actually</span> <span
  m='1979940'>another</span> <span m='1980210'>operation,</span> <span m='1980660'>which</span>
  <span m='1980840'>is,</span> <span m='1980990'>ah,</span> <span m='1981440'>this</span>
  <span m='1981620'>point</span> <span m='1981770'>is</span> <span m='1981860'>no</span>
  <span m='1981980'>longer</span> <span m='1982190'>moving</span> <span m='1982430'>in</span>
  <span m='1982490'>that</span> <span m='1982640'>direction.</span> <span m='1983070'>Now,</span>
  <span m='1983150'>it's</span> <span m='1983270'>moving</span> <span m='1983510'>in</span>
  <span m='1983600'>this</span> <span m='1983750'>direction.</span> <span m='1985320'>So</span>
  <span m='1985640'>the</span> <span m='1985850'>operations</span> <span m='1992600'>are,</span>
  <span m='1992840'>advance</span> <span m='1996350'>to</span> <span m='1996590'>time</span>
  <span m='1996950'>t--</span> <span m='1998780'>so</span> <span m='1998960'>this</span>
  <span m='1999140'>is</span> <span m='1999260'>like</span> <span m='1999410'>setting</span>
  <span m='1999870'>now</span> <span m='2000570'>equal</span> <span m='2000920'>to</span>
  <span m='2001090'>t--</span> <span m='2002650'>and</span> <span m='2002980'>change</span>
  <span m='2006110'>a</span> <span m='2006280'>point</span> <span m='2006650'>x</span>
  <span m='2008110'>to</span> <span m='2008500'>have</span> <span m='2008950'>some</span>
  <span m='2009460'>new</span> <span m='2009840'>f</span> <span m='2010110'>of</span>
  <span m='2010220'>t</span> <span m='2010990'>trajectory.</span> </p><p><span m='2012574'>AUDIENCE:</span>
  <span m='2012685'>I</span> <span m='2012796'>thought</span> <span m='2012907'>it</span>
  <span m='2013021'>was supposed to be</span> <span m='2013468'>arbitrary.</span>
  </p><p><span m='2015710'>ERIK DEMAINE:</span> <span m='2015885'>Well,</span> <span
  m='2016950'>arbitrary</span> <span m='2017440'>trajectory</span> <span m='2017930'>is</span>
  <span m='2018100'>not--</span> <span m='2018400'>not</span> <span m='2018700'>quite.</span>
  <span m='2019800'>I'm</span> <span m='2019940'>going</span> <span m='2020060'>to</span>
  <span m='2020170'>restrict</span> <span m='2020560'>what</span> <span m='2020740'>those</span>
  <span m='2020950'>trajectories</span> <span m='2021460'>are.</span> <span m='2022060'>But</span>
  <span m='2022180'>that</span> <span m='2022360'>is</span> <span m='2022510'>the</span>
  <span m='2022630'>remaining</span> <span m='2022960'>question.</span> <span m='2024970'>What</span>
  <span m='2025150'>kind</span> <span m='2025330'>of</span> <span m='2025420'>f of</span>
  <span m='2025675'>t's</span> <span m='2025930'>do</span> <span m='2026020'>we</span>
  <span m='2026140'>allow?</span> </p><p><span m='2030420'>I'm</span> <span m='2030540'>drawing</span>
  <span m='2030780'>the</span> <span m='2030870'>picture</span> <span m='2031260'>in</span>
  <span m='2031950'>d</span> <span m='2032100'>dimensions,</span> <span m='2032790'>let's</span>
  <span m='2032970'>say.</span> <span m='2033780'>And</span> <span m='2034020'>most</span>
  <span m='2034290'>of</span> <span m='2034350'>the</span> <span m='2034440'>work
  in</span> <span m='2034770'>kinetic</span> <span m='2035190'>structures</span> <span
  m='2035670'>in</span> <span m='2036100'>2D--</span> <span m='2036540'>a</span> <span
  m='2036570'>little</span> <span m='2036810'>bit</span> <span m='2036900'>in</span>
  <span m='2036960'>3D--</span> <span m='2038460'>but</span> <span m='2038700'>I'm</span>
  <span m='2038790'>going</span> <span m='2038910'>to</span> <span m='2038970'>focus</span>
  <span m='2039270'>today</span> <span m='2039480'>mostly</span> <span m='2039780'>on</span>
  <span m='2039930'>1D.</span> <span m='2040500'>Because</span> <span m='2040770'>it's</span>
  <span m='2041010'>easy</span> <span m='2041280'>to</span> <span m='2041370'>analyze,</span>
  <span m='2041880'>clean.</span> <span m='2043110'>There's</span> <span m='2043350'>a</span>
  <span m='2043410'>lot</span> <span m='2043560'>of</span> <span m='2043680'>open</span>
  <span m='2043890'>questions</span> <span m='2044310'>in</span> <span m='2044430'>2D.</span>
  <span m='2046410'>So</span> <span m='2047040'>we</span> <span m='2047220'>can</span>
  <span m='2047370'>also</span> <span m='2047580'>think</span> <span m='2047790'>of</span>
  <span m='2047880'>these--</span> <span m='2048239'>there's</span> <span m='2048540'>points</span>
  <span m='2048840'>on</span> <span m='2048929'>a</span> <span m='2049020'>line.</span>
  <span m='2049739'>They</span> <span m='2049860'>have</span> <span m='2050070'>velocities,</span>
  <span m='2051449'>accelerations,</span> <span m='2052860'>who</span> <span m='2053010'>knows</span>
  <span m='2053310'>what.</span> <span m='2054030'>That</span> <span m='2054239'>would</span>
  <span m='2054389'>be--</span> <span m='2058650'>OK,</span> <span m='2058920'>let's</span>
  <span m='2059040'>say--</span> <span m='2059909'>models</span> <span m='2063600'>of</span>
  <span m='2063840'>trajectories.</span> </p><p><span m='2071429'>The</span> <span
  m='2071520'>simplest</span> <span m='2071909'>one</span> <span m='2072120'>that</span>
  <span m='2072239'>would</span> <span m='2072360'>be</span> <span m='2072540'>affine--</span>
  <span m='2075199'>f</span> <span m='2075579'>of t</span> <span m='2075960'>equals</span>
  <span m='2076590'>a</span> <span m='2076889'>plus</span> <span m='2077580'>bt.</span>
  <span m='2078706'>a</span> <span m='2079110'>and</span> <span m='2079409'>b</span>
  <span m='2079590'>here</span> <span m='2079889'>would</span> <span m='2080040'>be</span>
  <span m='2080190'>points.</span> <span m='2080444'>a</span> <span m='2080699'>and</span>
  <span m='2080850'>d</span> <span m='2080940'>dimensions</span> <span m='2081480'>are</span>
  <span m='2081630'>just</span> <span m='2081960'>values</span> <span m='2082679'>in</span>
  <span m='2082889'>one</span> <span m='2083070'>dimension.</span> <span m='2086469'>So</span>
  <span m='2086969'>the</span> <span m='2087060'>motivation</span> <span m='2087540'>is,</span>
  <span m='2087750'>maybe,</span> <span m='2088050'>you have</span> <span m='2088139'>cell</span>
  <span m='2088380'>phones</span> <span m='2089010'>or</span> <span m='2089370'>cars</span>
  <span m='2090030'>or</span> <span m='2090090'>something.</span> <span m='2091290'>You</span>
  <span m='2091469'>have</span> <span m='2091620'>some</span> <span m='2091770'>current</span>
  <span m='2092040'>estimates</span> <span m='2092520'>on</span> <span m='2092670'>which</span>
  <span m='2092850'>way</span> <span m='2092969'>they're</span> <span m='2093090'>going</span>
  <span m='2093449'>and</span> <span m='2093540'>at</span> <span m='2093630'>what</span>
  <span m='2093840'>speed.</span> <span m='2095580'>Then</span> <span m='2095790'>this</span>
  <span m='2096000'>would</span> <span m='2096090'>be</span> <span m='2096270'>the</span>
  <span m='2096690'>simple</span> <span m='2097050'>model.</span> </p><p><span m='2097500'>And</span>
  <span m='2098130'>if</span> <span m='2098280'>either</span> <span m='2098550'>those</span>
  <span m='2098760'>two</span> <span m='2098910'>things</span> <span m='2099150'>change,</span>
  <span m='2100630'>you</span> <span m='2100740'>have</span> <span m='2100890'>to</span>
  <span m='2100980'>do</span> <span m='2101100'>a</span> <span m='2101130'>change</span>
  <span m='2101580'>operation.</span> <span m='2102570'>So</span> <span m='2102720'>you</span>
  <span m='2102840'>pay</span> <span m='2103110'>for</span> <span m='2103290'>that</span>
  <span m='2103500'>every</span> <span m='2103680'>time</span> <span m='2103920'>they</span>
  <span m='2104520'>change</span> <span m='2104820'>their</span> <span m='2104910'>trajectory.</span>
  <span m='2106020'>But</span> <span m='2106230'>otherwise,</span> <span m='2106650'>it's</span>
  <span m='2106740'>going</span> <span m='2106860'>to</span> <span m='2106950'>be</span>
  <span m='2107040'>super</span> <span m='2107340'>efficient,</span> <span m='2107700'>because</span>
  <span m='2107910'>advance</span> <span m='2108195'>is</span> <span m='2108530'>going</span>
  <span m='2108660'>to</span> <span m='2108750'>be</span> <span m='2108960'>super</span>
  <span m='2109320'>fast.</span> <span m='2109890'>That's</span> <span m='2110100'>the</span>
  <span m='2110190'>plan.</span> </p><p><span m='2112350'>But</span> <span m='2112560'>maybe</span>
  <span m='2112890'>it's</span> <span m='2113040'>not</span> <span m='2113250'>just</span>
  <span m='2116010'>position</span> <span m='2116400'>and</span> <span m='2116490'>speed.</span>
  <span m='2117150'>Maybe</span> <span m='2117360'>also</span> <span m='2117560'>have</span>
  <span m='2117630'>acceleration</span> <span m='2119010'>and</span> <span m='2119730'>stuff.</span>
  <span m='2122880'>And</span> <span m='2123000'>then</span> <span m='2126900'>the</span>
  <span m='2127170'>extension</span> <span m='2127620'>of</span> <span m='2127710'>that</span>
  <span m='2127920'>would</span> <span m='2128050'>be</span> <span m='2128310'>bounded</span>
  <span m='2128730'>degree</span> <span m='2129030'>algebraic,</span> <span m='2134400'>which</span>
  <span m='2134640'>is,</span> <span m='2142410'>you</span> <span m='2142560'>have</span>
  <span m='2142710'>some</span> <span m='2142860'>polynomial</span> <span m='2143460'>of</span>
  <span m='2143580'>bounded</span> <span m='2143940'>degree--</span> <span m='2144450'>sorry,</span>
  <span m='2144725'>that should be</span> <span m='2145000'>c--</span> <span m='2147600'>but</span>
  <span m='2147930'>bounded.</span> <span m='2149610'>And</span> <span m='2150540'>the</span>
  <span m='2150690'>reason</span> <span m='2150990'>we</span> <span m='2151110'>care</span>
  <span m='2151260'>about</span> <span m='2151440'>bounded</span> <span m='2151890'>is</span>
  <span m='2152370'>really</span> <span m='2152580'>the</span> <span m='2152700'>following.</span>
  <span m='2153930'>There's</span> <span m='2154140'>an</span> <span m='2154230'>even</span>
  <span m='2154440'>more</span> <span m='2154590'>general</span> <span m='2154920'>model</span>
  <span m='2155250'>which</span> <span m='2155430'>we</span> <span m='2155550'>call</span>
  <span m='2156030'>pseudo</span> <span m='2156360'>algebraic.</span> </p><p><span
  m='2190760'>So</span> <span m='2190970'>we</span> <span m='2191510'>would</span>
  <span m='2191600'>like</span> <span m='2191810'>to</span> <span m='2191930'>bound</span>
  <span m='2192260'>the</span> <span m='2192350'>cost</span> <span m='2192740'>of</span>
  <span m='2192950'>this</span> <span m='2193130'>advance</span> <span m='2193520'>operation.</span>
  <span m='2194150'>What</span> <span m='2194300'>we'd</span> <span m='2194450'>like</span>
  <span m='2194720'>is</span> <span m='2194840'>that</span> <span m='2195050'>when</span>
  <span m='2195260'>we</span> <span m='2195350'>advance</span> <span m='2195740'>time</span>
  <span m='2196220'>a</span> <span m='2196280'>large</span> <span m='2196640'>amount,</span>
  <span m='2198500'>stuff</span> <span m='2198860'>doesn't</span> <span m='2199160'>change</span>
  <span m='2200870'>crazy</span> <span m='2201140'>number</span> <span m='2201350'>of</span>
  <span m='2201440'>times.</span> <span m='2201950'>And</span> <span m='2202100'>pseudo</span>
  <span m='2202370'>algebraic</span> <span m='2203000'>says</span> <span m='2203300'>that</span>
  <span m='2203420'>if</span> <span m='2203570'>you</span> <span m='2203630'>look</span>
  <span m='2203840'>at</span> <span m='2203930'>anything</span> <span m='2205250'>you</span>
  <span m='2205370'>care</span> <span m='2205610'>about--</span> <span m='2206000'>we
  call</span> <span m='2206170'>this</span> <span m='2206360'>a</span> <span m='2206420'>certificate</span>
  <span m='2207260'>of</span> <span m='2207470'>interest.</span> <span m='2208280'>We'll</span>
  <span m='2208370'>be</span> <span m='2208430'>talking</span> <span m='2208700'>a</span>
  <span m='2208760'>lot</span> <span m='2208910'>about</span> <span m='2209150'>certificates</span>
  <span m='2209810'>today.</span> </p><p><span m='2210860'>Certificate</span> <span
  m='2211340'>is</span> <span m='2211430'>something</span> <span m='2211700'>like,</span>
  <span m='2212180'>is</span> <span m='2212360'>this</span> <span m='2212510'>point</span>
  <span m='2212810'>left</span> <span m='2213080'>of</span> <span m='2213170'>that</span>
  <span m='2213350'>point.</span> <span m='2213950'>It's</span> <span m='2214100'>a</span>
  <span m='2214190'>Boolean</span> <span m='2214730'>question</span> <span m='2215210'>about</span>
  <span m='2215570'>the</span> <span m='2215690'>moving</span> <span m='2215990'>points.</span>
  <span m='2216630'>It's</span> <span m='2216740'>either</span> <span m='2216920'>true</span>
  <span m='2217220'>or</span> <span m='2217280'>false.</span> </p><p><span m='2219090'>And</span>
  <span m='2219110'>what</span> <span m='2219260'>I'd</span> <span m='2219380'>like</span>
  <span m='2219710'>is</span> <span m='2219920'>that--</span> <span m='2220890'>I</span>
  <span m='2221480'>have</span> <span m='2221630'>some</span> <span m='2221780'>point.</span>
  <span m='2222370'>It</span> <span m='2222530'>has</span> <span m='2222680'>some</span>
  <span m='2222890'>crazy</span> <span m='2223580'>trajectory.</span> <span m='2224660'>I</span>
  <span m='2224720'>have</span> <span m='2224870'>another</span> <span m='2225140'>point.</span>
  <span m='2225430'>It</span> <span m='2225500'>has</span> <span m='2225650'>some</span>
  <span m='2225830'>crazy</span> <span m='2226460'>trajectory.</span> <span m='2227570'>I</span>
  <span m='2227660'>don't</span> <span m='2227810'>want,</span> <span m='2228250'>is</span>
  <span m='2228470'>this</span> <span m='2228650'>point</span> <span m='2228920'>left</span>
  <span m='2229190'>of</span> <span m='2229250'>this</span> <span m='2229430'>point,</span>
  <span m='2229670'>to</span> <span m='2229790'>change</span> <span m='2230540'>an</span>
  <span m='2230690'>unbounded</span> <span m='2231140'>number</span> <span m='2231350'>of</span>
  <span m='2231440'>times.</span> <span m='2231830'>I'd</span> <span m='2231920'>like</span>
  <span m='2232100'>it</span> <span m='2232160'>to</span> <span m='2232280'>be</span>
  <span m='2232430'>constant,</span> <span m='2234320'>as</span> <span m='2234470'>long</span>
  <span m='2234800'>as</span> <span m='2234950'>no</span> <span m='2235160'>change</span>
  <span m='2235580'>operations</span> <span m='2236090'>are</span> <span m='2236180'>called.</span>
  </p><p><span m='2236510'>So</span> <span m='2236720'>for</span> <span m='2236870'>a</span>
  <span m='2236900'>single</span> <span m='2237320'>trajectory,</span> <span m='2238490'>I'd</span>
  <span m='2238640'>like</span> <span m='2238850'>these</span> <span m='2239150'>to</span>
  <span m='2239270'>flip</span> <span m='2239600'>a</span> <span m='2239660'>constant</span>
  <span m='2240410'>number</span> <span m='2240680'>of</span> <span m='2240770'>times.</span>
  <span m='2241070'>Now,</span> <span m='2241190'>if</span> <span m='2241280'>you're</span>
  <span m='2241490'>algebraic</span> <span m='2243040'>with</span> <span m='2243230'>bounded</span>
  <span m='2243530'>degree,</span> <span m='2243890'>then</span> <span m='2244040'>that</span>
  <span m='2244190'>will</span> <span m='2244310'>be</span> <span m='2244460'>the</span>
  <span m='2244550'>case.</span> <span m='2245990'>But</span> <span m='2246140'>more</span>
  <span m='2246320'>generally,</span> <span m='2247250'>as</span> <span m='2247340'>long</span>
  <span m='2247520'>as</span> <span m='2247610'>you</span> <span m='2247670'>sort</span>
  <span m='2247850'>of</span> <span m='2247940'>switch</span> <span m='2248600'>between</span>
  <span m='2248900'>left</span> <span m='2249140'>and</span> <span m='2249230'>right</span>
  <span m='2249650'>bounded</span> <span m='2249950'>number</span> <span m='2250130'>of</span>
  <span m='2250220'>times,</span> <span m='2250490'>then</span> <span m='2250670'>that</span>
  <span m='2250880'>particular</span> <span m='2251420'>certificate</span> <span m='2251960'>will</span>
  <span m='2252060'>only</span> <span m='2252250'>change</span> <span m='2253040'>unbounded</span>
  <span m='2253400'>number</span> <span m='2253640'>of</span> <span m='2253700'>times.</span>
  <span m='2254630'>But</span> <span m='2254750'>in</span> <span m='2254840'>general,</span>
  <span m='2255140'>anything</span> <span m='2255740'>where</span> <span m='2256610'>all</span>
  <span m='2256790'>the</span> <span m='2256850'>certificates</span> <span m='2257390'>I</span>
  <span m='2257480'>care</span> <span m='2257660'>about</span> <span m='2257900'>change</span>
  <span m='2258160'>a constant</span> <span m='2258310'>number</span> <span m='2258570'>of</span>
  <span m='2258670'>times</span> <span m='2259370'>is</span> <span m='2259520'>just</span>
  <span m='2259790'>as</span> <span m='2259910'>good</span> <span m='2260060'>as</span>
  <span m='2260180'>algebraic.</span> </p><p><span m='2260690'>This</span> <span m='2260870'>is</span>
  <span m='2260960'>really</span> <span m='2261200'>why</span> <span m='2261380'>we</span>
  <span m='2261500'>like</span> <span m='2262220'>this.</span> <span m='2262910'>I
  think</span> <span m='2263030'>I've</span> <span m='2263210'>talked</span> <span
  m='2263420'>enough</span> <span m='2263690'>about</span> <span m='2264440'>trajectory</span>
  <span m='2264890'>models.</span> <span m='2265190'>So it's</span> <span m='2265310'>not</span>
  <span m='2265550'>totally</span> <span m='2265910'>generic.</span> <span m='2266930'>But</span>
  <span m='2267110'>it</span> <span m='2267200'>covers</span> <span m='2267710'>a</span>
  <span m='2267740'>lot</span> <span m='2268160'>of</span> <span m='2268220'>things</span>
  <span m='2268460'>you</span> <span m='2268550'>might</span> <span m='2268700'>care</span>
  <span m='2268880'>about.</span> </p><p><span m='2270578'>AUDIENCE:</span> <span
  m='2270826'>[INAUDIBLE]</span> <span m='2271074'>certificate</span> <span m='2271570'>of
  interest?</span> </p><p><span m='2273060'>ERIK DEMAINE:</span> <span m='2273195'>Certificate</span>
  <span m='2273600'>of</span> <span m='2273720'>interest</span> <span m='2274050'>is</span>
  <span m='2274140'>just</span> <span m='2275690'>a</span> <span m='2275760'>Boolean</span>
  <span m='2276240'>function</span> <span m='2276600'>on</span> <span m='2276720'>a</span>
  <span m='2276780'>constant</span> <span m='2277290'>number</span> <span m='2277650'>of</span>
  <span m='2278730'>data</span> <span m='2278970'>points</span> <span m='2280680'>over</span>
  <span m='2280890'>time--</span> <span m='2281320'>a</span> <span m='2281550'>constant
  number</span> <span m='2281760'>of</span> <span m='2281850'>trajectories,</span>
  <span m='2282660'>I</span> <span m='2282720'>should</span> <span m='2282900'>say.</span>
  <span m='2285045'>I'll</span> <span m='2285360'>probably</span> <span m='2285750'>actually</span>
  <span m='2286110'>define</span> <span m='2286420'>certificate</span> <span m='2286950'>right</span>
  <span m='2287160'>now.</span> </p><p><span m='2287460'>AUDIENCE:</span> <span m='2287607'>Good.</span>
  </p><p><span m='2291360'>ERIK DEMAINE:</span> <span m='2291577'>Certificates--</span>
  <span m='2292470'>I'm</span> <span m='2292650'>going</span> <span m='2292800'>to</span>
  <span m='2292860'>define</span> <span m='2293130'>them</span> <span m='2293220'>more</span>
  <span m='2293460'>as</span> <span m='2293550'>a</span> <span m='2293610'>tool</span>
  <span m='2294030'>that</span> <span m='2294210'>we</span> <span m='2294360'>use</span>
  <span m='2294690'>to</span> <span m='2294810'>build</span> <span m='2294990'>data</span>
  <span m='2295200'>structures,</span> <span m='2295680'>but</span> <span m='2295860'>they're</span>
  <span m='2296010'>really</span> <span m='2296220'>the</span> <span m='2296310'>same</span>
  <span m='2296580'>thing</span> <span m='2296760'>that</span> <span m='2296880'>I</span>
  <span m='2296970'>mean</span> <span m='2297180'>here.</span> <span m='2306330'>So</span>
  <span m='2309510'>pretty</span> <span m='2309870'>much</span> <span m='2310170'>all</span>
  <span m='2310440'>kinetic</span> <span m='2310800'>data</span> <span m='2311010'>structures</span>
  <span m='2311520'>follow</span> <span m='2312540'>this</span> <span m='2312870'>unified</span>
  <span m='2313350'>approach.</span> <span m='2313740'>Kinetic</span> <span m='2314030'>data</span>
  <span m='2314220'>structures</span> <span m='2314480'>are</span> <span m='2314590'>actually</span>
  <span m='2314880'>a</span> <span m='2314910'>pretty</span> <span m='2315180'>new</span>
  <span m='2315330'>thing,</span> <span m='2316230'>introduced</span> <span m='2316620'>in</span>
  <span m='2316740'>1999.</span> <span m='2317890'>So</span> <span m='2318150'>as
  data</span> <span m='2318450'>structures</span> <span m='2318810'>go,</span> <span
  m='2318990'>that's</span> <span m='2319230'>new.</span> <span m='2320160'>And</span>
  <span m='2320490'>over</span> <span m='2320640'>the</span> <span m='2320730'>last</span>
  <span m='2322150'>however</span> <span m='2322380'>many</span> <span m='2322560'>years</span>
  <span m='2322740'>that</span> <span m='2322890'>is--</span> <span m='2323040'>13--</span>
  <span m='2323850'>there's</span> <span m='2324180'>been</span> <span m='2324330'>a</span>
  <span m='2324390'>bunch</span> <span m='2324630'>of</span> <span m='2325460'>kinetic</span>
  <span m='2325770'>data</span> <span m='2325950'>structures.</span> </p><p><span
  m='2329320'>So</span> <span m='2329490'>what</span> <span m='2329670'>we're</span>
  <span m='2329730'>going</span> <span m='2329820'>to</span> <span m='2329910'>do</span>
  <span m='2330690'>is</span> <span m='2331890'>store</span> <span m='2332280'>the</span>
  <span m='2332400'>data</span> <span m='2332640'>structure</span> <span m='2335790'>that</span>
  <span m='2335970'>is</span> <span m='2336120'>accurate</span> <span m='2336760'>now.</span>
  <span m='2339210'>So</span> <span m='2339780'>this</span> <span m='2339930'>will</span>
  <span m='2340020'>make</span> <span m='2340170'>queries</span> <span m='2340680'>about</span>
  <span m='2340920'>the</span> <span m='2341010'>present</span> <span m='2341340'>really</span>
  <span m='2341550'>easy.</span> <span m='2342370'>It</span> <span m='2342470'>just</span>
  <span m='2342810'>is</span> <span m='2343200'>.</span> <span m='2343710'>You</span>
  <span m='2343860'>look</span> <span m='2343980'>at</span> <span m='2344040'>the</span>
  <span m='2344130'>data</span> <span m='2344280'>structure,</span> <span m='2344670'>you</span>
  <span m='2344760'>do</span> <span m='2344910'>a</span> <span m='2344950'>query.</span>
  <span m='2346020'>And</span> <span m='2346200'>so</span> <span m='2346320'>the</span>
  <span m='2346440'>hard</span> <span m='2346620'>part</span> <span m='2346890'>becomes,</span>
  <span m='2348010'>how</span> <span m='2348120'>do</span> <span m='2348270'>I</span>
  <span m='2348420'>do</span> <span m='2348840'>advance?</span> <span m='2350310'>How</span>
  <span m='2350460'>do</span> <span m='2350580'>I</span> <span m='2350610'>advance</span>
  <span m='2351030'>time</span> <span m='2351870'>and</span> <span m='2352020'>make</span>
  <span m='2352320'>the</span> <span m='2352440'>new</span> <span m='2352620'>data</span>
  <span m='2352830'>structure,</span> <span m='2353290'>which</span> <span m='2353370'>is</span>
  <span m='2353730'>correct,</span> <span m='2354270'>about</span> <span m='2354600'>the</span>
  <span m='2354720'>new</span> <span m='2355080'>now?</span> </p><p><span m='2358230'>The
  way</span> <span m='2358450'>we</span> <span m='2358580'>do</span> <span m='2358700'>that</span>
  <span m='2359000'>is</span> <span m='2359180'>with</span> <span m='2359420'>certificates.</span>
  <span m='2360770'>So</span> <span m='2360980'>what</span> <span m='2361130'>I'm</span>
  <span m='2361220'>going</span> <span m='2361430'>to</span> <span m='2361550'>do</span>
  <span m='2363170'>is</span> <span m='2363320'>additionally</span> <span m='2363770'>store,</span>
  <span m='2367700'>basically,</span> <span m='2368180'>a</span> <span m='2368300'>proof</span>
  <span m='2368900'>that</span> <span m='2369080'>this</span> <span m='2369260'>data</span>
  <span m='2369500'>structure</span> <span m='2369950'>is</span> <span m='2370190'>valid.</span>
  <span m='2373135'>We can</span> <span m='2373630'>say</span> <span m='2374290'>conditions</span>
  <span m='2376970'>which</span> <span m='2376990'>are</span> <span m='2377080'>currently</span>
  <span m='2377440'>true--</span> <span m='2378860'>and</span> <span m='2379390'>as</span>
  <span m='2379450'>long</span> <span m='2379690'>as</span> <span m='2379780'>they</span>
  <span m='2379900'>remain</span> <span m='2380260'>true,</span> <span m='2381160'>the</span>
  <span m='2381280'>data</span> <span m='2381460'>structure</span> <span m='2381880'>remains</span>
  <span m='2382330'>valid.</span> <span m='2387250'>So</span> <span m='2387400'>these</span>
  <span m='2387580'>conditions</span> <span m='2387970'>are</span> <span m='2388060'>true</span>
  <span m='2388300'>now,</span> <span m='2390040'>and--</span> <span m='2392050'>sorry--</span>
  <span m='2392320'>under</span> <span m='2392590'>which</span> <span m='2392950'>data</span>
  <span m='2393190'>structure</span> <span m='2394540'>is</span> <span m='2394930'>accurate</span>
  <span m='2396252'>or</span> <span m='2396660'>correct.</span> <span m='2400150'>And</span>
  <span m='2400930'>those</span> <span m='2401140'>conditions</span> <span m='2401590'>are</span>
  <span m='2401710'>true</span> <span m='2401950'>now.</span> </p><p><span m='2404080'>OK,</span>
  <span m='2404500'>so</span> <span m='2405430'>for</span> <span m='2406150'>example--</span>
  <span m='2407810'>well,</span> <span m='2408280'>we'll</span> <span m='2408460'>get</span>
  <span m='2408610'>to</span> <span m='2408700'>examples</span> <span m='2409120'>in</span>
  <span m='2409210'>a</span> <span m='2409270'>moment.</span> <span m='2414720'>We'll
  just</span> <span m='2414910'>keep</span> <span m='2415210'>abstract</span> <span
  m='2415630'>for</span> <span m='2415720'>a</span> <span m='2415750'>little</span>
  <span m='2415960'>bit</span> <span m='2416080'>longer.</span> <span m='2418840'>Each</span>
  <span m='2419050'>of</span> <span m='2419140'>these</span> <span m='2419260'>certificates,</span>
  <span m='2420860'>you</span> <span m='2420910'>can</span> <span m='2421060'>figure</span>
  <span m='2421420'>out</span> <span m='2422110'>a</span> <span m='2422170'>failure</span>
  <span m='2422710'>time.</span> <span m='2439830'>So</span> <span m='2439980'>you</span>
  <span m='2440040'>have</span> <span m='2440190'>some</span> <span m='2440580'>certificate,</span>
  <span m='2441270'>like,</span> <span m='2442050'>this</span> <span m='2442260'>point</span>
  <span m='2442560'>is</span> <span m='2442710'>to</span> <span m='2442830'>the</span>
  <span m='2442920'>left</span> <span m='2443190'>of</span> <span m='2443280'>that</span>
  <span m='2443460'>point.</span> <span m='2445740'>And</span> <span m='2446100'>you</span>
  <span m='2446340'>just</span> <span m='2446640'>look</span> <span m='2447000'>ahead</span>
  <span m='2447600'>in</span> <span m='2447720'>time.</span> <span m='2448560'>If</span>
  <span m='2448680'>you</span> <span m='2448770'>have</span> <span m='2448980'>some</span>
  <span m='2449340'>constant</span> <span m='2449850'>defined</span> <span m='2450510'>trajectories,</span>
  <span m='2451300'>you just</span> <span m='2451390'>see,</span> <span m='2451590'>when</span>
  <span m='2451830'>is</span> <span m='2451950'>the</span> <span m='2452070'>time</span>
  <span m='2452640'>when</span> <span m='2452880'>they</span> <span m='2453030'>will</span>
  <span m='2453150'>be</span> <span m='2453330'>aligned</span> <span m='2453720'>vertically?</span>
  <span m='2454230'>After</span> <span m='2454560'>that</span> <span m='2454740'>time,</span>
  <span m='2455670'>they're</span> <span m='2455790'>going</span> <span m='2455910'>to</span>
  <span m='2456000'>switch</span> <span m='2456700'>who</span> <span m='2456880'>is</span>
  <span m='2457020'>left</span> <span m='2457260'>of</span> <span m='2457380'>whom.</span>
  </p><p><span m='2458700'>So</span> <span m='2458880'>just</span> <span m='2459030'>compute</span>
  <span m='2459330'>that</span> <span m='2459480'>failure</span> <span m='2459780'>time.</span>
  <span m='2460110'>I'm</span> <span m='2460170'>going</span> <span m='2460290'>to</span>
  <span m='2460350'>assume--</span> <span m='2461040'>that's</span> <span m='2461220'>another</span>
  <span m='2461490'>assumption</span> <span m='2461850'>about</span> <span m='2462090'>the</span>
  <span m='2462240'>trajectory</span> <span m='2462720'>model--</span> <span m='2463410'>that</span>
  <span m='2463570'>this</span> <span m='2463770'>takes</span> <span m='2464040'>constant</span>
  <span m='2464460'>time</span> <span m='2464850'>for</span> <span m='2465210'>trajectory.</span>
  <span m='2470640'>I</span> <span m='2470980'>do</span> <span m='2471130'>that</span>
  <span m='2471280'>for</span> <span m='2471430'>every</span> <span m='2472810'>certificate,</span>
  <span m='2474910'>and</span> <span m='2475090'>then</span> <span m='2476650'>put</span>
  <span m='2476890'>those</span> <span m='2477130'>failure</span> <span m='2477460'>times</span>
  <span m='2477850'>into a</span> <span m='2478090'>priority</span> <span m='2478540'>queue.</span>
  <span m='2483232'>Do you want to</span> <span m='2483730'>ask</span> <span m='2483900'>your</span>
  <span m='2484010'>question?</span> </p><p><span m='2485392'>AUDIENCE:</span> <span
  m='2485640'>So</span> <span m='2486880'>is it required</span> <span m='2487376'>that
  a</span> <span m='2487872'>certificate</span> <span m='2488864'>needs to be--</span>
  <span m='2490352'>like,</span> <span m='2490848'>that</span> <span m='2491344'>we've
  checked that a</span> <span m='2491840'>certificate</span> <span m='2492336'>is
  true.</span> <span m='2493328'>It</span> <span m='2493840'>just</span> <span m='2494290'>needs
  to be</span> <span m='2494712'>bounded</span> <span m='2495134'>by order</span>
  <span m='2495556'>one, or--</span> </p><p><span m='2496400'>ERIK DEMAINE:</span>
  <span m='2496550'>Yeah.</span> <span m='2496700'>So</span> <span m='2497270'>I'm</span>
  <span m='2497450'>assuming</span> <span m='2498800'>checking</span> <span m='2499160'>a</span>
  <span m='2499220'>certificate</span> <span m='2499700'>takes</span> <span m='2499940'>constant</span>
  <span m='2500320'>time,</span> <span m='2501100'>whether</span> <span m='2501320'>it</span>
  <span m='2501440'>currently</span> <span m='2501800'>holds,</span> <span m='2502820'>and</span>
  <span m='2503120'>computing</span> <span m='2503435'>the</span> <span m='2503980'>failure</span>
  <span m='2504410'>time</span> <span m='2504680'>takes</span> <span m='2504890'>constant</span>
  <span m='2505190'>time.</span> <span m='2506160'>Yeah.</span> <span m='2507440'>I</span>
  <span m='2507500'>mean,</span> <span m='2508370'>you</span> <span m='2508550'>could</span>
  <span m='2508670'>assume</span> <span m='2508970'>it,</span> <span m='2509060'>or</span>
  <span m='2509420'>maybe</span> <span m='2509630'>you</span> <span m='2509720'>pay</span>
  <span m='2509900'>a</span> <span m='2509930'>little</span> <span m='2510140'>more.</span>
  <span m='2510650'>I</span> <span m='2510710'>mean,</span> <span m='2510860'>this</span>
  <span m='2511040'>is</span> <span m='2511190'>how</span> <span m='2511370'>we're</span>
  <span m='2511460'>going</span> <span m='2511570'>to</span> <span m='2511640'>build</span>
  <span m='2511830'>the</span> <span m='2511910'>data</span> <span m='2512090'>structure.</span>
  <span m='2512510'>So</span> <span m='2512750'>whatever</span> <span m='2513080'>it</span>
  <span m='2513140'>costs,</span> <span m='2513620'>it</span> <span m='2513710'>will</span>
  <span m='2513830'>cost.</span> <span m='2514340'>But</span> <span m='2515150'>I</span>
  <span m='2515210'>think</span> <span m='2515420'>everything</span> <span m='2515750'>we'll</span>
  <span m='2515840'>talk</span> <span m='2516080'>about</span> <span m='2516350'>and</span>
  <span m='2516400'>pretty</span> <span m='2516590'>much</span> <span m='2516770'>every</span>
  <span m='2516950'>certificate</span> <span m='2517400'>out</span> <span m='2517580'>there</span>
  <span m='2517730'>is</span> <span m='2517820'>sort</span> <span m='2518030'>of</span>
  <span m='2518090'>a</span> <span m='2518150'>constant</span> <span m='2518570'>size</span>
  <span m='2519710'>thing.</span> </p><p><span m='2520970'>Some</span> <span m='2521180'>of</span>
  <span m='2521240'>them</span> <span m='2521360'>are</span> <span m='2521420'>bigger.</span>
  <span m='2521810'>But</span> <span m='2522940'>we'll</span> <span m='2523220'>get</span>
  <span m='2523370'>to</span> <span m='2523610'>the</span> <span m='2523730'>costs</span>
  <span m='2524300'>involved.</span> <span m='2525110'>Maybe</span> <span m='2525290'>we</span>
  <span m='2525350'>won't</span> <span m='2525500'>worry</span> <span m='2525650'>about</span>
  <span m='2525860'>time</span> <span m='2526070'>too</span> <span m='2526190'>much.</span>
  </p><p><span m='2527771'>So priority</span> <span m='2528180'>queue</span> <span
  m='2528550'>is</span> <span m='2528640'>going</span> <span m='2528750'>to</span>
  <span m='2528860'>take</span> <span m='2529670'>log</span> <span m='2530170'>n</span>
  <span m='2530450'>time,</span> <span m='2530810'>where</span> <span m='2530930'>n</span>
  <span m='2531050'>is</span> <span m='2531200'>the</span> <span m='2531290'>number</span>
  <span m='2531530'>of</span> <span m='2531590'>certificates</span> <span m='2531980'>in</span>
  <span m='2532370'>the</span> <span m='2532520'>data</span> <span m='2532700'>structure,</span>
  <span m='2533480'>to</span> <span m='2533600'>find,</span> <span m='2533960'>when</span>
  <span m='2534230'>is</span> <span m='2534380'>the</span> <span m='2534500'>next</span>
  <span m='2534770'>failure?</span> <span m='2535740'>So</span> <span m='2535840'>if</span>
  <span m='2535940'>I</span> <span m='2536040'>want</span> <span m='2536090'>to</span>
  <span m='2536150'>do</span> <span m='2536240'>an</span> <span m='2536330'>advance,</span>
  <span m='2537410'>basically,</span> <span m='2537500'>I'm going</span> <span m='2537590'>to</span>
  <span m='2537830'>do</span> <span m='2538340'>discrete</span> <span m='2538700'>event</span>
  <span m='2538910'>simulation.</span> <span m='2539450'>I</span> <span m='2539540'>find</span>
  <span m='2539780'>the</span> <span m='2539870'>next</span> <span m='2540200'>event</span>
  <span m='2540530'>when</span> <span m='2540680'>something</span> <span m='2541070'>changes,</span>
  <span m='2541580'>i.e.</span> <span m='2541970'>a</span> <span m='2542030'>certificate</span>
  <span m='2542690'>fails.</span> <span m='2543610'>I'm going</span> <span m='2543670'>to</span>
  <span m='2543840'>fix</span> <span m='2544160'>that</span> <span m='2544340'>event--</span>
  <span m='2545560'>fix</span> <span m='2545870'>that</span> <span m='2546020'>certificate--</span>
  <span m='2546830'>make</span> <span m='2547130'>the</span> <span m='2547220'>data</span>
  <span m='2547400'>structure</span> <span m='2547730'>correct</span> <span m='2548210'>again.</span>
  <span m='2549230'>Then</span> <span m='2549380'>advance</span> <span m='2549770'>to</span>
  <span m='2549860'>the</span> <span m='2549980'>next</span> <span m='2550310'>failure.</span>
  <span m='2551240'>Repeat.</span> <span m='2552510'>As</span> <span m='2552680'>long</span>
  <span m='2552830'>as</span> <span m='2552890'>there</span> <span m='2552980'>aren't</span>
  <span m='2553100'>too</span> <span m='2553280'>many</span> <span m='2553460'>certificates</span>
  <span m='2554060'>to</span> <span m='2554150'>mess</span> <span m='2554360'>me</span>
  <span m='2554540'>up,</span> <span m='2555590'>this</span> <span m='2555770'>advance</span>
  <span m='2556220'>will</span> <span m='2556430'>be</span> <span m='2556880'>fast.</span>
  <span m='2561100'>So</span> <span m='2562790'>yeah.</span> </p><p><span m='2582010'>So</span>
  <span m='2582190'>here's</span> <span m='2582430'>how</span> <span m='2582550'>we're</span>
  <span m='2582610'>going</span> <span m='2582760'>to</span> <span m='2583030'>implement</span>
  <span m='2583420'>advance.</span> <span m='2584690'>Basically</span> <span m='2585430'>in</span>
  <span m='2585580'>all</span> <span m='2585910'>kinetic</span> <span m='2586300'>data</span>
  <span m='2586510'>structures,</span> <span m='2587770'>we</span> <span m='2587920'>just</span>
  <span m='2588110'>say,</span> <span m='2588640'>while</span> <span m='2591430'>t</span>
  <span m='2591940'>is</span> <span m='2592270'>greater</span> <span m='2592690'>than</span>
  <span m='2593020'>or</span> <span m='2593170'>equal</span> <span m='2593500'>to</span>
  <span m='2595240'>the</span> <span m='2595360'>next</span> <span m='2595690'>failure</span>
  <span m='2595990'>of</span> <span m='2596680'>the</span> <span m='2596830'>priority</span>
  <span m='2597220'>queue,</span> <span m='2599020'>we</span> <span m='2599170'>advance</span>
  <span m='2599650'>to</span> <span m='2599770'>that</span> <span m='2600130'>moment</span>
  <span m='2600460'>in</span> <span m='2600550'>time,</span> <span m='2601330'>when</span>
  <span m='2601450'>something</span> <span m='2601750'>interesting</span> <span m='2602170'>happens.</span>
  <span m='2605560'>We</span> <span m='2605680'>do</span> <span m='2605950'>an</span>
  <span m='2606070'>event.</span> <span m='2610672'>I'll write it</span> <span m='2611130'>this
  way.</span> <span m='2619960'>And</span> <span m='2620530'>then</span> <span m='2620890'>we</span>
  <span m='2621010'>set</span> <span m='2621280'>now</span> <span m='2621540'>to</span>
  <span m='2621690'>t.</span> </p><p><span m='2628550'>And this</span> <span m='2628730'>event</span>
  <span m='2629030'>thing</span> <span m='2629600'>has</span> <span m='2629810'>to</span>
  <span m='2629930'>somehow</span> <span m='2630860'>fix</span> <span m='2631130'>the</span>
  <span m='2631220'>data</span> <span m='2631400'>structure</span> <span m='2633200'>and</span>
  <span m='2634910'>fix</span> <span m='2635180'>the</span> <span m='2635270'>certificates.</span>
  <span m='2639460'>So</span> <span m='2639650'>that</span> <span m='2639920'>is</span>
  <span m='2640130'>the</span> <span m='2640220'>challenge,</span> <span m='2640700'>is,</span>
  <span m='2640820'>how</span> <span m='2640970'>do</span> <span m='2641030'>you</span>
  <span m='2641150'>deal</span> <span m='2641360'>with</span> <span m='2641510'>an</span>
  <span m='2641600'>event</span> <span m='2642380'>when</span> <span m='2642530'>one</span>
  <span m='2642680'>of</span> <span m='2642770'>your</span> <span m='2642890'>certificates</span>
  <span m='2643520'>breaks?</span> <span m='2645030'>So</span> <span m='2645260'>if</span>
  <span m='2645380'>you</span> <span m='2645770'>have</span> <span m='2645980'>a</span>
  <span m='2646040'>data</span> <span m='2646190'>structure,</span> <span m='2646520'>and
  you</span> <span m='2646580'>want</span> <span m='2646730'>to</span> <span m='2646790'>make</span>
  <span m='2646940'>it,</span> <span m='2647000'>kinetic</span> <span m='2648210'>you</span>
  <span m='2648350'>just</span> <span m='2648830'>first</span> <span m='2649100'>write</span>
  <span m='2649310'>down</span> <span m='2649460'>some</span> <span m='2649610'>certificates</span>
  <span m='2650210'>under</span> <span m='2650420'>which</span> <span m='2650600'>it's</span>
  <span m='2650720'>guaranteed</span> <span m='2651140'>to</span> <span m='2651230'>be</span>
  <span m='2651350'>valid,</span> <span m='2653090'>and</span> <span m='2653240'>then</span>
  <span m='2654710'>see</span> <span m='2655040'>how</span> <span m='2655160'>to</span>
  <span m='2655250'>fix</span> <span m='2655520'>them</span> <span m='2656120'>as</span>
  <span m='2656300'>things</span> <span m='2656630'>happen.</span> <span m='2657020'>Then</span>
  <span m='2657170'>there's</span> <span m='2657350'>the</span> <span m='2657410'>analysis</span>
  <span m='2657890'>issue,</span> <span m='2658160'>which</span> <span m='2658340'>we</span>
  <span m='2658430'>will</span> <span m='2658580'>get</span> <span m='2658730'>to.</span>
  </p><p><span m='2659010'>Let's</span> <span m='2659170'>start</span> <span m='2659390'>with</span>
  <span m='2659540'>an</span> <span m='2659630'>example</span> <span m='2660750'>before</span>
  <span m='2660860'>we</span> <span m='2660950'>get</span> <span m='2661070'>to</span>
  <span m='2661160'>analyzing,</span> <span m='2662530'>so</span> <span m='2662890'>this</span>
  <span m='2663080'>becomes</span> <span m='2663410'>a</span> <span m='2663440'>little</span>
  <span m='2663650'>more</span> <span m='2663830'>concrete.</span> </p><p><span m='2672602'>AUDIENCE:</span>
  <span m='2672845'>I have another</span> <span m='2673088'>question.</span> </p><p><span
  m='2674070'>ERIK DEMAINE:</span> <span m='2674175'>Yeah.</span> </p><p><span m='2674280'>AUDIENCE:</span>
  <span m='2674438'>So</span> <span m='2674596'>are</span> <span m='2674755'>the change</span>
  <span m='2675230'>operations</span> <span m='2678080'>sort of</span> <span m='2678555'>online,</span>
  <span m='2679030'>or do you</span> <span m='2679505'>have</span> <span m='2679980'>the</span>
  <span m='2680455'>sequence of</span> <span m='2680930'>changes</span> <span m='2681405'>that
  you're going to</span> <span m='2681890'>[INAUDIBLE]</span> </p><p><span m='2682110'>ERIK
  DEMAINE:</span> <span m='2682245'>All</span> <span m='2682380'>of</span> <span m='2682470'>these</span>
  <span m='2682650'>operations</span> <span m='2683190'>are</span> <span m='2683280'>online.</span>
  <span m='2683880'>So</span> <span m='2684980'>at</span> <span m='2685110'>any</span>
  <span m='2685290'>moment,</span> <span m='2685650'>someone</span> <span m='2685980'>says</span>
  <span m='2686190'>advance,</span> <span m='2686700'>someone</span> <span m='2686955'>says</span>
  <span m='2687210'>change,</span> <span m='2688050'>or</span> <span m='2688230'>someone</span>
  <span m='2688500'>says</span> <span m='2688680'>query.</span> <span m='2689040'>And
  query</span> <span m='2689520'>is</span> <span m='2689670'>respect</span> <span
  m='2690180'>to</span> <span m='2691050'>now.</span> </p><p><span m='2693950'>So</span>
  <span m='2694170'>we</span> <span m='2694380'>have</span> <span m='2694500'>no</span>
  <span m='2694620'>idea</span> <span m='2694950'>which</span> <span m='2695160'>of</span>
  <span m='2695220'>these</span> <span m='2695460'>are</span> <span m='2695550'>coming,</span>
  <span m='2696530'>in</span> <span m='2696650'>what</span> <span m='2696810'>order,</span>
  <span m='2697460'>whatever.</span> <span m='2697825'>I</span> <span m='2698140'>don't</span>
  <span m='2698430'>think</span> <span m='2699600'>anyone's</span> <span m='2699910'>studied</span>
  <span m='2700320'>the</span> <span m='2700410'>case</span> <span m='2700650'>where</span>
  <span m='2700740'>you know up</span> <span m='2701220'>front</span> <span m='2701520'>all</span>
  <span m='2701640'>the</span> <span m='2701730'>things</span> <span m='2701970'>that</span>
  <span m='2702070'>are</span> <span m='2702170'>going</span> <span m='2702270'>to</span>
  <span m='2702370'>happen.</span> <span m='2703120'>Though</span> <span m='2703290'>there</span>
  <span m='2703440'>are,</span> <span m='2703770'>presumably,</span> <span m='2704490'>applications</span>
  <span m='2705090'>for</span> <span m='2705210'>that.</span> <span m='2705630'>I</span>
  <span m='2705660'>mean,</span> <span m='2705840'>time</span> <span m='2706170'>can</span>
  <span m='2706320'>just</span> <span m='2706470'>be</span> <span m='2706590'>a</span>
  <span m='2706620'>euphemism</span> <span m='2707160'>for</span> <span m='2707410'>a</span>
  <span m='2707430'>dimension,</span> <span m='2708090'>or</span> <span m='2708180'>whatever.</span>
  <span m='2710410'>But</span> <span m='2710750'>a</span> <span m='2710850'>lot</span>
  <span m='2711120'>of</span> <span m='2711210'>the</span> <span m='2711300'>kinetic</span>
  <span m='2711600'>people</span> <span m='2712170'>really</span> <span m='2712470'>want</span>
  <span m='2712650'>to</span> <span m='2712710'>be</span> <span m='2712830'>tracking</span>
  <span m='2713220'>points</span> <span m='2713580'>and</span> <span m='2713670'>maintaining</span>
  <span m='2714630'>what's</span> <span m='2714840'>happening.</span> </p><p><span
  m='2717300'>So</span> <span m='2718260'>let's</span> <span m='2718410'>do</span>
  <span m='2718560'>a</span> <span m='2718620'>1D</span> <span m='2718980'>problem--</span>
  <span m='2720670'>a</span> <span m='2720720'>simple</span> <span m='2721050'>one--</span>
  <span m='2722060'>sort of</span> <span m='2722400'>the</span> <span m='2722490'>most</span>
  <span m='2722700'>basic</span> <span m='2723060'>problem,</span> <span m='2724370'>which</span>
  <span m='2724410'>is</span> <span m='2724490'>a</span> <span m='2724530'>predecessor</span>
  <span m='2725130'>problem.</span> <span m='2726090'>Insert,</span> <span m='2726670'>delete.</span>
  <span m='2727880'>We</span> <span m='2727980'>won't</span> <span m='2728100'>worry</span>
  <span m='2728310'>too</span> <span m='2728430'>much</span> <span m='2728610'>about</span>
  <span m='2728760'>insert and</span> <span m='2729060'>delete</span> <span m='2729330'>here.</span>
  <span m='2730830'>It's</span> <span m='2730920'>hard</span> <span m='2731070'>enough,</span>
  <span m='2731340'>because</span> <span m='2731520'>the</span> <span m='2731610'>points</span>
  <span m='2731880'>are</span> <span m='2731970'>moving</span> <span m='2732240'>around--</span>
  <span m='2733590'>and</span> <span m='2734610'>predecessor</span> <span m='2735180'>and</span>
  <span m='2735270'>successor.</span> </p><p><span m='2736020'>So</span> <span m='2736140'>I</span>
  <span m='2736200'>want</span> <span m='2736410'>to</span> <span m='2736500'>know,</span>
  <span m='2736980'>on</span> <span m='2737190'>the</span> <span m='2737280'>line,</span>
  <span m='2738920'>I</span> <span m='2738980'>have</span> <span m='2739170'>some</span>
  <span m='2739320'>points.</span> <span m='2739800'>They're</span> <span m='2739940'>moving.</span>
  <span m='2740910'>Now,</span> <span m='2741150'>query</span> <span m='2741630'>is,</span>
  <span m='2742330'>at</span> <span m='2742470'>the</span> <span m='2742660'>current</span>
  <span m='2742980'>time,</span> <span m='2744750'>who's</span> <span m='2744930'>to</span>
  <span m='2745050'>the</span> <span m='2745110'>left</span> <span m='2745380'>and</span>
  <span m='2745470'>who's</span> <span m='2745620'>to</span> <span m='2745740'>the</span>
  <span m='2745830'>right</span> <span m='2746040'>of</span> <span m='2746160'>this</span>
  <span m='2746310'>query?</span> <span m='2748035'>OK.</span> </p><p><span m='2751360'>How</span>
  <span m='2751570'>do</span> <span m='2751690'>we</span> <span m='2751780'>maintain</span>
  <span m='2752230'>this?</span> <span m='2754330'>This</span> <span m='2754750'>is</span>
  <span m='2754810'>a</span> <span m='2754870'>problem</span> <span m='2755140'>we'll</span>
  <span m='2755260'>be</span> <span m='2755350'>studying</span> <span m='2755650'>a</span>
  <span m='2755710'>lot</span> <span m='2755920'>in</span> <span m='2756070'>this</span>
  <span m='2756220'>class.</span> <span m='2757030'>But</span> <span m='2757240'>the</span>
  <span m='2757660'>basic</span> <span m='2758230'>structure</span> <span m='2758740'>for</span>
  <span m='2758890'>solving</span> <span m='2759250'>predecessor,</span> <span m='2759760'>insert,</span>
  <span m='2760130'>delete,</span> <span m='2760330'>predecessor,</span> <span m='2760990'>is--</span>
  </p><p><span m='2763846'>AUDIENCE:</span> <span m='2764084'>Binary</span> <span
  m='2764322'>search tree.</span> </p><p><span m='2764800'>ERIK DEMAINE:</span> <span
  m='2764925'>Binary</span> <span m='2765290'>search</span> <span m='2765570'>tree--</span>
  <span m='2768190'>balanced</span> <span m='2768560'>binary</span> <span m='2768830'>search
  tree.</span> <span m='2769840'>OK,</span> <span m='2769980'>so</span> <span m='2770110'>let's</span>
  <span m='2770290'>use</span> <span m='2770620'>a</span> <span m='2770680'>log</span>
  <span m='2770990'>n</span> <span m='2771130'>high</span> <span m='2771760'>AVL</span>
  <span m='2772120'>trees--</span> <span m='2772480'>whatever.</span> <span m='2774970'>So</span>
  <span m='2775210'>what</span> <span m='2775360'>do</span> <span m='2775450'>we</span>
  <span m='2775600'>need</span> <span m='2776710'>for</span> <span m='2776860'>certificates?</span>
  <span m='2778420'>I</span> <span m='2778450'>was</span> <span m='2778540'>going</span>
  <span m='2778640'>to</span> <span m='2778750'>use</span> <span m='2778870'>this</span>
  <span m='2779020'>as</span> <span m='2779140'>an</span> <span m='2779200'>example,</span>
  <span m='2779680'>but</span> <span m='2779800'>it's</span> <span m='2779950'>actually</span>
  <span m='2780190'>a</span> <span m='2780220'>little</span> <span m='2780400'>tricky</span>
  <span m='2780700'>to</span> <span m='2780820'>think</span> <span m='2781000'>about</span>
  <span m='2781750'>what</span> <span m='2781930'>the</span> <span m='2782020'>certificates</span>
  <span m='2782620'>are.</span> <span m='2783580'>Because</span> <span m='2783820'>the</span>
  <span m='2783940'>binary</span> <span m='2784270'>search</span> <span m='2784480'>tree</span>
  <span m='2784630'>property</span> <span m='2785320'>is</span> <span m='2787030'>x</span>
  <span m='2787345'>plus</span> <span m='2787660'>or</span> <span m='2788120'>equal</span>
  <span m='2788350'>to</span> <span m='2788440'>x</span> <span m='2790090'>greater</span>
  <span m='2790440'>or</span> <span m='2790540'>equal</span> <span m='2790670'>to</span>
  <span m='2790740'>x.</span> </p><p><span m='2792730'>That's</span> <span m='2792880'>kind</span>
  <span m='2793060'>of</span> <span m='2793150'>a</span> <span m='2793180'>lot</span>
  <span m='2793390'>of</span> <span m='2793450'>certificates.</span> <span m='2793795'>If</span>
  <span m='2794140'>I</span> <span m='2794200'>want</span> <span m='2794320'>to</span>
  <span m='2794380'>compare</span> <span m='2794710'>x</span> <span m='2795020'>to</span>
  <span m='2795160'>every</span> <span m='2795550'>single</span> <span m='2795880'>guy
  in</span> <span m='2796210'>here</span> <span m='2796510'>and</span> <span m='2796775'>compare</span>
  <span m='2797040'>x</span> <span m='2797260'>to</span> <span m='2797350'>every</span>
  <span m='2797590'>single</span> <span m='2797860'>guy in</span> <span m='2798100'>here,</span>
  <span m='2798700'>that</span> <span m='2798840'>would</span> <span m='2798930'>be</span>
  <span m='2799210'>a,</span> <span m='2799440'>I</span> <span m='2799640'>think,</span>
  <span m='2799930'>quadratic</span> <span m='2800530'>number of</span> <span m='2800770'>certificates,</span>
  <span m='2801490'>in</span> <span m='2801730'>general.</span> <span m='2802120'>Almost</span>
  <span m='2802450'>everyone</span> <span m='2802900'>has</span> <span m='2803140'>a</span>
  <span m='2803290'>relation.</span> <span m='2804550'>I'd</span> <span m='2804680'>prefer</span>
  <span m='2805000'>to</span> <span m='2805120'>get</span> <span m='2805420'>away</span>
  <span m='2805630'>with</span> <span m='2805780'>fewer</span> <span m='2806050'>certificates.</span>
  <span m='2806680'>Because</span> <span m='2806870'>then, less</span> <span m='2807370'>certificates</span>
  <span m='2807970'>will</span> <span m='2808660'>fail.</span> </p><p><span m='2811400'>So</span>
  <span m='2812920'>cute</span> <span m='2813160'>idea--</span> <span m='2815140'>I</span>
  <span m='2815200'>really</span> <span m='2815530'>only</span> <span m='2815680'>need</span>
  <span m='2815830'>to</span> <span m='2815950'>compare</span> <span m='2816250'>x</span>
  <span m='2816550'>with</span> <span m='2816820'>this</span> <span m='2817030'>one</span>
  <span m='2818350'>and</span> <span m='2818650'>this</span> <span m='2818860'>one.</span>
  <span m='2819040'>--</span> <span m='2819960'>the</span> <span m='2820090'>max</span>
  <span m='2820450'>in</span> <span m='2820540'>the</span> <span m='2820840'>subtree</span>
  <span m='2821170'>and</span> <span m='2821260'>the</span> <span m='2821350'>min</span>
  <span m='2821530'>in</span> <span m='2821650'>the</span> <span m='2821810'>subtree.</span>
  <span m='2822730'>In</span> <span m='2822850'>general,</span> <span m='2824360'>if</span>
  <span m='2824380'>I</span> <span m='2824440'>look</span> <span m='2824620'>at</span>
  <span m='2824710'>the</span> <span m='2824800'>data</span> <span m='2825100'>in</span>
  <span m='2825250'>sorted</span> <span m='2825640'>order,</span> <span m='2826900'>it</span>
  <span m='2826990'>has</span> <span m='2827170'>to</span> <span m='2827260'>stay</span>
  <span m='2827470'>sorted</span> <span m='2827850'>order,</span> <span m='2830800'>where</span>
  <span m='2835770'>it's</span> <span m='2835920'>not</span> <span m='2836070'>going</span>
  <span m='2836190'>to</span> <span m='2836250'>be</span> <span m='2836340'>sorted.</span>
  <span m='2837630'>But</span> <span m='2837810'>this</span> <span m='2838170'>is</span>
  <span m='2838620'>an</span> <span m='2838790'>inorder</span> <span m='2839260'>traversal.</span>
  </p><p><span m='2842810'>Inorder</span> <span m='2843240'>traversal</span> <span
  m='2844260'>is</span> <span m='2844470'>something</span> <span m='2844860'>we</span>
  <span m='2844980'>can</span> <span m='2845250'>understand</span> <span m='2846390'>without</span>
  <span m='2846750'>knowing</span> <span m='2847110'>what</span> <span m='2847260'>the</span>
  <span m='2847350'>data</span> <span m='2847650'>is.</span> <span m='2847950'>Because</span>
  <span m='2848100'>remember,</span> <span m='2848340'>data</span> <span m='2848550'>is</span>
  <span m='2848670'>constantly</span> <span m='2849240'>changing.</span> <span m='2849790'>We</span>
  <span m='2849890'>can't</span> <span m='2849990'>really</span> <span m='2850200'>use</span>
  <span m='2850470'>the</span> <span m='2850590'>keys</span> <span m='2850920'>here.</span>
  <span m='2852000'>But</span> <span m='2852150'>we</span> <span m='2852270'>can</span>
  <span m='2852390'>use</span> <span m='2852570'>the</span> <span m='2852660'>abstract</span>
  <span m='2853080'>shape</span> <span m='2853320'>of</span> <span m='2853410'>the</span>
  <span m='2853500'>tree</span> <span m='2853770'>and</span> <span m='2853860'>do</span>
  <span m='2853980'>an</span> <span m='2854070'>inorder</span> <span m='2854340'>traversal,</span>
  <span m='2856770'>and</span> <span m='2856860'>say,</span> <span m='2857040'>look,</span>
  <span m='2857610'>as</span> <span m='2857760'>long</span> <span m='2858030'>as</span>
  <span m='2858190'>x i</span> <span m='2858590'>is</span> <span m='2858860'>less
  than</span> <span m='2858960'>or equal to</span> <span m='2859070'>x i</span> <span
  m='2859340'>plus</span> <span m='2859560'>one</span> <span m='2859890'>in</span>
  <span m='2860145'>the</span> <span m='2860400'>inorder</span> <span m='2860580'>traversal</span>
  <span m='2861030'>for</span> <span m='2861180'>all</span> <span m='2861390'>i,</span>
  <span m='2862350'>then</span> <span m='2862980'>this</span> <span m='2863160'>is</span>
  <span m='2863280'>a</span> <span m='2863340'>valid</span> <span m='2863730'>binary</span>
  <span m='2864030'>search</span> <span m='2864270'>tree.</span> <span m='2864690'>If
  an</span> <span m='2864880'>inorder</span> <span m='2865040'>traversal</span> <span
  m='2865560'>stays</span> <span m='2865860'>sorted,</span> <span m='2866340'>we're</span>
  <span m='2866777'>golden.</span> </p><p><span m='2868090'>So</span> <span m='2868140'>those</span>
  <span m='2868350'>are</span> <span m='2868410'>my</span> <span m='2868560'>certificates.</span>
  <span m='2868845'>There's</span> <span m='2869130'>only</span> <span m='2869370'>n</span>
  <span m='2869520'>of</span> <span m='2869610'>them.</span> <span m='2870951'>So</span>
  <span m='2871350'>that's</span> <span m='2871560'>nice.</span> </p><p><span m='2875910'>And</span>
  <span m='2876610'>we</span> <span m='2876720'>need</span> <span m='2876870'>to</span>
  <span m='2876960'>check</span> <span m='2877410'>that</span> <span m='2877830'>we</span>
  <span m='2877950'>can</span> <span m='2878070'>compute</span> <span m='2878460'>a</span>
  <span m='2878520'>failure</span> <span m='2878910'>time.</span> <span m='2879270'>This</span>
  <span m='2879450'>is</span> <span m='2879630'>usually</span> <span m='2880050'>really</span>
  <span m='2880290'>easy.</span> <span m='2880700'>But</span> <span m='2880920'>we'll</span>
  <span m='2881400'>go</span> <span m='2881550'>through</span> <span m='2881700'>the</span>
  <span m='2881790'>exercise</span> <span m='2890478'>of</span> <span m='2890980'>writing</span>
  <span m='2891370'>it</span> <span m='2891430'>down.</span> </p><p><span m='2896590'>So</span>
  <span m='2896950'>I</span> <span m='2897100'>want</span> <span m='2897270'>to</span>
  <span m='2897370'>know,</span> <span m='2898180'>among</span> <span m='2898480'>all</span>
  <span m='2898630'>times</span> <span m='2899050'>greater</span> <span m='2899340'>than
  or equal to</span> <span m='2899620'>now,</span> <span m='2900640'>when</span> <span
  m='2901060'>will</span> <span m='2902320'>x i--</span> <span m='2903325'>am I</span>
  <span m='2903580'>doing</span> <span m='2903790'>strict</span> <span m='2904150'>here?</span>
  <span m='2904695'>This</span> <span m='2905030'>should</span> <span m='2905760'>probably</span>
  <span m='2906050'>be</span> <span m='2906310'>greater</span> <span m='2906640'>than.</span>
  <span m='2908850'>Yeah,</span> <span m='2909090'>so</span> <span m='2909280'>that's</span>
  <span m='2909460'>why</span> <span m='2909620'>I</span> <span m='2909670'>have</span>
  <span m='2909740'>an</span> <span m='2909810'>infimum.</span> </p><p><span m='2911760'>OK,</span>
  <span m='2912370'>I</span> <span m='2912490'>take</span> <span m='2912740'>the</span>
  <span m='2914320'>earliest</span> <span m='2914740'>moment</span> <span m='2915130'>when</span>
  <span m='2915390'>x i of</span> <span m='2915860'>t</span> <span m='2916270'>is</span>
  <span m='2916450'>greater</span> <span m='2916780'>than</span> <span m='2916900'>x
  i</span> <span m='2917110'>of</span> <span m='2917230'>plus</span> <span m='2917470'>one,</span>
  <span m='2917690'>which is</span> <span m='2917850'>the</span> <span m='2917950'>opposite</span>
  <span m='2918430'>of</span> <span m='2918520'>what</span> <span m='2918670'>I</span>
  <span m='2918790'>want,</span> <span m='2920080'>and</span> <span m='2921070'>take</span>
  <span m='2921310'>the</span> <span m='2921430'>infimum</span> <span m='2921790'>of</span>
  <span m='2922000'>those</span> <span m='2922210'>times.</span> <span m='2922660'>And</span>
  <span m='2922750'>so</span> <span m='2923350'>that</span> <span m='2923530'>will</span>
  <span m='2923650'>be</span> <span m='2923950'>the</span> <span m='2924070'>moment</span>
  <span m='2924280'>of</span> <span m='2924340'>transition</span> <span m='2924790'>when</span>
  <span m='2924910'>they're</span> <span m='2925060'>equal.</span> <span m='2925930'>And</span>
  <span m='2926040'>then--</span> <span m='2926230'>boom--</span> <span m='2926710'>it's</span>
  <span m='2926830'>going</span> <span m='2926960'>to</span> <span m='2927040'>jump</span>
  <span m='2927280'>over.</span> <span m='2927520'>I'm</span> <span m='2927700'>assuming</span>
  <span m='2928060'>these</span> <span m='2928210'>things</span> <span m='2928450'>are</span>
  <span m='2928660'>continuous.</span> </p><p><span m='2930310'>AUDIENCE:</span> <span
  m='2930406'>That's</span> <span m='2930502'>why</span> <span m='2930598'>you</span>
  <span m='2930694'>take</span> <span m='2930790'>the</span> <span m='2930910'>infimum?</span>
  </p><p><span m='2931660'>ERIK DEMAINE:</span> <span m='2931855'>Yeah.</span> <span
  m='2932385'>So</span> <span m='2932720'>it</span> <span m='2932740'>would</span>
  <span m='2932860'>be</span> <span m='2933040'>an</span> <span m='2933410'>infimum,</span>
  <span m='2933730'>because</span> <span m='2935020'>these</span> <span m='2935200'>guys</span>
  <span m='2935620'>are</span> <span m='2936610'>going</span> <span m='2936730'>to
  cross.</span> <span m='2937420'>I</span> <span m='2937480'>mean,</span> <span m='2937720'>I</span>
  <span m='2937810'>don't</span> <span m='2937990'>care</span> <span m='2938260'>about</span>
  <span m='2939130'>this</span> <span m='2939340'>kind</span> <span m='2939520'>of</span>
  <span m='2939610'>happening.</span> <span m='2940355'>But</span> <span m='2940620'>if</span>
  <span m='2940660'>it's</span> <span m='2940750'>going</span> <span m='2940870'>to</span>
  <span m='2940930'>actually</span> <span m='2941380'>go</span> <span m='2941500'>across,</span>
  <span m='2942040'>then</span> <span m='2942220'>there'll</span> <span m='2942390'>be</span>
  <span m='2942520'>the</span> <span m='2942640'>moment</span> <span m='2942910'>of</span>
  <span m='2942970'>transition</span> <span m='2943870'>where</span> <span m='2943960'>they're</span>
  <span m='2944080'>equal.</span> <span m='2944470'>And</span> <span m='2944560'>that's</span>
  <span m='2944740'>going</span> <span m='2944920'>to</span> <span m='2944980'>be</span>
  <span m='2945100'>this</span> <span m='2945290'>infimum.</span> </p><p><span m='2947810'>OK.</span>
  <span m='2948730'>How</span> <span m='2948910'>do</span> <span m='2948970'>you</span>
  <span m='2949060'>compute</span> <span m='2949390'>that?</span> <span m='2949570'>Well,</span>
  <span m='2949720'>it</span> <span m='2949780'>depends</span> <span m='2950200'>what</span>
  <span m='2950350'>these</span> <span m='2950530'>trajectory</span> <span m='2951010'>functions</span>
  <span m='2951400'>are</span> <span m='2951490'>like.</span> <span m='2951820'>If</span>
  <span m='2953080'>it's</span> <span m='2953200'>algebraic,</span> <span m='2953920'>then</span>
  <span m='2954100'>this</span> <span m='2954250'>is</span> <span m='2954310'>just</span>
  <span m='2954490'>a</span> <span m='2954550'>polynomial</span> <span m='2955150'>thing.</span>
  <span m='2956080'>You</span> <span m='2956200'>can</span> <span m='2956350'>do</span>
  <span m='2956500'>it</span> <span m='2956850'>in</span> <span m='2957000'>bounded</span>
  <span m='2957140'>degree.</span> <span m='2957460'>You</span> <span m='2957520'>can</span>
  <span m='2957640'>do</span> <span m='2957760'>it</span> <span m='2957820'>in</span>
  <span m='2957880'>constant</span> <span m='2958240'>time.</span> <span m='2959440'>That's</span>
  <span m='2959680'>our</span> <span m='2959800'>model.</span> </p><p><span m='2961870'>OK,</span>
  <span m='2962140'>so</span> <span m='2962260'>you</span> <span m='2962320'>put</span>
  <span m='2962500'>them</span> <span m='2962650'>into</span> <span m='2962830'>a</span>
  <span m='2962860'>priority</span> <span m='2963210'>queue.</span> <span m='2964690'>Do</span>
  <span m='2964840'>this</span> <span m='2965050'>advance.</span> <span m='2965830'>And</span>
  <span m='2965920'>now,</span> <span m='2966110'>the</span> <span m='2966160'>question</span>
  <span m='2966490'>is,</span> <span m='2966580'>how</span> <span m='2966790'>do</span>
  <span m='2966880'>you</span> <span m='2967060'>process</span> <span m='2967540'>an</span>
  <span m='2967660'>event?</span> <span m='2969130'>When</span> <span m='2969640'>one</span>
  <span m='2969850'>of</span> <span m='2969910'>these</span> <span m='2970060'>things</span>
  <span m='2970270'>happens,</span> <span m='2970840'>you're</span> <span m='2971590'>about</span>
  <span m='2971890'>to</span> <span m='2971980'>transition</span> <span m='2972550'>to</span>
  <span m='2972670'>x i</span> <span m='2973090'>being</span> <span m='2973300'>bigger</span>
  <span m='2973540'>than</span> <span m='2973690'>x i</span> <span m='2973990'>plus</span>
  <span m='2974230'>one.</span> <span m='2974830'>What</span> <span m='2975040'>do</span>
  <span m='2975130'>you</span> <span m='2975250'>do?</span> </p><p><span m='2980570'>So</span>
  <span m='2980720'>that's</span> <span m='2980990'>the</span> <span m='2981080'>real</span>
  <span m='2981410'>heart</span> <span m='2981620'>of</span> <span m='2981710'>the</span>
  <span m='2981770'>data</span> <span m='2981980'>structure.</span> <span m='2989800'>Although,</span>
  <span m='2990100'>really,</span> <span m='2990460'>the</span> <span m='2990610'>heart</span>
  <span m='2990940'>of</span> <span m='2991150'>a</span> <span m='2991400'>kinetic</span>
  <span m='2991720'>data</span> <span m='2991930'>structure</span> <span m='2992260'>is</span>
  <span m='2992500'>the</span> <span m='2992650'>choice</span> <span m='2993100'>of</span>
  <span m='2993220'>certificates.</span> <span m='2995080'>If</span> <span m='2995230'>you</span>
  <span m='2995560'>choose</span> <span m='2995830'>certificates</span> <span m='2997060'>well,</span>
  <span m='2998680'>then</span> <span m='2998830'>you're</span> <span m='2998920'>going</span>
  <span m='2999040'>to</span> <span m='2999100'>be</span> <span m='2999190'>efficient.</span>
  <span m='3000390'>We</span> <span m='3000450'>haven't</span> <span m='3000600'>defined</span>
  <span m='3000960'>efficient</span> <span m='3001290'>yet.</span> <span m='3001825'>We</span>
  <span m='3002090'>will.</span> <span m='3003520'>Otherwise,</span> <span m='3003860'>you're</span>
  <span m='3004200'>not</span> <span m='3004380'>going</span> <span m='3004500'>to</span>
  <span m='3004590'>be</span> <span m='3004680'>so</span> <span m='3004830'>fast.</span>
  <span m='3006708'>So</span> <span m='3009444'>it's</span> <span m='3009900'>all</span>
  <span m='3010110'>about</span> <span m='3010370'>using</span> <span m='3010710'>certificates</span>
  <span m='3011220'>right.</span> <span m='3011430'>The</span> <span m='3011520'>rest</span>
  <span m='3011790'>is</span> <span m='3011940'>kind</span> <span m='3012360'>of</span>
  <span m='3012500'>straightforward.</span> </p><p><span m='3016740'>So</span> <span
  m='3016850'>let's</span> <span m='3017030'>suppose</span> <span m='3017360'>that
  this</span> <span m='3017540'>certificate</span> <span m='3018080'>is</span> <span
  m='3018260'>about</span> <span m='3018590'>to</span> <span m='3018710'>fail.</span>
  <span m='3020600'>And</span> <span m='3020930'>we're</span> <span m='3021260'>guaranteed</span>
  <span m='3021890'>by</span> <span m='3022070'>this</span> <span m='3023090'>algorithm</span>
  <span m='3023690'>that</span> <span m='3024190'>it</span> <span m='3024320'>fails</span>
  <span m='3024840'>now.</span> <span m='3025220'>We</span> <span m='3025370'>have</span>
  <span m='3025460'>advanced</span> <span m='3025910'>to</span> <span m='3026030'>the</span>
  <span m='3026150'>time</span> <span m='3026480'>when</span> <span m='3026600'>it</span>
  <span m='3026720'>is</span> <span m='3026840'>about</span> <span m='3027110'>to</span>
  <span m='3027230'>fail.</span> <span m='3028180'>We</span> <span m='3028280'>process</span>
  <span m='3028640'>that</span> <span m='3028820'>event.</span> <span m='3030180'>So</span>
  <span m='3030470'>now</span> <span m='3030860'>is</span> <span m='3030980'>the</span>
  <span m='3031100'>time</span> <span m='3031400'>when</span> <span m='3031520'>these</span>
  <span m='3031640'>two</span> <span m='3031760'>things</span> <span m='3031970'>are</span>
  <span m='3032030'>equal.</span> <span m='3032360'>Right</span> <span m='3032570'>after</span>
  <span m='3032870'>now,</span> <span m='3033620'>we</span> <span m='3033740'>will</span>
  <span m='3033860'>get</span> <span m='3034010'>to</span> <span m='3034220'>greater</span>
  <span m='3034520'>than.</span> </p><p><span m='3036990'>So</span> <span m='3038300'>here's</span>
  <span m='3038480'>what</span> <span m='3038630'>I</span> <span m='3038690'>do.</span>
  <span m='3042710'>Swap</span> <span m='3043040'>them</span> <span m='3048040'>in
  the</span> <span m='3048190'>binary</span> <span m='3048490'>search</span> <span
  m='3048730'>tree.</span> <span m='3049000'>So</span> <span m='3049090'>right</span>
  <span m='3049300'>now,</span> <span m='3049720'>maybe</span> <span m='3052940'>just</span>
  <span m='3053140'>in</span> <span m='3053230'>general,</span> <span m='3053530'>it's</span>
  <span m='3053620'>going</span> <span m='3053740'>to</span> <span m='3053800'>look</span>
  <span m='3053890'>something</span> <span m='3054160'>like</span> <span m='3054310'>this.</span>
  <span m='3054490'>We</span> <span m='3054550'>have</span> <span m='3054670'>x</span>
  <span m='3054930'>i,</span> <span m='3055780'>x i plus</span> <span m='3056270'>one.</span>
  <span m='3056580'>Or it</span> <span m='3056740'>could</span> <span m='3056890'>be</span>
  <span m='3057040'>the</span> <span m='3057160'>reverse</span> <span m='3058000'>scenario,</span>
  <span m='3058570'>where</span> <span m='3059650'>x i</span> <span m='3060000'>plus</span>
  <span m='3060160'>one</span> <span m='3060310'>is</span> <span m='3060400'>a</span>
  <span m='3060460'>leaf,</span> <span m='3060700'>and</span> <span m='3060800'>x
  i</span> <span m='3061125'>is the</span> <span m='3061450'>predecessor.</span> <span
  m='3063070'>Right</span> <span m='3063310'>now,</span> <span m='3063600'>they're</span>
  <span m='3063790'>equal</span> <span m='3064510'>in</span> <span m='3064720'>value.</span>
  <span m='3066010'>So</span> <span m='3066120'>I'm</span> <span m='3066170'>just</span>
  <span m='3066280'>going</span> <span m='3066410'>to</span> <span m='3066470'>interchange</span>
  <span m='3067060'>them,</span> <span m='3068470'>move</span> <span m='3068740'>x</span>
  <span m='3068850'>i</span> <span m='3069130'>up</span> <span m='3069310'>here.</span>
  </p><p><span m='3072070'>So</span> <span m='3072820'>it's</span> <span m='3072940'>a</span>
  <span m='3072970'>little</span> <span m='3073180'>confusing.</span> <span m='3073720'>But</span>
  <span m='3073840'>this</span> <span m='3074190'>is x i</span> <span m='3074530'>plus</span>
  <span m='3074770'>one,</span> <span m='3075880'>and</span> <span m='3076060'>this</span>
  <span m='3076270'>is</span> <span m='3076460'>x i.</span> <span m='3077560'>Replace</span>
  <span m='3077950'>those.</span> <span m='3078400'>These</span> <span m='3078610'>are</span>
  <span m='3078670'>really</span> <span m='3078910'>pointers</span> <span m='3079450'>to</span>
  <span m='3080520'>the</span> <span m='3080620'>trajectories,</span> <span m='3082090'>however</span>
  <span m='3082390'>they're</span> <span m='3082510'>described.</span> <span m='3084070'>Interchange</span>
  <span m='3084580'>them.</span> <span m='3085000'>It's still</span> <span m='3085420'>valid</span>
  <span m='3085900'>as</span> <span m='3086050'>a</span> <span m='3086110'>binary</span>
  <span m='3086380'>search</span> <span m='3086620'>tree.</span> <span m='3086890'>Actually,</span>
  <span m='3087300'>this</span> <span m='3087490'>binary</span> <span m='3087690'>search</span>
  <span m='3087850'>tree</span> <span m='3088000'>never</span> <span m='3088270'>becomes</span>
  <span m='3088600'>invalid,</span> <span m='3088960'>because</span> <span m='3089110'>at</span>
  <span m='3089200'>this</span> <span m='3089380'>moment,</span> <span m='3089650'>they're</span>
  <span m='3089770'>equal.</span> <span m='3090550'>And</span> <span m='3090690'>after</span>
  <span m='3091090'>now,</span> <span m='3091930'>things</span> <span m='3092110'>will</span>
  <span m='3092200'>continue</span> <span m='3092590'>to</span> <span m='3092680'>be</span>
  <span m='3092830'>OK,</span> <span m='3093160'>because</span> <span m='3093780'>this</span>
  <span m='3093970'>guy</span> <span m='3094180'>will</span> <span m='3094270'>be</span>
  <span m='3094420'>bigger</span> <span m='3094690'>than</span> <span m='3094840'>this</span>
  <span m='3095020'>one.</span> <span m='3096080'>That's</span> <span m='3096320'>the</span>
  <span m='3096400'>assumption.</span> </p><p><span m='3098530'>We</span> <span m='3098680'>just</span>
  <span m='3098800'>need</span> <span m='3098950'>to</span> <span m='3099070'>fix</span>
  <span m='3099490'>the</span> <span m='3099730'>certificates.</span> <span m='3100360'>Fixing</span>
  <span m='3100690'>the</span> <span m='3100750'>data</span> <span m='3100930'>structure</span>
  <span m='3101290'>was</span> <span m='3101500'>pretty</span> <span m='3101740'>trivial--</span>
  <span m='3102160'>constant</span> <span m='3102460'>time.</span> <span m='3104000'>So</span>
  <span m='3104290'>what</span> <span m='3104440'>certificates</span> <span m='3104950'>do</span>
  <span m='3105100'>we</span> <span m='3105160'>need</span> <span m='3105280'>to</span>
  <span m='3105400'>do?</span> <span m='3107380'>We</span> <span m='3107530'>need</span>
  <span m='3107710'>to</span> <span m='3107890'>add</span> <span m='3108280'>this</span>
  <span m='3108460'>new</span> <span m='3108670'>certificate.</span> <span m='3109360'>I'm</span>
  <span m='3109420'>going</span> <span m='3109570'>to</span> <span m='3109630'>call</span>
  <span m='3109790'>it</span> <span m='3109850'>x i</span> <span m='3110230'>prime</span>
  <span m='3110580'>is</span> <span m='3111345'>less</span> <span m='3111760'>than
  or</span> <span m='3111890'>equal</span> <span m='3112090'>to</span> <span m='3112190'>x
  i</span> <span m='3112570'>plus</span> <span m='3112810'>one</span> <span m='3113080'>prime.</span>
  <span m='3114260'>So</span> <span m='3114280'>this</span> <span m='3114490'>is</span>
  <span m='3114610'>actually</span> <span m='3115990'>x i</span> <span m='3116320'>plus</span>
  <span m='3116680'>one,</span> <span m='3117190'>formerly</span> <span m='3117700'>known</span>
  <span m='3118030'>as</span> <span m='3118200'>x i</span> <span m='3118400'>plus</span>
  <span m='3118730'>one,</span> <span m='3118930'>formerly</span> <span m='3119380'>known</span>
  <span m='3119530'>as</span> <span m='3119620'>x i.</span> <span m='3120120'>But</span>
  <span m='3120280'>it'd</span> <span m='3120730'>be</span> <span m='3120820'>really</span>
  <span m='3121060'>confusing.</span> </p><p><span m='3122860'>So I'm going to</span>
  <span m='3123010'>use</span> <span m='3123160'>the</span> <span m='3123250'>primes</span>
  <span m='3123670'>to</span> <span m='3123790'>be</span> <span m='3124030'>the</span>
  <span m='3124180'>new</span> <span m='3124510'>data</span> <span m='3124750'>structure.</span>
  <span m='3126010'>Because</span> <span m='3126190'>this</span> <span m='3126340'>is</span>
  <span m='3126430'>always</span> <span m='3126700'>the</span> <span m='3126760'>kind</span>
  <span m='3126910'>of</span> <span m='3127000'>certificate</span> <span m='3127480'>we</span>
  <span m='3127630'>want.</span> <span m='3128840'>We</span> <span m='3128950'>also</span>
  <span m='3129220'>need</span> <span m='3129430'>to</span> <span m='3129820'>update</span>
  <span m='3132610'>certificates.</span> </p><p><span m='3134740'>So</span> <span
  m='3135040'>there</span> <span m='3135160'>used</span> <span m='3135430'>to</span>
  <span m='3135580'>be</span> <span m='3135970'>an</span> <span m='3136090'>x i</span>
  <span m='3136690'>minus</span> <span m='3136945'>one</span> <span m='3137200'>less</span>
  <span m='3137485'>than</span> <span m='3137770'>or equal</span> <span m='3138040'>to</span>
  <span m='3138130'>x i.</span> <span m='3139270'>We</span> <span m='3139390'>want</span>
  <span m='3139540'>to</span> <span m='3139630'>turn</span> <span m='3139870'>that</span>
  <span m='3140020'>into</span> <span m='3141130'>x i</span> <span m='3141520'>minus</span>
  <span m='3141850'>one</span> <span m='3142145'>less than</span> <span m='3142440'>or
  equal</span> <span m='3142660'>to</span> <span m='3142800'>x i</span> <span m='3143320'>prime.</span>
  <span m='3145340'>And</span> <span m='3145480'>we</span> <span m='3145570'>used</span>
  <span m='3145750'>to</span> <span m='3145870'>have</span> <span m='3146140'>an</span>
  <span m='3146260'>x i</span> <span m='3146635'>less than</span> <span m='3147010'>or
  equal</span> <span m='3147280'>to</span> <span m='3147400'>x i</span> <span m='3147750'>plus
  one.</span> <span m='3149230'>We</span> <span m='3149350'>want</span> <span m='3149500'>to</span>
  <span m='3149560'>turn</span> <span m='3149770'>that</span> <span m='3149920'>into</span>
  <span m='3151060'>x i</span> <span m='3151510'>prime</span> <span m='3152260'>less</span>
  <span m='3152530'>than or</span> <span m='3152800'>equal--</span> <span m='3153070'>oh,</span>
  <span m='3153220'>that one,</span> <span m='3153420'>we</span> <span m='3153520'>already</span>
  <span m='3153730'>did.</span> <span m='3154485'>Sorry.</span> </p><p><span m='3154940'>So</span>
  <span m='3154990'>I</span> <span m='3155110'>want</span> <span m='3155290'>x i</span>
  <span m='3155990'>plus</span> <span m='3156710'>one</span> <span m='3157140'>to</span>
  <span m='3157550'>x i</span> <span m='3157960'>plus</span> <span m='3158260'>two.</span>
  <span m='3159550'>And</span> <span m='3159760'>I</span> <span m='3159820'>want</span>
  <span m='3159970'>to</span> <span m='3160030'>do,</span> <span m='3160280'>now,</span>
  <span m='3160670'>x i</span> <span m='3160990'>plus</span> <span m='3161230'>one</span>
  <span m='3161440'>prime</span> <span m='3161980'>to</span> <span m='3162250'>x i</span>
  <span m='3163210'>plus</span> <span m='3163480'>two.</span> <span m='3165000'>OK,</span>
  <span m='3165190'>basically,</span> <span m='3165490'>wherever</span> <span m='3165840'>the</span>
  <span m='3166000'>primes</span> <span m='3166390'>happen,</span> <span m='3166750'>which</span>
  <span m='3166930'>is</span> <span m='3167020'>x i</span> <span m='3167170'>and</span>
  <span m='3167340'>x i</span> <span m='3167680'>plus</span> <span m='3167920'>one--</span>
  <span m='3168580'>whatever</span> <span m='3168880'>certificates</span> <span m='3169450'>they're</span>
  <span m='3169540'>involved</span> <span m='3169990'>in,</span> <span m='3170230'>you</span>
  <span m='3170350'>have</span> <span m='3170530'>to</span> <span m='3170650'>update</span>
  <span m='3171040'>them--</span> <span m='3171730'>meaning,</span> <span m='3172060'>rip</span>
  <span m='3172270'>out</span> <span m='3172450'>the</span> <span m='3172540'>old</span>
  <span m='3172690'>one,</span> <span m='3172900'>put</span> <span m='3173080'>in</span>
  <span m='3173170'>the</span> <span m='3173260'>new</span> <span m='3173410'>one.</span>
  </p><p><span m='3175120'>And</span> <span m='3175480'>the</span> <span m='3175690'>main</span>
  <span m='3175990'>issue</span> <span m='3176260'>here</span> <span m='3176500'>is</span>
  <span m='3176650'>that</span> <span m='3176740'>you</span> <span m='3176860'>have</span>
  <span m='3176950'>to</span> <span m='3177070'>maintain</span> <span m='3177460'>the</span>
  <span m='3177550'>priority</span> <span m='3177970'>queue.</span> <span m='3178940'>So</span>
  <span m='3179020'>you've</span> <span m='3179200'>got</span> <span m='3179380'>to</span>
  <span m='3179590'>take</span> <span m='3179830'>them</span> <span m='3179980'>out</span>
  <span m='3180100'>of</span> <span m='3180160'>the</span> <span m='3180220'>priority</span>
  <span m='3180580'>queue,</span> <span m='3181690'>recompute</span> <span m='3182320'>their</span>
  <span m='3182470'>failure</span> <span m='3182830'>times,</span> <span m='3183880'>put</span>
  <span m='3184030'>them</span> <span m='3184180'>back</span> <span m='3184420'>in</span>
  <span m='3184480'>the</span> <span m='3184570'>priority</span> <span m='3184960'>queue</span>
  <span m='3185260'>with</span> <span m='3185380'>that</span> <span m='3185800'>failure</span>
  <span m='3186100'>time.</span> <span m='3187550'>But</span> <span m='3187840'>the</span>
  <span m='3187990'>point</span> <span m='3188200'>is,</span> <span m='3188350'>this</span>
  <span m='3188530'>is</span> <span m='3188920'>a</span> <span m='3188980'>constant</span>
  <span m='3189430'>number</span> <span m='3190090'>of</span> <span m='3190240'>updates.</span>
  </p><p><span m='3192010'>In</span> <span m='3192160'>general,</span> <span m='3192700'>pretty</span>
  <span m='3192970'>much,</span> <span m='3193210'>as</span> <span m='3193330'>long</span>
  <span m='3193630'>as</span> <span m='3193810'>the</span> <span m='3194680'>things</span>
  <span m='3195010'>you're</span> <span m='3195310'>messing</span> <span m='3195760'>with--</span>
  <span m='3196240'>the</span> <span m='3196360'>items</span> <span m='3196660'>you're</span>
  <span m='3196780'>changing--</span> <span m='3197980'>are</span> <span m='3198100'>involved</span>
  <span m='3198670'>in</span> <span m='3198880'>a</span> <span m='3198940'>small</span>
  <span m='3199330'>number</span> <span m='3199600'>of</span> <span m='3199660'>certificates</span>
  <span m='3200260'>each,</span> <span m='3201130'>then</span> <span m='3201280'>this</span>
  <span m='3201430'>will</span> <span m='3201550'>be</span> <span m='3202270'>cheap.</span>
  <span m='3203530'>I'm</span> <span m='3203650'>writing</span> <span m='3203860'>this</span>
  <span m='3203980'>explicitly.</span> <span m='3204580'>But</span> <span m='3204730'>in</span>
  <span m='3204820'>general,</span> <span m='3205180'>it's just,</span> <span m='3205510'>update</span>
  <span m='3205870'>whatever</span> <span m='3206170'>certificates</span> <span m='3206680'>those</span>
  <span m='3206860'>points</span> <span m='3207130'>were</span> <span m='3207190'>involved</span>
  <span m='3207550'>in.</span> <span m='3208330'>The</span> <span m='3208420'>issue</span>
  <span m='3208600'>is</span> <span m='3208720'>how</span> <span m='3208900'>many</span>
  <span m='3209080'>things</span> <span m='3209290'>you</span> <span m='3209380'>change,</span>
  <span m='3210400'>and</span> <span m='3210700'>how</span> <span m='3210910'>many</span>
  <span m='3211180'>certificates</span> <span m='3211810'>each</span> <span m='3212020'>of</span>
  <span m='3212080'>those</span> <span m='3212290'>things</span> <span m='3212620'>is</span>
  <span m='3213050'>in.</span> </p><p><span m='3213310'>In</span> <span m='3213790'>this</span>
  <span m='3213940'>case,</span> <span m='3214610'>changing</span> <span m='3214840'>a
  constant</span> <span m='3215140'>number</span> <span m='3215320'>of</span> <span
  m='3215380'>things--</span> <span m='3215680'>each</span> <span m='3215890'>of</span>
  <span m='3215950'>them</span> <span m='3216070'>is</span> <span m='3216190'>in</span>
  <span m='3216340'>a</span> <span m='3216400'>constant</span> <span m='3216760'>number</span>
  <span m='3216930'>of</span> <span m='3216970'>certificates.</span> <span m='3218020'>So</span>
  <span m='3218200'>it's</span> <span m='3219220'>not</span> <span m='3219370'>constant</span>
  <span m='3219760'>time,</span> <span m='3220090'>but a</span> <span m='3220210'>constant</span>
  <span m='3220600'>number</span> <span m='3220810'>of</span> <span m='3220900'>calls</span>
  <span m='3221260'>to</span> <span m='3221410'>priority</span> <span m='3221770'>queue</span>
  <span m='3221950'>updates--</span> <span m='3222280'>so</span> <span m='3222760'>log</span>
  <span m='3222970'>n</span> <span m='3223210'>time.</span> </p><p><span m='3225655'>AUDIENCE:</span>
  <span m='3225877'>Question.</span> </p><p><span m='3226550'>ERIK DEMAINE:</span>
  <span m='3226620'>Yeah,</span> <span m='3227140'>question.</span> </p><p><span m='3227540'>AUDIENCE:</span>
  <span m='3227775'>So</span> <span m='3228480'>but how</span> <span m='3228950'>do
  you find</span> <span m='3229890'>the</span> <span m='3230360'>things that you just</span>
  <span m='3230830'>changed</span> <span m='3231300'>in the</span> <span m='3231770'>priority</span>
  <span m='3232240'>queue</span> <span m='3232710'>of the failure</span> <span m='3233180'>times.</span>
  </p><p><span m='3234190'>ERIK DEMAINE:</span> <span m='3234265'>How</span> <span
  m='3234340'>do</span> <span m='3234400'>you</span> <span m='3234490'>find</span>
  <span m='3234760'>them</span> <span m='3234910'>in</span> <span m='3235060'>the</span>
  <span m='3235150'>priority</span> <span m='3235540'>queue?</span> <span m='3236440'>How</span>
  <span m='3236590'>do</span> <span m='3236650'>you</span> <span m='3236770'>find</span>
  <span m='3237280'>these</span> <span m='3237460'>x i's</span> <span m='3237910'>and
  x i</span> <span m='3238190'>plus</span> <span m='3238420'>ones?</span> <span m='3241240'>Every</span>
  <span m='3241480'>point</span> <span m='3241720'>knows</span> <span m='3242020'>what</span>
  <span m='3242170'>certificates</span> <span m='3242730'>it's</span> <span m='3242860'>in,</span>
  <span m='3243040'>meaning</span> <span m='3243310'>it has</span> <span m='3243490'>a</span>
  <span m='3243550'>point</span> <span m='3243940'>or two--</span> <span m='3244180'>a</span>
  <span m='3244210'>list</span> <span m='3244450'>of</span> <span m='3244540'>certificates</span>
  <span m='3244810'>it's in.</span> <span m='3245200'>There's</span> <span m='3245320'>only</span>
  <span m='3245530'>two</span> <span m='3245680'>of</span> <span m='3245740'>them.</span>
  <span m='3246250'>And</span> <span m='3246400'>each</span> <span m='3246550'>certificate</span>
  <span m='3247060'>has</span> <span m='3247240'>a</span> <span m='3247300'>pointer</span>
  <span m='3247820'>into</span> <span m='3248200'>its</span> <span m='3248470'>existence</span>
  <span m='3248980'>in</span> <span m='3249080'>the</span> <span m='3249190'>priority</span>
  <span m='3249550'>queue.</span> <span m='3250010'>So</span> <span m='3250060'>then</span>
  <span m='3250210'>you</span> <span m='3250330'>know</span> <span m='3250540'>where</span>
  <span m='3250780'>it</span> <span m='3250870'>is</span> <span m='3251020'>in</span>
  <span m='3251080'>the</span> <span m='3251170'>priority</span> <span m='3251500'>queue</span>
  <span m='3251770'>and</span> <span m='3251860'>you</span> <span m='3251950'>can</span>
  <span m='3252100'>rip</span> <span m='3252280'>it</span> <span m='3252370'>out.</span>
  <span m='3253548'>Yeah.</span> <span m='3256020'>Lots</span> <span m='3256310'>of</span>
  <span m='3256370'>pointers</span> <span m='3256730'>and</span> <span m='3256820'>cross-linking.</span>
  <span m='3257909'>Yeah?</span> </p><p><span m='3259620'>AUDIENCE:</span> <span m='3259742'>So</span>
  <span m='3262799'>in</span> <span m='3263288'>something that's</span> <span m='3263777'>pseudo</span>
  <span m='3264266'>algebraic,</span> <span m='3264755'>any</span> <span m='3265244'>certificate</span>
  <span m='3265733'>of</span> <span m='3266222'>interest</span> <span m='3266711'>changes</span>
  <span m='3267200'>o of one</span> <span m='3267689'>times.</span> <span m='3268667'>But
  here,</span> <span m='3269645'>there's</span> <span m='3271112'>o of n</span> <span
  m='3271601'>squared--</span> <span m='3272090'>even though</span> <span m='3272579'>we're
  only taking</span> <span m='3273068'>n certificates</span> <span m='3273557'>at
  a time,</span> <span m='3274046'>there's</span> <span m='3274535'>o</span> <span
  m='3275024'>of</span> <span m='3275513'>n squared possible</span> <span m='3276002'>certificates
  in</span> <span m='3276491'>each of them.</span> </p><p><span m='3277970'>ERIK DEMAINE:</span>
  <span m='3278075'>You're</span> <span m='3278180'>asking</span> <span m='3278480'>about</span>
  <span m='3278630'>efficiency,</span> <span m='3279320'>which</span> <span m='3280060'>we'll</span>
  <span m='3280220'>go</span> <span m='3280400'>to</span> <span m='3280630'>now.</span>
  <span m='3281780'>This</span> <span m='3281990'>looks</span> <span m='3282380'>disconcerting,</span>
  <span m='3283160'>because</span> <span m='3286290'>even</span> <span m='3286540'>though</span>
  <span m='3286770'>pseudo</span> <span m='3287180'>algebraic</span> <span m='3287770'>gives
  us</span> <span m='3287880'>that</span> <span m='3288920'>each</span> <span m='3289130'>certificate</span>
  <span m='3289760'>won't</span> <span m='3289970'>change</span> <span m='3290300'>too</span>
  <span m='3290420'>many</span> <span m='3290630'>times,</span> <span m='3291450'>there</span>
  <span m='3291580'>are</span> <span m='3291720'>quadratic</span> <span m='3292280'>number</span>
  <span m='3292520'>of</span> <span m='3292580'>potential</span> <span m='3293120'>certificates.</span>
  <span m='3293750'>They</span> <span m='3293870'>could</span> <span m='3294140'>all</span>
  <span m='3294410'>become</span> <span m='3294770'>relevant.</span> <span m='3295820'>And</span>
  <span m='3295970'>indeed,</span> <span m='3296420'>that</span> <span m='3296600'>is</span>
  <span m='3296720'>the</span> <span m='3296810'>case,</span> <span m='3297290'>if</span>
  <span m='3297500'>you</span> <span m='3304220'>have</span> <span m='3304400'>these</span>
  <span m='3304640'>points,</span> <span m='3305450'>spaced</span> <span m='3305900'>out</span>
  <span m='3306020'>a</span> <span m='3306090'>lot,</span> <span m='3307130'>and then</span>
  <span m='3307310'>you</span> <span m='3307400'>have</span> <span m='3307580'>these</span>
  <span m='3307820'>points,</span> <span m='3308600'>spaced</span> <span m='3309050'>out</span>
  <span m='3309200'>a</span> <span m='3309290'>little--</span> <span m='3310520'>four</span>
  <span m='3310700'>and</span> <span m='3310820'>four.</span> </p><p><span m='3312110'>And</span>
  <span m='3312500'>these</span> <span m='3312830'>guys</span> <span m='3313130'>are</span>
  <span m='3313220'>all</span> <span m='3313340'>moving</span> <span m='3314360'>constant</span>
  <span m='3314780'>velocity</span> <span m='3315290'>this</span> <span m='3315500'>way.</span>
  <span m='3316910'>And</span> <span m='3317120'>the</span> <span m='3317240'>white</span>
  <span m='3317510'>guys</span> <span m='3318050'>are</span> <span m='3318350'>stationary.</span>
  <span m='3320240'>Then</span> <span m='3321380'>what</span> <span m='3321620'>happens?</span>
  <span m='3322180'>Well,</span> <span m='3322320'>there's</span> <span m='3323560'>event,</span>
  <span m='3323890'>event,</span> <span m='3324190'>event,</span> <span m='3324440'>event,</span>
  <span m='3324760'>event,</span> <span m='3325760'>event,</span> <span m='3326000'>event,</span>
  <span m='3326300'>event,</span> <span m='3326570'>event,</span> <span m='3326630'>event,</span>
  <span m='3326870'>event,</span> <span m='3327470'>event,</span> <span m='3327710'>event,</span>
  <span m='3327980'>event,</span> <span m='3328250'>event,</span> <span m='3328520'>event,</span>
  <span m='3329090'>event,</span> <span m='3329300'>event,</span> <span m='3329540'>event,</span>
  <span m='3329770'>event,</span> <span m='3329980'>event.</span> <span m='3331160'>You're</span>
  <span m='3331280'>going</span> <span m='3331430'>to</span> <span m='3331490'>get</span>
  <span m='3332210'>n</span> <span m='3332570'>squared</span> <span m='3334190'>events.</span>
  <span m='3334730'>You</span> <span m='3335000'>get,</span> <span m='3335180'>like,</span>
  <span m='3335410'>n over</span> <span m='3335600'>two</span> <span m='3336650'>each</span>
  <span m='3336830'>time</span> <span m='3337040'>you</span> <span m='3337130'>cross</span>
  <span m='3338040'>a</span> <span m='3338120'>white</span> <span m='3338300'>point.</span>
  </p><p><span m='3341040'>I</span> <span m='3341130'>call</span> <span m='3341400'>this</span>
  <span m='3341730'>OK.</span> <span m='3343440'>Why?</span> <span m='3344880'>Because</span>
  <span m='3345850'>of</span> <span m='3345990'>efficiency.</span> </p><p><span m='3349770'>The</span>
  <span m='3349890'>claim</span> <span m='3350220'>is,</span> <span m='3350400'>this</span>
  <span m='3350640'>is</span> <span m='3350700'>sort</span> <span m='3350910'>of</span>
  <span m='3351000'>the</span> <span m='3351090'>best</span> <span m='3351360'>you</span>
  <span m='3351450'>could</span> <span m='3351600'>hope</span> <span m='3351750'>to</span>
  <span m='3351870'>do.</span> <span m='3352440'>So</span> <span m='3352560'>in</span>
  <span m='3352650'>that</span> <span m='3352800'>sense,</span> <span m='3353170'>it's</span>
  <span m='3353340'>as</span> <span m='3353700'>good</span> <span m='3353940'>as</span>
  <span m='3354090'>you</span> <span m='3354240'>can</span> <span m='3354360'>hope</span>
  <span m='3354510'>to</span> <span m='3354600'>do.</span> <span m='3355260'>If</span>
  <span m='3355440'>you</span> <span m='3355590'>want</span> <span m='3355800'>to</span>
  <span m='3355890'>maintain</span> <span m='3357400'>predecessors--</span> <span
  m='3360050'>let's</span> <span m='3360420'>put</span> <span m='3360570'>it</span>
  <span m='3360660'>this</span> <span m='3360810'>way.</span> <span m='3361860'>If</span>
  <span m='3362100'>we</span> <span m='3362250'>need</span> <span m='3362490'>to</span>
  <span m='3362640'>know--</span> <span m='3365950'>"know"</span> <span m='3366460'>is</span>
  <span m='3366690'>a</span> <span m='3367020'>sort</span> <span m='3367260'>of</span>
  <span m='3367320'>vague</span> <span m='3367620'>thing--</span> <span m='3368700'>the</span>
  <span m='3368850'>sorted</span> <span m='3369270'>order</span> <span m='3369600'>of</span>
  <span m='3369690'>the</span> <span m='3369810'>points,</span> <span m='3380450'>then</span>
  <span m='3381350'>you</span> <span m='3381660'>need</span> <span m='3382940'>an</span>
  <span m='3383060'>event--</span> <span m='3384300'>if</span> <span m='3384650'>we're
  going to</span> <span m='3384740'>keep</span> <span m='3385280'>a</span> <span m='3385340'>data</span>
  <span m='3385550'>structure</span> <span m='3385950'>that is</span> <span m='3386120'>always</span>
  <span m='3386450'>accurate</span> <span m='3386840'>now--</span> <span m='3387230'>so</span>
  <span m='3387380'>this</span> <span m='3387560'>is</span> <span m='3387620'>sort</span>
  <span m='3387770'>of</span> <span m='3388010'>an</span> <span m='3388160'>assumption--</span>
  <span m='3390530'>then</span> <span m='3391160'>you</span> <span m='3391340'>need</span>
  <span m='3393920'>an</span> <span m='3394010'>event</span> <span m='3395090'>every</span>
  <span m='3395330'>time</span> <span m='3395900'>you</span> <span m='3396020'>have</span>
  <span m='3396170'>an</span> <span m='3396260'>order</span> <span m='3396470'>change.</span>
  <span m='3398336'>That's</span> <span m='3398810'>sort</span> <span m='3399110'>of</span>
  <span m='3399230'>a</span> <span m='3399290'>tautology.</span> <span m='3399920'>But</span>
  <span m='3401420'>it's</span> <span m='3401630'>a</span> <span m='3401780'>perspective.</span>
  </p><p><span m='3404150'>And</span> <span m='3404480'>what's</span> <span m='3404660'>happening</span>
  <span m='3405080'>here</span> <span m='3405410'>is</span> <span m='3405530'>that</span>
  <span m='3405650'>we</span> <span m='3405800'>have</span> <span m='3406010'>an</span>
  <span m='3406070'>event</span> <span m='3406550'>every</span> <span m='3406790'>time</span>
  <span m='3407360'>there's</span> <span m='3407540'>an</span> <span m='3407600'>order</span>
  <span m='3407810'>change.</span> <span m='3408620'>So</span> <span m='3409640'>sometimes,</span>
  <span m='3410350'>yeah,</span> <span m='3410450'>it's</span> <span m='3410690'>going</span>
  <span m='3410820'>to</span> <span m='3410930'>be</span> <span m='3411110'>bad.</span>
  <span m='3411550'>Worst</span> <span m='3411830'>case</span> <span m='3412220'>here</span>
  <span m='3412390'>is</span> <span m='3412490'>quadratic.</span> <span m='3414840'>You</span>
  <span m='3414860'>can</span> <span m='3415010'>actually</span> <span m='3415280'>prove</span>
  <span m='3416090'>for</span> <span m='3416480'>pseudo</span> <span m='3416750'>algebraic,</span>
  <span m='3418070'>it</span> <span m='3418220'>is</span> <span m='3418610'>order</span>
  <span m='3418940'>n</span> <span m='3419120'>squared</span> <span m='3419420'>events.</span>
  <span m='3420390'>So</span> <span m='3420410'>this</span> <span m='3420590'>was</span>
  <span m='3420830'>really</span> <span m='3421070'>a</span> <span m='3421130'>lower</span>
  <span m='3421430'>bound.</span> <span m='3424950'>But</span> <span m='3425030'>it</span>
  <span m='3425120'>is</span> <span m='3425330'>also</span> <span m='3426440'>order</span>
  <span m='3426680'>n</span> <span m='3426860'>squared</span> <span m='3428030'>all</span>
  <span m='3428240'>the</span> <span m='3428330'>time,</span> <span m='3428810'>because,</span>
  <span m='3429830'>if</span> <span m='3429890'>you</span> <span m='3429950'>look</span>
  <span m='3430130'>at</span> <span m='3430190'>any</span> <span m='3430370'>pair</span>
  <span m='3430670'>of</span> <span m='3430760'>guys,</span> <span m='3431150'>they're</span>
  <span m='3431270'>only</span> <span m='3431450'>going</span> <span m='3431570'>to</span>
  <span m='3431630'>change</span> <span m='3431930'>a</span> <span m='3431990'>constant</span>
  <span m='3432380'>number</span> <span m='3432560'>of</span> <span m='3432650'>times</span>
  <span m='3432990'>who's</span> <span m='3433220'>above</span> <span m='3433570'>whom,</span>
  <span m='3434090'>for</span> <span m='3434280'>pseudo</span> <span m='3434480'>algebraic,</span>
  <span m='3435740'>if</span> <span m='3435920'>there</span> <span m='3436070'>are</span>
  <span m='3436130'>no</span> <span m='3436310'>change</span> <span m='3436760'>events.</span>
  </p><p><span m='3438040'>So</span> <span m='3438620'>for</span> <span m='3438740'>efficiency,</span>
  <span m='3440090'>because</span> <span m='3440300'>it's</span> <span m='3440420'>really</span>
  <span m='3440720'>hard</span> <span m='3440870'>to</span> <span m='3440960'>analyze</span>
  <span m='3441230'>if</span> <span m='3441500'>points</span> <span m='3441830'>are</span>
  <span m='3441920'>changing</span> <span m='3442430'>their</span> <span m='3443150'>trajectories</span>
  <span m='3443660'>all</span> <span m='3443780'>the</span> <span m='3443870'>time,</span>
  <span m='3444290'>assume</span> <span m='3444800'>there's</span> <span m='3444980'>no</span>
  <span m='3445190'>changes.</span> <span m='3446150'>We</span> <span m='3446300'>basically</span>
  <span m='3446630'>just</span> <span m='3446810'>advance</span> <span m='3447290'>to</span>
  <span m='3447440'>infinity.</span> <span m='3448380'>How</span> <span m='3448490'>much</span>
  <span m='3448730'>could</span> <span m='3448910'>that</span> <span m='3449120'>possibly</span>
  <span m='3449630'>cost?</span> <span m='3450080'>That's</span> <span m='3450320'>how</span>
  <span m='3450800'>kinetic</span> <span m='3451130'>people</span> <span m='3451400'>like</span>
  <span m='3451580'>to</span> <span m='3451640'>analyze</span> <span m='3452030'>things.</span>
  </p><p><span m='3453060'>And</span> <span m='3453200'>for</span> <span m='3453320'>this</span>
  <span m='3453500'>problem,</span> <span m='3454250'>for</span> <span m='3454400'>maintaining</span>
  <span m='3454790'>sorted</span> <span m='3455060'>order</span> <span m='3455270'>at</span>
  <span m='3455330'>all</span> <span m='3455450'>times,</span> <span m='3456560'>the</span>
  <span m='3456680'>worst</span> <span m='3456950'>case</span> <span m='3457160'>answer</span>
  <span m='3457430'>is</span> <span m='3457610'>theta</span> <span m='3457880'>n</span>
  <span m='3458030'>squared.</span> <span m='3458900'>This</span> <span m='3459080'>data</span>
  <span m='3459290'>structure</span> <span m='3459650'>achieves</span> <span m='3460100'>theta</span>
  <span m='3460340'>n</span> <span m='3460460'>squared,</span> <span m='3460800'>so</span>
  <span m='3460940'>we</span> <span m='3461060'>consider</span> <span m='3461450'>it</span>
  <span m='3461540'>worst</span> <span m='3461750'>case</span> <span m='3461960'>optimal,</span>
  <span m='3463130'>in</span> <span m='3463280'>this</span> <span m='3463730'>weird</span>
  <span m='3463970'>sense.</span> </p><p><span m='3465000'>OK,</span> <span m='3465140'>this</span>
  <span m='3465350'>is</span> <span m='3465560'>if</span> <span m='3465860'>you</span>
  <span m='3466040'>really</span> <span m='3466370'>want</span> <span m='3466520'>to</span>
  <span m='3466610'>maintain</span> <span m='3467010'>the</span> <span m='3467090'>sorted</span>
  <span m='3467390'>order.</span> <span m='3467600'>Now,</span> <span m='3467960'>we</span>
  <span m='3468110'>didn't</span> <span m='3468410'>say</span> <span m='3468860'>we</span>
  <span m='3468980'>wanted</span> <span m='3469220'>to</span> <span m='3469310'>maintain</span>
  <span m='3469670'>the</span> <span m='3469760'>sorted</span> <span m='3470030'>order.</span>
  <span m='3470240'>We</span> <span m='3470390'>said</span> <span m='3470600'>we</span>
  <span m='3470720'>want</span> <span m='3470900'>to</span> <span m='3470960'>maintain</span>
  <span m='3471380'>a</span> <span m='3471440'>predecessor</span> <span m='3472070'>data</span>
  <span m='3472250'>structure.</span> <span m='3473570'>But it</span> <span m='3473930'>feels</span>
  <span m='3474380'>kind</span> <span m='3474710'>of</span> <span m='3474770'>like</span>
  <span m='3475010'>those</span> <span m='3475280'>are</span> <span m='3475400'>the</span>
  <span m='3475520'>same</span> <span m='3475790'>thing,</span> <span m='3476090'>maybe.</span>
  <span m='3477770'>I</span> <span m='3477800'>don't</span> <span m='3477920'>know</span>
  <span m='3478010'>if</span> <span m='3478070'>there's</span> <span m='3478250'>a</span>
  <span m='3478310'>formal</span> <span m='3478640'>sense</span> <span m='3478970'>in</span>
  <span m='3479060'>which</span> <span m='3479270'>this</span> <span m='3479450'>is</span>
  <span m='3479540'>the</span> <span m='3479630'>case.</span> </p><p><span m='3480470'>And</span>
  <span m='3480620'>efficiency,</span> <span m='3481130'>in</span> <span m='3481220'>general,</span>
  <span m='3481580'>is</span> <span m='3482300'>the</span> <span m='3482480'>vaguest</span>
  <span m='3482960'>part</span> <span m='3483730'>of</span> <span m='3484310'>kinetic.</span>
  <span m='3484670'>And</span> <span m='3484760'>for</span> <span m='3484870'>each</span>
  <span m='3485060'>problem,</span> <span m='3485360'>you</span> <span m='3485450'>have</span>
  <span m='3485540'>to</span> <span m='3485720'>think</span> <span m='3485960'>hard</span>
  <span m='3487160'>to</span> <span m='3487280'>understand,</span> <span m='3487700'>what</span>
  <span m='3487880'>does</span> <span m='3488000'>efficient</span> <span m='3488360'>mean</span>
  <span m='3488640'>for</span> <span m='3488780'>this</span> <span m='3488930'>problem?</span>
  <span m='3492050'>But</span> <span m='3493100'>maybe</span> <span m='3493490'>don't</span>
  <span m='3493670'>even</span> <span m='3493850'>worry</span> <span m='3494030'>about</span>
  <span m='3494180'>efficiency--</span> <span m='3494700'>what</span> <span m='3494870'>does</span>
  <span m='3495020'>a</span> <span m='3495080'>lower</span> <span m='3495320'>bound</span>
  <span m='3495560'>mean--</span> <span m='3496480'>but</span> <span m='3496640'>bottom</span>
  <span m='3496970'>line</span> <span m='3497180'>is--</span> <span m='3497450'>worst</span>
  <span m='3497720'>case,</span> <span m='3498110'>n</span> <span m='3498260'>squared</span>
  <span m='3498500'>events,</span> <span m='3499010'>if</span> <span m='3499130'>there</span>
  <span m='3499280'>are</span> <span m='3499310'>no</span> <span m='3500230'>change</span>
  <span m='3501040'>operations.</span> </p><p><span m='3502280'>So</span> <span m='3502400'>you</span>
  <span m='3502490'>can</span> <span m='3502610'>think</span> <span m='3502790'>of</span>
  <span m='3502910'>the</span> <span m='3503330'>running</span> <span m='3503780'>time,</span>
  <span m='3504200'>if</span> <span m='3504320'>you</span> <span m='3504410'>want,</span>
  <span m='3505120'>of</span> <span m='3505490'>jumping</span> <span m='3505790'>to</span>
  <span m='3505880'>infinity</span> <span m='3506300'>as</span> <span m='3506450'>order</span>
  <span m='3506750'>n</span> <span m='3506880'>squared</span> <span m='3507160'>in</span>
  <span m='3507230'>the</span> <span m='3507290'>worst</span> <span m='3507470'>case.</span>
  <span m='3508010'>That's</span> <span m='3508220'>how</span> <span m='3508400'>we</span>
  <span m='3509180'>analyze</span> <span m='3509600'>these</span> <span m='3509750'>things.</span>
  <span m='3510410'>There</span> <span m='3510500'>are</span> <span m='3510530'>other</span>
  <span m='3510680'>things</span> <span m='3510890'>we'd</span> <span m='3511010'>like</span>
  <span m='3511160'>to</span> <span m='3511250'>analyze.</span> <span m='3512610'>Efficiency</span>
  <span m='3513010'>is</span> <span m='3513110'>one</span> <span m='3513290'>of</span>
  <span m='3513350'>them.</span> </p><p><span m='3514650'>We</span> <span m='3514670'>have</span>
  <span m='3516800'>three</span> <span m='3517100'>others,</span> <span m='3518990'>which</span>
  <span m='3519170'>I</span> <span m='3519230'>sort</span> <span m='3519440'>of</span>
  <span m='3519530'>hinted</span> <span m='3519800'>at.</span> <span m='3520310'>There's</span>
  <span m='3520460'>responsiveness,</span> <span m='3522360'>which</span> <span m='3522500'>is</span>
  <span m='3523250'>time</span> <span m='3524930'>spent</span> <span m='3525500'>to</span>
  <span m='3525650'>do</span> <span m='3525770'>an</span> <span m='3525860'>event.</span>
  <span m='3526870'>So</span> <span m='3527060'>when</span> <span m='3527240'>a</span>
  <span m='3527270'>certificate</span> <span m='3527780'>is</span> <span m='3527870'>invalidated,</span>
  <span m='3528500'>how</span> <span m='3528620'>much</span> <span m='3528800'>time</span>
  <span m='3529040'>does</span> <span m='3529190'>it</span> <span m='3529280'>take</span>
  <span m='3529520'>to</span> <span m='3529610'>do</span> <span m='3529760'>that?</span>
  </p><p><span m='3531320'>There's</span> <span m='3531630'>locality,</span> <span
  m='3532310'>which</span> <span m='3532460'>is</span> <span m='3532550'>closely</span>
  <span m='3532910'>related.</span> <span m='3534380'>This</span> <span m='3534620'>is</span>
  <span m='3534800'>the</span> <span m='3535130'>number</span> <span m='3536800'>of--</span>
  <span m='3537590'>oh, I</span> <span m='3538023'>see--</span> <span m='3538940'>number</span>
  <span m='3539270'>of</span> <span m='3543110'>certificates</span> <span m='3545510'>per</span>
  <span m='3547100'>data</span> <span m='3547400'>object.</span> <span m='3551560'>I</span>
  <span m='3551630'>said</span> <span m='3551900'>over</span> <span m='3552110'>here,</span>
  <span m='3552440'>this</span> <span m='3552620'>is</span> <span m='3552710'>good,</span>
  <span m='3553100'>because</span> <span m='3553580'>each</span> <span m='3554120'>item</span>
  <span m='3554570'>x i</span> <span m='3555000'>is</span> <span m='3555230'>only</span>
  <span m='3555440'>involved</span> <span m='3555770'>in</span> <span m='3555890'>a</span>
  <span m='3555950'>constant</span> <span m='3556310'>number</span> <span m='3556490'>of</span>
  <span m='3556550'>certificates.</span> <span m='3557370'>So</span> <span m='3557450'>we</span>
  <span m='3557520'>say</span> <span m='3557690'>the</span> <span m='3557780'>locality</span>
  <span m='3558470'>is</span> <span m='3558620'>constant--</span> <span m='3559802'>constant</span>
  <span m='3560140'>number</span> <span m='3560320'>of</span> <span m='3560390'>certificates</span>
  <span m='3560840'>per</span> <span m='3560990'>object.</span> </p><p><span m='3562310'>Usually,</span>
  <span m='3562640'>locality</span> <span m='3563150'>implies</span> <span m='3563540'>responsive.</span>
  <span m='3564410'>As</span> <span m='3564530'>long</span> <span m='3564740'>as</span>
  <span m='3564830'>you</span> <span m='3564920'>can</span> <span m='3565040'>update</span>
  <span m='3565340'>the</span> <span m='3565400'>data</span> <span m='3565610'>structure,</span>
  <span m='3566760'>you</span> <span m='3566780'>can</span> <span m='3566870'>also</span>
  <span m='3567170'>update</span> <span m='3567470'>the</span> <span m='3567560'>certificates</span>
  <span m='3568520'>in</span> <span m='3568700'>whatever--</span> <span m='3570010'>you</span>
  <span m='3570140'>pay</span> <span m='3570380'>a</span> <span m='3570440'>log</span>
  <span m='3570740'>factor,</span> <span m='3571070'>because</span> <span m='3571220'>you're</span>
  <span m='3571340'>updating</span> <span m='3571670'>a</span> <span m='3571730'>priority</span>
  <span m='3572150'>queue.</span> <span m='3573150'>But</span> <span m='3573380'>you</span>
  <span m='3573590'>can</span> <span m='3573980'>update</span> <span m='3574640'>all</span>
  <span m='3574820'>those</span> <span m='3575000'>events,</span> <span m='3576160'>or</span>
  <span m='3576770'>redo</span> <span m='3577190'>all</span> <span m='3577340'>the</span>
  <span m='3577430'>certificates</span> <span m='3578540'>in</span> <span m='3578680'>an</span>
  <span m='3578780'>event,</span> <span m='3579110'>provided</span> <span m='3579560'>you</span>
  <span m='3579660'>are</span> <span m='3579740'>local.</span> <span m='3580080'>So</span>
  <span m='3580250'>locally</span> <span m='3580640'>usually</span> <span m='3581000'>implies</span>
  <span m='3581570'>responsive,</span> <span m='3582860'>more</span> <span m='3583070'>or</span>
  <span m='3583100'>less.</span> </p><p><span m='3584410'>And</span> <span m='3584740'>then--</span>
  <span m='3585020'>what's the</span> <span m='3585140'>other</span> <span m='3585260'>one--</span>
  <span m='3585440'>compact.</span> <span m='3588530'>This</span> <span m='3588710'>is</span>
  <span m='3588860'>about</span> <span m='3589100'>space.</span> <span m='3590630'>And</span>
  <span m='3590720'>we</span> <span m='3590840'>just</span> <span m='3591050'>like</span>
  <span m='3591350'>the</span> <span m='3591590'>number</span> <span m='3591920'>of</span>
  <span m='3591980'>certificates</span> <span m='3592580'>to</span> <span m='3592730'>be</span>
  <span m='3592850'>small.</span> <span m='3595170'>So</span> <span m='3595310'>in</span>
  <span m='3595400'>this</span> <span m='3595550'>case,</span> <span m='3595940'>number
  of</span> <span m='3596180'>certificates</span> <span m='3596780'>is</span> <span
  m='3596900'>linear.</span> <span m='3598180'>That's</span> <span m='3598390'>that</span>
  <span m='3598610'>up</span> <span m='3598760'>here.</span> <span m='3599720'>So</span>
  <span m='3599960'>we</span> <span m='3600080'>consider</span> <span m='3600470'>the</span>
  <span m='3600710'>structure</span> <span m='3601040'>to</span> <span m='3601130'>be</span>
  <span m='3601580'>optimally</span> <span m='3602000'>compact.</span> <span m='3602540'>You</span>
  <span m='3602600'>need</span> <span m='3602840'>at</span> <span m='3602900'>least</span>
  <span m='3603170'>n.</span> </p><p><span m='3604850'>So</span> <span m='3605110'>in</span>
  <span m='3605500'>our</span> <span m='3605630'>case,</span> <span m='3605970'>we're</span>
  <span m='3606070'>getting</span> <span m='3606200'>order</span> <span m='3606410'>n</span>
  <span m='3606650'>here,</span> <span m='3607250'>order</span> <span m='3607670'>one</span>
  <span m='3608060'>here,</span> <span m='3608720'>order</span> <span m='3609050'>log</span>
  <span m='3609440'>n</span> <span m='3609710'>here.</span> <span m='3611240'>And</span>
  <span m='3611360'>efficiency</span> <span m='3612260'>I</span> <span m='3612380'>guess</span>
  <span m='3612760'>you'd</span> <span m='3612920'>call</span> <span m='3613340'>constant,</span>
  <span m='3615050'>kind</span> <span m='3615440'>of.</span> <span m='3617210'>Efficiency</span>
  <span m='3617810'>is</span> <span m='3617960'>the</span> <span m='3618110'>ratio</span>
  <span m='3618860'>of</span> <span m='3619760'>how</span> <span m='3620030'>many</span>
  <span m='3620330'>events</span> <span m='3620660'>you</span> <span m='3620780'>do</span>
  <span m='3621440'>divided</span> <span m='3621800'>by</span> <span m='3621950'>how</span>
  <span m='3622100'>many</span> <span m='3622250'>events</span> <span m='3622550'>you</span>
  <span m='3622640'>need</span> <span m='3622820'>to</span> <span m='3622940'>do.</span>
  <span m='3624950'>And</span> <span m='3625100'>here,</span> <span m='3625250'>it</span>
  <span m='3625340'>is</span> <span m='3625430'>optimal,</span> <span m='3627800'>in</span>
  <span m='3627950'>a</span> <span m='3628040'>certain</span> <span m='3628580'>vague</span>
  <span m='3628880'>sense.</span> <span m='3630590'>Sorry,</span> <span m='3631000'>that's</span>
  <span m='3631190'>a little</span> <span m='3631450'>unsatisfying.</span> <span m='3632000'>But</span>
  <span m='3634130'>it's</span> <span m='3634370'>unsatisfying.</span> <span m='3635240'>That's</span>
  <span m='3635720'>the</span> <span m='3635780'>literature</span> <span m='3637910'>for</span>
  <span m='3638150'>that</span> <span m='3638300'>problem.</span> </p><p><span m='3638720'>We're</span>
  <span m='3638840'>going</span> <span m='3638960'>to</span> <span m='3639050'>do</span>
  <span m='3639200'>another</span> <span m='3639470'>problem,</span> <span m='3639990'>which</span>
  <span m='3640100'>is</span> <span m='3640730'>more</span> <span m='3640940'>satisfying,</span>
  <span m='3641295'>I would</span> <span m='3641650'>say.</span> <span m='3645440'>And
  it</span> <span m='3645590'>kind</span> <span m='3645770'>of</span> <span m='3645860'>shows</span>
  <span m='3646130'>you</span> <span m='3646280'>why</span> <span m='3646790'>kinetic</span>
  <span m='3647360'>problems</span> <span m='3647750'>are</span> <span m='3648530'>pretty</span>
  <span m='3648710'>interesting.</span> <span m='3653220'>Data</span> <span m='3653600'>structures</span>
  <span m='3654030'>are</span> <span m='3654120'>often</span> <span m='3654390'>pretty</span>
  <span m='3654750'>darn</span> <span m='3655020'>simple,</span> <span m='3655950'>and</span>
  <span m='3656340'>the</span> <span m='3656520'>fun</span> <span m='3656790'>part</span>
  <span m='3657030'>is</span> <span m='3657240'>the</span> <span m='3657330'>analysis.</span>
  <span m='3659952'>Or,</span> <span m='3660450'>where</span> <span m='3660700'>it</span>
  <span m='3660970'>can</span> <span m='3661110'>get</span> <span m='3661230'>intricate</span>
  <span m='3661650'>is</span> <span m='3661830'>the</span> <span m='3661920'>analysis.</span>
  <span m='3664300'>So</span> <span m='3664980'>let's</span> <span m='3665250'>solve</span>
  <span m='3665740'>kinetic</span> <span m='3666040'>heap.</span> <span m='3666990'>Our</span>
  <span m='3667080'>goal</span> <span m='3667680'>is</span> <span m='3667830'>to</span>
  <span m='3667890'>be</span> <span m='3668010'>able</span> <span m='3668190'>to</span>
  <span m='3668410'>do</span> <span m='3669260'>find</span> <span m='3669720'>min.</span>
  </p><p><span m='3672490'>And</span> <span m='3673950'>yeah,</span> <span m='3675390'>there's</span>
  <span m='3675540'>also</span> <span m='3675780'>insertions</span> <span m='3676260'>and</span>
  <span m='3676350'>deletions.</span> <span m='3677730'>But</span> <span m='3677970'>I'm</span>
  <span m='3678090'>not</span> <span m='3678770'>going</span> <span m='3679020'>to</span>
  <span m='3679140'>think</span> <span m='3679320'>about</span> <span m='3679560'>them.</span>
  <span m='3679860'>Because</span> <span m='3680820'>they're</span> <span m='3680940'>not</span>
  <span m='3681060'>really</span> <span m='3681270'>that</span> <span m='3681420'>different.</span>
  <span m='3682190'>They're</span> <span m='3682500'>kind</span> <span m='3682650'>of</span>
  <span m='3682710'>like</span> <span m='3682890'>a</span> <span m='3682950'>change.</span>
  <span m='3683520'>Let's</span> <span m='3683670'>not</span> <span m='3683820'>worry</span>
  <span m='3683970'>about</span> <span m='3684210'>it.</span> </p><p><span m='3685120'>The</span>
  <span m='3685220'>goal</span> <span m='3685320'>is</span> <span m='3685440'>to</span>
  <span m='3685680'>maintain</span> <span m='3686070'>the</span> <span m='3686160'>minimum.</span>
  <span m='3687870'>Now,</span> <span m='3688230'>if</span> <span m='3688410'>you</span>
  <span m='3688500'>look</span> <span m='3688740'>at</span> <span m='3688890'>this</span>
  <span m='3689610'>point</span> <span m='3689850'>set</span> <span m='3690720'>and</span>
  <span m='3690930'>their</span> <span m='3691080'>velocities,</span> <span m='3692100'>how</span>
  <span m='3692310'>many</span> <span m='3692520'>times</span> <span m='3692810'>does</span>
  <span m='3692910'>the</span> <span m='3693000'>minimum</span> <span m='3693330'>change?</span>
  <span m='3695490'>Once.</span> <span m='3696900'>Initially,</span> <span m='3697220'>the</span>
  <span m='3697560'>min</span> <span m='3697740'>is</span> <span m='3697860'>this.</span>
  <span m='3698610'>Eventually,</span> <span m='3699000'>the min</span> <span m='3699270'>will</span>
  <span m='3699390'>be</span> <span m='3699510'>this--</span> <span m='3700380'>one</span>
  <span m='3700710'>change</span> <span m='3701220'>to</span> <span m='3701340'>the</span>
  <span m='3701430'>minimum.</span> </p><p><span m='3702810'>So</span> <span m='3702990'>this</span>
  <span m='3703200'>data</span> <span m='3703440'>structure</span> <span m='3704190'>is</span>
  <span m='3704340'>a</span> <span m='3704460'>bad</span> <span m='3704880'>way</span>
  <span m='3705030'>to</span> <span m='3705150'>maintain</span> <span m='3705510'>the</span>
  <span m='3705570'>minimum.</span> <span m='3705960'>Yes,</span> <span m='3706320'>it</span>
  <span m='3706440'>does</span> <span m='3706650'>maintain</span> <span m='3707010'>the</span>
  <span m='3707100'>minimum.</span> <span m='3707930'>But</span> <span m='3708060'>it's</span>
  <span m='3708150'>going</span> <span m='3708300'>to</span> <span m='3708360'>spend</span>
  <span m='3708600'>a</span> <span m='3708660'>quadratic</span> <span m='3709260'>number</span>
  <span m='3709500'>of</span> <span m='3709560'>events</span> <span m='3710130'>in</span>
  <span m='3710260'>this</span> <span m='3710340'>situation,</span> <span m='3710880'>where</span>
  <span m='3711060'>the</span> <span m='3711150'>min</span> <span m='3711480'>only</span>
  <span m='3711660'>changes</span> <span m='3712050'>once.</span> <span m='3713860'>So</span>
  <span m='3713970'>can</span> <span m='3714300'>we</span> <span m='3714420'>get</span>
  <span m='3714610'>a--</span> <span m='3714990'>ideally,</span> <span m='3715410'>you</span>
  <span m='3715530'>have</span> <span m='3715710'>one</span> <span m='3715920'>certificate,</span>
  <span m='3716490'>which</span> <span m='3716670'>is</span> <span m='3716790'>like,</span>
  <span m='3717420'>this</span> <span m='3717600'>point</span> <span m='3717870'>is</span>
  <span m='3718050'>the</span> <span m='3718170'>minimum.</span> <span m='3719030'>But</span>
  <span m='3719350'>that's</span> <span m='3719670'>not</span> <span m='3719850'>such</span>
  <span m='3720030'>a</span> <span m='3720090'>good</span> <span m='3720210'>certificate,</span>
  <span m='3720750'>because</span> <span m='3720900'>then,</span> <span m='3721080'>every</span>
  <span m='3721410'>point</span> <span m='3721650'>is</span> <span m='3721740'>involved</span>
  <span m='3722160'>in</span> <span m='3722280'>it.</span> </p><p><span m='3723090'>And</span>
  <span m='3723180'>how</span> <span m='3723330'>do</span> <span m='3723390'>you</span>
  <span m='3723510'>know</span> <span m='3723840'>when</span> <span m='3723990'>it's</span>
  <span m='3724110'>going</span> <span m='3724230'>to</span> <span m='3724290'>be</span>
  <span m='3724380'>violated?</span> <span m='3725030'>I</span> <span m='3725100'>guess</span>
  <span m='3725280'>you</span> <span m='3725400'>could</span> <span m='3725490'>compute</span>
  <span m='3725790'>it</span> <span m='3725850'>in,</span> <span m='3725940'>like,</span>
  <span m='3726090'>linear</span> <span m='3726420'>time</span> <span m='3726780'>or</span>
  <span m='3726870'>something.</span> <span m='3728150'>It's</span> <span m='3728610'>not</span>
  <span m='3728850'>a</span> <span m='3728910'>good</span> <span m='3729090'>plan.</span>
  <span m='3730680'>We</span> <span m='3730770'>need</span> <span m='3730950'>to</span>
  <span m='3731160'>break</span> <span m='3731460'>down</span> <span m='3731710'>the</span>
  <span m='3731790'>certificates</span> <span m='3732480'>that</span> <span m='3732600'>only</span>
  <span m='3732840'>involve</span> <span m='3733140'>a</span> <span m='3733200'>constant</span>
  <span m='3733530'>number</span> <span m='3733740'>of</span> <span m='3733800'>things</span>
  <span m='3736500'>and</span> <span m='3736620'>maintain</span> <span m='3736980'>the</span>
  <span m='3737040'>minimum.</span> <span m='3737400'>And</span> <span m='3737520'>somehow,</span>
  <span m='3738090'>I</span> <span m='3738210'>want</span> <span m='3738420'>to</span>
  <span m='3738660'>get</span> <span m='3738990'>below</span> <span m='3740310'>quadratic</span>
  <span m='3740790'>number</span> <span m='3741000'>of</span> <span m='3741120'>events,</span>
  <span m='3741920'>in</span> <span m='3742020'>the</span> <span m='3742080'>worst</span>
  <span m='3742290'>case.</span> <span m='3743810'>And</span> <span m='3744280'>you</span>
  <span m='3744420'>can.</span> <span m='3745080'>And</span> <span m='3745180'>you</span>
  <span m='3745280'>do</span> <span m='3745380'>it</span> <span m='3745620'>with</span>
  <span m='3745980'>a</span> <span m='3746070'>heap.</span> </p><p><span m='3748620'>Remember</span>
  <span m='3748890'>heaps?</span> <span m='3753090'>Store</span> <span m='3753150'>min</span>
  <span m='3753370'>heap.</span> <span m='3755080'>So</span> <span m='3755780'>min</span>
  <span m='3755970'>heap</span> <span m='3756240'>has</span> <span m='3756510'>this</span>
  <span m='3756610'>property.</span> <span m='3757872'>You</span> <span m='3758220'>have
  x,</span> <span m='3758580'>y,</span> <span m='3760270'>and</span> <span m='3760380'>z.</span>
  <span m='3761550'>Then</span> <span m='3761970'>x</span> <span m='3762270'>is</span>
  <span m='3762390'>less</span> <span m='3762600'>than or equal to</span> <span m='3762870'>y,</span>
  <span m='3763920'>and</span> <span m='3764040'>x</span> <span m='3764310'>is</span>
  <span m='3764400'>less than or</span> <span m='3764670'>equal</span> <span m='3764830'>to</span>
  <span m='3764910'>z.</span> <span m='3765790'>This</span> <span m='3766040'>is</span>
  <span m='3766260'>nice,</span> <span m='3766560'>because--</span> <span m='3766920'>local</span>
  <span m='3767220'>property.</span> <span m='3768220'>These</span> <span m='3768480'>are</span>
  <span m='3768720'>my</span> <span m='3769020'>certificates.</span> <span m='3771390'>For</span>
  <span m='3771510'>every</span> <span m='3771750'>node</span> <span m='3771990'>x,</span>
  <span m='3772660'>I</span> <span m='3772760'>have</span> <span m='3772830'>to</span>
  <span m='3772920'>have</span> <span m='3773100'>this</span> <span m='3773250'>property.</span>
  </p><p><span m='3775230'>So</span> <span m='3775470'>I</span> <span m='3775530'>have</span>
  <span m='3776670'>order</span> <span m='3776940'>n</span> <span m='3777120'>certificates.</span>
  <span m='3781050'>That's</span> <span m='3781230'>good.</span> <span m='3781440'>I</span>
  <span m='3781530'>had</span> <span m='3781650'>order</span> <span m='3781860'>n</span>
  <span m='3781950'>certificates</span> <span m='3782460'>before.</span> <span m='3782880'>But</span>
  <span m='3783030'>I</span> <span m='3783090'>claim</span> <span m='3783420'>these,</span>
  <span m='3784410'>magically,</span> <span m='3784980'>are</span> <span m='3785190'>easier</span>
  <span m='3785580'>to</span> <span m='3785730'>maintain</span> <span m='3786540'>than</span>
  <span m='3786720'>those,</span> <span m='3787080'>even</span> <span m='3787530'>though</span>
  <span m='3787980'>they</span> <span m='3788070'>look</span> <span m='3788280'>almost</span>
  <span m='3788640'>the</span> <span m='3788730'>same--</span> <span m='3790770'>kind</span>
  <span m='3791010'>of</span> <span m='3791070'>crazy.</span> </p><p><span m='3794130'>I</span>
  <span m='3794160'>don't</span> <span m='3794250'>know</span> <span m='3794370'>if</span>
  <span m='3794520'>I</span> <span m='3794580'>really</span> <span m='3794820'>need</span>
  <span m='3794940'>to</span> <span m='3795090'>write</span> <span m='3795330'>it,</span>
  <span m='3795510'>but</span> <span m='3796350'>how</span> <span m='3796500'>do</span>
  <span m='3796620'>we</span> <span m='3796740'>do</span> <span m='3796980'>an</span>
  <span m='3797070'>event?</span> <span m='3801930'>If</span> <span m='3802170'>x</span>
  <span m='3802410'>and</span> <span m='3802500'>y</span> <span m='3802710'>are</span>
  <span m='3802800'>about</span> <span m='3803040'>to</span> <span m='3803160'>invert</span>
  <span m='3803610'>in</span> <span m='3804000'>order--</span> <span m='3804900'>so</span>
  <span m='3805080'>currently,</span> <span m='3805335'>x</span> <span m='3805590'>lets</span>
  <span m='3805890'>me go</span> <span m='3805980'>to</span> <span m='3806070'>y.</span>
  <span m='3807060'>In</span> <span m='3807210'>a</span> <span m='3807270'>moment,</span>
  <span m='3807780'>x</span> <span m='3807990'>will</span> <span m='3808080'>be</span>
  <span m='3808200'>bigger</span> <span m='3808440'>than</span> <span m='3808590'>y.</span>
  <span m='3809520'>I</span> <span m='3809580'>swap</span> <span m='3809940'>x</span>
  <span m='3810090'>and</span> <span m='3810180'>y,</span> <span m='3810810'>update</span>
  <span m='3811200'>all</span> <span m='3811290'>the</span> <span m='3811350'>certificates--</span>
  <span m='3813270'>constant</span> <span m='3813750'>for</span> <span m='3813900'>each.</span>
  </p><p><span m='3814250'>There's</span> <span m='3814600'>two</span> <span m='3814950'>items</span>
  <span m='3815250'>I'm</span> <span m='3815310'>moving.</span> <span m='3816150'>Each</span>
  <span m='3816270'>one</span> <span m='3816390'>is</span> <span m='3816480'>involved</span>
  <span m='3816810'>in</span> <span m='3816900'>a</span> <span m='3816960'>constant</span>
  <span m='3817380'>of</span> <span m='3817530'>certificates--</span> <span m='3818250'>three</span>
  <span m='3818620'>now,</span> <span m='3818880'>instead</span> <span m='3819120'>of</span>
  <span m='3819210'>two--</span> <span m='3820440'>but</span> <span m='3821390'>constant</span>
  <span m='3821890'>number</span> <span m='3822080'>of</span> <span m='3822150'>certificate</span>
  <span m='3822630'>changes</span> <span m='3823110'>and</span> <span m='3823230'>stuff--</span>
  </p><p><span m='3823650'>AUDIENCE:</span> <span m='3823890'>Question.</span> </p><p><span
  m='3824130'>ERIK DEMAINE:</span> <span m='3824280'>--log</span> <span m='3824430'>n</span>
  <span m='3824550'>time.</span> <span m='3825200'>I</span> <span m='3825260'>update</span>
  <span m='3825400'>the</span> <span m='3825510'>priority</span> <span m='3825900'>queue.</span>
  <span m='3826950'>Question?</span> </p><p><span m='3827310'>AUDIENCE:</span> <span
  m='3827432'>How</span> <span m='3827554'>is</span> <span m='3827676'>it</span> <span
  m='3827798'>three?</span> </p><p><span m='3832090'>ERIK DEMAINE:</span> <span m='3832160'>Why</span>
  <span m='3832230'>is</span> <span m='3832320'>it</span> <span m='3832410'>three?</span>
  <span m='3832740'>x is</span> <span m='3833070'>involved in a</span> <span m='3833410'>certificate</span>
  <span m='3833970'>with</span> <span m='3834150'>its</span> <span m='3834270'>two</span>
  <span m='3834450'>children,</span> <span m='3834940'>and</span> <span m='3835050'>with</span>
  <span m='3835200'>its</span> <span m='3835320'>parent.</span> <span m='3835710'>Its</span>
  <span m='3835860'>parent</span> <span m='3836190'>has</span> <span m='3836490'>a</span>
  <span m='3837240'>relation,</span> <span m='3837570'>as</span> <span m='3837660'>well.</span>
  <span m='3838836'>Yeah.</span> <span m='3839320'>So</span> <span m='3839700'>you</span>
  <span m='3839820'>have</span> <span m='3839910'>to</span> <span m='3840000'>be</span>
  <span m='3840120'>careful</span> <span m='3840420'>in</span> <span m='3840510'>counting</span>
  <span m='3842040'>locality.</span> <span m='3843090'>How</span> <span m='3843240'>many</span>
  <span m='3843420'>certificates</span> <span m='3844050'>in</span> <span m='3844320'>each</span>
  <span m='3844560'>object</span> <span m='3845010'>in?</span> </p><p><span m='3845920'>OK</span>
  <span m='3846420'>so</span> <span m='3846620'>we're</span> <span m='3846730'>responsive--</span>
  <span m='3847470'>log</span> <span m='3847720'>n</span> <span m='3847920'>time,</span>
  <span m='3848790'>local,</span> <span m='3849300'>constant,</span> <span m='3849870'>certificates</span>
  <span m='3850380'>per</span> <span m='3850500'>object,</span> <span m='3850770'>compact,</span>
  <span m='3851370'>linear</span> <span m='3851580'>number</span> <span m='3851840'>certificates--</span>
  <span m='3852300'>all</span> <span m='3852460'>these</span> <span m='3852630'>are</span>
  <span m='3852690'>the</span> <span m='3852810'>same.</span> <span m='3853950'>Big</span>
  <span m='3854250'>issue is</span> <span m='3854970'>about</span> <span m='3855300'>efficiency.</span>
  <span m='3856200'>How</span> <span m='3856410'>many</span> <span m='3856590'>events</span>
  <span m='3857070'>is</span> <span m='3857280'>it,</span> <span m='3857550'>in</span>
  <span m='3857700'>the</span> <span m='3857790'>worst</span> <span m='3858030'>case?</span>
  <span m='3858720'>How</span> <span m='3858870'>many</span> <span m='3859020'>events</span>
  <span m='3859290'>do</span> <span m='3859410'>I</span> <span m='3859470'>need?</span>
  </p><p><span m='3862020'>OK,</span> <span m='3862290'>here,</span> <span m='3866850'>for</span>
  <span m='3867060'>kinetic</span> <span m='3867360'>heap,</span> <span m='3867630'>where</span>
  <span m='3867780'>I</span> <span m='3867870'>want</span> <span m='3868020'>to</span>
  <span m='3868110'>maintain</span> <span m='3868470'>the</span> <span m='3868560'>minimum</span>
  <span m='3868890'>at</span> <span m='3869070'>all</span> <span m='3869220'>times,</span>
  <span m='3869830'>there's</span> <span m='3869960'>actually</span> <span m='3870250'>a</span>
  <span m='3870300'>very</span> <span m='3870480'>clear</span> <span m='3870790'>lower</span>
  <span m='3871050'>bound.</span> <span m='3872610'>The</span> <span m='3874050'>number</span>
  <span m='3874410'>of</span> <span m='3874480'>events--</span> <span m='3876800'>or</span>
  <span m='3876930'>let's</span> <span m='3877050'>say,</span> <span m='3877500'>the</span>
  <span m='3877620'>number</span> <span m='3877980'>of</span> <span m='3878130'>changes</span>
  <span m='3878640'>to</span> <span m='3878760'>the</span> <span m='3878880'>min--</span>
  <span m='3883580'>I think</span> <span m='3883650'>this</span> <span m='3883830'>is</span>
  <span m='3883950'>what</span> <span m='3884580'>some</span> <span m='3884760'>people</span>
  <span m='3885000'>call</span> <span m='3885150'>external</span> <span m='3885630'>events.</span>
  <span m='3886020'>Like,</span> <span m='3886230'>you</span> <span m='3886380'>can't</span>
  <span m='3886620'>control</span> <span m='3887040'>when</span> <span m='3887190'>the</span>
  <span m='3887250'>min</span> <span m='3887430'>changes.</span> <span m='3888270'>The</span>
  <span m='3888360'>user</span> <span m='3888660'>controls</span> <span m='3889200'>that</span>
  <span m='3889500'>by</span> <span m='3889800'>how</span> <span m='3889980'>they</span>
  <span m='3890100'>set</span> <span m='3890310'>up</span> <span m='3890490'>the</span>
  <span m='3891690'>trajectories.</span> <span m='3893610'>Changes</span> <span m='3893940'>to</span>
  <span m='3894100'>the</span> <span m='3894300'>min</span> <span m='3894870'>is</span>
  <span m='3895500'>at</span> <span m='3895620'>least</span> <span m='3895950'>n in</span>
  <span m='3896280'>the</span> <span m='3896370'>worst</span> <span m='3896550'>case.</span>
  </p><p><span m='3903070'>It's</span> <span m='3903160'>pretty</span> <span m='3903340'>easy</span>
  <span m='3903550'>to</span> <span m='3903610'>set</span> <span m='3903820'>this</span>
  <span m='3903970'>up.</span> <span m='3904180'>You have a</span> <span m='3904450'>point,</span>
  <span m='3905380'>another</span> <span m='3905590'>point</span> <span m='3905920'>moving</span>
  <span m='3906160'>at</span> <span m='3906220'>constant</span> <span m='3906550'>velocity</span>
  <span m='3906940'>to</span> <span m='3907030'>the</span> <span m='3907090'>left,</span>
  <span m='3907540'>it</span> <span m='3907660'>will</span> <span m='3907810'>overtake.</span>
  <span m='3908800'>You</span> <span m='3908860'>have</span> <span m='3908950'>another</span>
  <span m='3909190'>point</span> <span m='3909460'>farther</span> <span m='3909880'>away,</span>
  <span m='3910880'>with</span> <span m='3911140'>a</span> <span m='3911380'>bigger</span>
  <span m='3911740'>velocity,</span> <span m='3912220'>to</span> <span m='3912340'>the</span>
  <span m='3912400'>left.</span> <span m='3912850'>It</span> <span m='3913000'>will</span>
  <span m='3913630'>overtake</span> <span m='3914230'>after</span> <span m='3914590'>this</span>
  <span m='3914770'>one</span> <span m='3914910'>overtakes--</span> <span m='3915580'>and,</span>
  <span m='3916040'>you</span> <span m='3916500'>know,</span> <span m='3916960'>something</span>
  <span m='3917260'>like</span> <span m='3917470'>this.</span> <span m='3917800'>You've</span>
  <span m='3918230'>got</span> <span m='3918340'>to</span> <span m='3918430'>make</span>
  <span m='3918550'>sure</span> <span m='3918700'>they</span> <span m='3918790'>don't</span>
  <span m='3918970'>all</span> <span m='3919150'>cross</span> <span m='3919450'>at</span>
  <span m='3919540'>the</span> <span m='3919600'>same</span> <span m='3919870'>moment.</span>
  <span m='3920590'>But</span> <span m='3920800'>this</span> <span m='3920920'>one
  will</span> <span m='3921160'>go</span> <span m='3921280'>first,</span> <span m='3921640'>and</span>
  <span m='3921730'>then</span> <span m='3921820'>this</span> <span m='3921890'>guy</span>
  <span m='3922110'>will</span> <span m='3922200'>cross</span> <span m='3922450'>over.</span>
  <span m='3922840'>And</span> <span m='3923200'>eventually--</span> </p><p><span
  m='3924700'>So</span> <span m='3924850'>it's</span> <span m='3924970'>easy</span>
  <span m='3925210'>to</span> <span m='3925330'>set</span> <span m='3925540'>up.</span>
  <span m='3926200'>The</span> <span m='3926320'>min</span> <span m='3926530'>can</span>
  <span m='3926770'>change</span> <span m='3927220'>a linear</span> <span m='3927310'>number</span>
  <span m='3927550'>of</span> <span m='3927610'>times.</span> <span m='3928540'>I</span>
  <span m='3928690'>claim</span> <span m='3930640'>in</span> <span m='3931120'>this</span>
  <span m='3931300'>data</span> <span m='3931480'>structure,</span> <span m='3931780'>well,</span>
  <span m='3931870'>of</span> <span m='3931960'>course,</span> <span m='3932180'>the</span>
  <span m='3932300'>min</span> <span m='3932470'>will</span> <span m='3932590'>change,</span>
  <span m='3932890'>at</span> <span m='3932950'>most,</span> <span m='3933260'>a</span>
  <span m='3933360'>linear</span> <span m='3933760'>number</span> <span m='3934000'>of</span>
  <span m='3934090'>times.</span> <span m='3934630'>Well,</span> <span m='3934900'>it's</span>
  <span m='3935050'>not</span> <span m='3935140'>clear</span> <span m='3935410'>it's
  at</span> <span m='3935500'>most.</span> <span m='3936580'>But</span> <span m='3936730'>that's</span>
  <span m='3936970'>true.</span> </p><p><span m='3937750'>What</span> <span m='3937870'>we</span>
  <span m='3937990'>care</span> <span m='3938170'>about</span> <span m='3938380'>though,
  is,</span> <span m='3938660'>we're</span> <span m='3938760'>storing</span> <span
  m='3938950'>way</span> <span m='3939370'>more</span> <span m='3939580'>certificates</span>
  <span m='3940210'>than</span> <span m='3940390'>the</span> <span m='3940480'>min.</span>
  <span m='3940870'>We</span> <span m='3940960'>have</span> <span m='3941080'>a</span>
  <span m='3941140'>linear</span> <span m='3941500'>number</span> <span m='3941710'>of</span>
  <span m='3941770'>certificates.</span> <span m='3942910'>I</span> <span m='3943000'>claim</span>
  <span m='3943330'>the</span> <span m='3943420'>total</span> <span m='3943810'>number</span>
  <span m='3944080'>of</span> <span m='3944170'>events</span> <span m='3946120'>in</span>
  <span m='3946270'>this</span> <span m='3946450'>data</span> <span m='3946660'>structure,</span>
  <span m='3947170'>if</span> <span m='3947350'>there</span> <span m='3947530'>are</span>
  <span m='3947560'>no</span> <span m='3947800'>change</span> <span m='3948280'>operations,</span>
  <span m='3949590'>if</span> <span m='3949750'>we</span> <span m='3949840'>just</span>
  <span m='3950110'>advance</span> <span m='3950620'>to</span> <span m='3950770'>infinity--</span>
  <span m='3952060'>number</span> <span m='3952330'>of</span> <span m='3952420'>events</span>
  <span m='3953360'>is</span> <span m='3953560'>order</span> <span m='3954490'>n</span>
  <span m='3954640'>log</span> <span m='3954940'>n.</span> <span m='3958230'>And</span>
  <span m='3958360'>so</span> <span m='3958510'>we</span> <span m='3958600'>call</span>
  <span m='3958780'>the</span> <span m='3958870'>efficiency</span> <span m='3959410'>log</span>
  <span m='3959770'>n,</span> <span m='3960160'>because</span> <span m='3960430'>you're</span>
  <span m='3961190'>log</span> <span m='3961480'>in</span> <span m='3961570'>factor</span>
  <span m='3961900'>away</span> <span m='3962170'>from</span> <span m='3962680'>this</span>
  <span m='3962870'>lower</span> <span m='3963060'>bound.</span> <span m='3964750'>This</span>
  <span m='3964990'>is</span> <span m='3965140'>the</span> <span m='3965260'>interesting</span>
  <span m='3965650'>part.</span> <span m='3966310'>And</span> <span m='3966520'>this</span>
  <span m='3966670'>requires</span> <span m='3967150'>a</span> <span m='3967220'>proof.</span>
  </p><p><span m='3999620'>So</span> <span m='3999860'>why</span> <span m='4000070'>is</span>
  <span m='4000190'>the</span> <span m='4000280'>number</span> <span m='4000490'>of</span>
  <span m='4000580'>events</span> <span m='4001060'>order</span> <span m='4001330'>n</span>
  <span m='4001560'>log</span> <span m='4001770'>n?</span> <span m='4002050'>We're</span>
  <span m='4002170'>going</span> <span m='4002290'>to</span> <span m='4002350'>prove</span>
  <span m='4002620'>this</span> <span m='4002890'>by</span> <span m='4003100'>amortization,</span>
  <span m='4007000'>with</span> <span m='4007210'>a</span> <span m='4007450'>somewhat</span>
  <span m='4010330'>tedious</span> <span m='4011080'>potential</span> <span m='4011500'>function.</span>
  <span m='4012410'>But</span> <span m='4012460'>it's</span> <span m='4012550'>sort</span>
  <span m='4012670'>of</span> <span m='4012730'>the</span> <span m='4012850'>obvious</span>
  <span m='4013180'>one.</span> </p><p><span m='4023230'>At</span> <span m='4023380'>a</span>
  <span m='4023440'>time</span> <span m='4023750'>t,</span> <span m='4024610'>I</span>
  <span m='4024670'>wanted</span> <span m='4024880'>to</span> <span m='4024970'>find</span>
  <span m='4025180'>my</span> <span m='4025600'>potential</span> <span m='4026050'>at</span>
  <span m='4026140'>time</span> <span m='4026410'>t</span> <span m='4027070'>to</span>
  <span m='4027200'>be,</span> <span m='4027460'>how</span> <span m='4027640'>many</span>
  <span m='4027850'>events</span> <span m='4028180'>will</span> <span m='4028360'>happen</span>
  <span m='4028690'>in</span> <span m='4028810'>the</span> <span m='4028900'>future?</span>
  <span m='4029450'>This</span> <span m='4029530'>is</span> <span m='4029650'>the</span>
  <span m='4029770'>thing</span> <span m='4030010'>I</span> <span m='4030130'>want</span>
  <span m='4030280'>to</span> <span m='4030350'>bound.</span> <span m='4031870'>So</span>
  <span m='4032040'>I</span> <span m='4032130'>want</span> <span m='4032230'>to</span>
  <span m='4032280'>prove</span> <span m='4032410'>this</span> <span m='4032590'>is</span>
  <span m='4032680'>order</span> <span m='4033100'>n</span> <span m='4033250'>log</span>
  <span m='4033460'>n</span> <span m='4033610'>at</span> <span m='4033790'>time</span>
  <span m='4034090'>zero.</span> <span m='4035200'>But</span> <span m='4035350'>let's</span>
  <span m='4035530'>think</span> <span m='4035710'>about</span> <span m='4035920'>how
  it</span> <span m='4036100'>changes</span> <span m='4036580'>over</span> <span m='4036760'>time.</span>
  </p><p><span m='4042290'>So</span> <span m='4044470'>I'm</span> <span m='4044560'>going</span>
  <span m='4044680'>to</span> <span m='4044770'>rewrite</span> <span m='4045190'>this</span>
  <span m='4046690'>as</span> <span m='4046840'>follows.</span> <span m='4076066'>I'm
  going to</span> <span m='4076560'>Sum</span> <span m='4077150'>over</span> <span
  m='4077540'>all</span> <span m='4078410'>items</span> <span m='4079250'>x.</span>
  <span m='4080320'>And</span> <span m='4080420'>we're</span> <span m='4080540'>thinking</span>
  <span m='4080870'>about</span> <span m='4081140'>the</span> <span m='4081440'>potential</span>
  <span m='4081800'>at</span> <span m='4081890'>time</span> <span m='4082190'>t.</span>
  <span m='4083180'>So</span> <span m='4083360'>I</span> <span m='4083420'>look--</span>
  <span m='4083780'>x</span> <span m='4084110'>is</span> <span m='4084290'>in</span>
  <span m='4084440'>some</span> <span m='4084710'>node.</span> <span m='4085520'>And</span>
  <span m='4086030'>which</span> <span m='4086210'>node</span> <span m='4086390'>it's</span>
  <span m='4086600'>in</span> <span m='4086840'>changes</span> <span m='4087170'>over</span>
  <span m='4087380'>time.</span> <span m='4087670'>But</span> <span m='4087830'>at</span>
  <span m='4087890'>time</span> <span m='4088160'>t,</span> <span m='4088610'>it's</span>
  <span m='4088730'>in</span> <span m='4088850'>some</span> <span m='4089040'>node.</span>
  </p><p><span m='4089600'>I</span> <span m='4089720'>look</span> <span m='4089900'>at</span>
  <span m='4089960'>all</span> <span m='4090080'>the</span> <span m='4090170'>descendants</span>
  <span m='4090620'>of</span> <span m='4090740'>that</span> <span m='4090890'>node.</span>
  <span m='4091620'>I</span> <span m='4091730'>look</span> <span m='4091940'>at</span>
  <span m='4092030'>those</span> <span m='4092300'>items.</span> <span m='4093640'>And</span>
  <span m='4093740'>I</span> <span m='4093830'>see</span> <span m='4094010'>which</span>
  <span m='4094250'>of</span> <span m='4094310'>those</span> <span m='4094490'>items</span>
  <span m='4094790'>will</span> <span m='4095060'>overtake</span> <span m='4095660'>x</span>
  <span m='4096109'>in</span> <span m='4096260'>a</span> <span m='4096319'>future</span>
  <span m='4096680'>time.</span> <span m='4097939'>Those</span> <span m='4098180'>are</span>
  <span m='4098270'>the</span> <span m='4098359'>ones</span> <span m='4098930'>that</span>
  <span m='4099050'>I</span> <span m='4099140'>care</span> <span m='4099350'>about.</span>
  <span m='4099529'>When</span> <span m='4099649'>you</span> <span m='4099770'>overtake</span>
  <span m='4100520'>an</span> <span m='4100670'>ancestor,</span> <span m='4101330'>that's</span>
  <span m='4101600'>when</span> <span m='4103040'>an</span> <span m='4103189'>event</span>
  <span m='4103430'>happens.</span> </p><p><span m='4105910'>I</span> <span m='4106220'>claim</span>
  <span m='4106550'>these</span> <span m='4106700'>two</span> <span m='4106850'>things</span>
  <span m='4107090'>are</span> <span m='4107180'>equal.</span> <span m='4108380'>I</span>
  <span m='4108529'>probably</span> <span m='4108890'>don't</span> <span m='4109069'>even</span>
  <span m='4109310'>need</span> <span m='4109460'>to</span> <span m='4109580'>prove</span>
  <span m='4109819'>that.</span> <span m='4110600'>So</span> <span m='4111200'>this</span>
  <span m='4111380'>is</span> <span m='4111470'>in</span> <span m='4111590'>parentheses.</span>
  <span m='4113000'>Don't</span> <span m='4113149'>worry</span> <span m='4113300'>about</span>
  <span m='4113510'>this</span> <span m='4113630'>being</span> <span m='4113870'>equal.</span>
  <span m='4114080'>Think</span> <span m='4114290'>of</span> <span m='4114380'>this</span>
  <span m='4114620'>as</span> <span m='4114740'>the</span> <span m='4114830'>potential</span>
  <span m='4115050'>function.</span> </p><p><span m='4120380'>Now,</span> <span m='4120590'>I</span>
  <span m='4120680'>want</span> <span m='4120830'>to</span> <span m='4120890'>look</span>
  <span m='4121069'>at</span> <span m='4121130'>an</span> <span m='4121250'>event</span>
  <span m='4121609'>and</span> <span m='4121760'>see</span> <span m='4122359'>how</span>
  <span m='4122630'>this</span> <span m='4122870'>changes.</span> <span m='4124340'>I</span>
  <span m='4124430'>need</span> <span m='4124609'>a</span> <span m='4124640'>little</span>
  <span m='4124880'>bit</span> <span m='4125029'>more</span> <span m='4125180'>notation.</span>
  <span m='4126800'>I'm</span> <span m='4126859'>going</span> <span m='4126979'>to</span>
  <span m='4127069'>call</span> <span m='4127279'>this</span> <span m='4127490'>thing</span>
  <span m='4129060'>phi</span> <span m='4129430'>of</span> <span m='4130319'>t</span>
  <span m='4130550'>comma</span> <span m='4130850'>x.</span> <span m='4133189'>So</span>
  <span m='4133310'>phi</span> <span m='4133580'>of t</span> <span m='4133850'>is</span>
  <span m='4134000'>the</span> <span m='4134060'>sum</span> <span m='4134359'>over</span>
  <span m='4134439'>all</span> <span m='4134660'>x</span> <span m='4134990'>of</span>
  <span m='4135200'>this</span> <span m='4135410'>thing,</span> <span m='4135710'>which</span>
  <span m='4135859'>is</span> <span m='4136100'>phi</span> <span m='4136189'>of</span>
  <span m='4136290'>t</span> <span m='4136380'>comma</span> <span m='4136700'>x--</span>
  <span m='4137720'>number</span> <span m='4137990'>of</span> <span m='4138050'>descendants</span>
  <span m='4138500'>of</span> <span m='4138620'>x</span> <span m='4138950'>at</span>
  <span m='4139069'>this</span> <span m='4139250'>time</span> <span m='4139640'>that</span>
  <span m='4139760'>will,</span> <span m='4140090'>in</span> <span m='4140210'>the</span>
  <span m='4140300'>future,</span> <span m='4140689'>overtake</span> <span m='4141330'>x,</span>
  <span m='4141750'>meaning</span> <span m='4142189'>their</span> <span m='4142430'>key</span>
  <span m='4142729'>will</span> <span m='4142850'>get</span> <span m='4143029'>larger</span>
  <span m='4143330'>than</span> <span m='4143510'>x.</span> </p><p><span m='4145290'>OK.</span>
  <span m='4146300'>I</span> <span m='4146450'>can</span> <span m='4147260'>also</span>
  <span m='4147529'>expand</span> <span m='4148270'>phi of</span> <span m='4148609'>t,</span>
  <span m='4148874'>x</span> <span m='4149140'>in</span> <span m='4150410'>a</span>
  <span m='4150470'>simple</span> <span m='4150800'>way.</span> <span m='4152010'>It's</span>
  <span m='4152450'>kind</span> <span m='4152689'>of</span> <span m='4152810'>trivial.</span>
  <span m='4153260'>But</span> <span m='4154490'>if</span> <span m='4154640'>I</span>
  <span m='4154760'>look</span> <span m='4155060'>at</span> <span m='4156470'>each</span>
  <span m='4156740'>child</span> <span m='4157250'>of</span> <span m='4157370'>x--</span>
  <span m='4157670'>there's</span> <span m='4157819'>two</span> <span m='4158060'>of</span>
  <span m='4158149'>them--</span> <span m='4158840'>call</span> <span m='4159050'>that</span>
  <span m='4159229'>y--</span> <span m='4160760'>and</span> <span m='4160850'>then</span>
  <span m='4161029'>measure</span> <span m='4162109'>how</span> <span m='4162410'>many</span>
  <span m='4162680'>descendants</span> <span m='4167300'>of</span> <span m='4167540'>y</span>
  <span m='4169649'>at</span> <span m='4169850'>time</span> <span m='4170180'>t</span>
  <span m='4175069'>will</span> <span m='4175279'>overtake</span> <span m='4176090'>x?</span>
  <span m='4178340'>So</span> <span m='4178609'>it's</span> <span m='4178790'>almost</span>
  <span m='4179120'>the</span> <span m='4179180'>same</span> <span m='4179450'>words,</span>
  <span m='4179779'>but</span> <span m='4179899'>I</span> <span m='4179960'>changed</span>
  <span m='4181130'>one</span> <span m='4181340'>of</span> <span m='4181460'>the</span>
  <span m='4181859'>x's</span> <span m='4182210'>to</span> <span m='4182330'>a</span>
  <span m='4182390'>y--</span> <span m='4182660'>but</span> <span m='4182779'>only</span>
  <span m='4183020'>one</span> <span m='4183170'>of</span> <span m='4183260'>them.</span>
  <span m='4186399'>Sorry--</span> <span m='4186664'>"future"</span> <span m='4186930'>I
  write</span> <span m='4187830'>greater</span> <span m='4188080'>than</span> <span
  m='4188260'>"t."</span> </p><p><span m='4190399'>This</span> <span m='4190700'>is</span>
  <span m='4190880'>a</span> <span m='4190970'>different</span> <span m='4191330'>quantity--</span>
  <span m='4191960'>slightly</span> <span m='4192470'>different--</span> <span m='4192770'>which</span>
  <span m='4192950'>I'm</span> <span m='4193010'>going</span> <span m='4193130'>to</span>
  <span m='4193210'>call</span> <span m='4193640'>phi</span> <span m='4193990'>of</span>
  <span m='4194690'>t</span> <span m='4195140'>comma</span> <span m='4195590'>x</span>
  <span m='4195930'>comma</span> <span m='4196370'>y.</span> <span m='4197360'>I</span>
  <span m='4197450'>just</span> <span m='4197600'>need</span> <span m='4197750'>to</span>
  <span m='4197840'>be</span> <span m='4197930'>able</span> <span m='4198080'>to</span>
  <span m='4198200'>talk</span> <span m='4198440'>about</span> <span m='4198680'>this.</span>
  <span m='4199160'>So this is</span> <span m='4199280'>mostly</span> <span m='4199580'>to</span>
  <span m='4199670'>introduce</span> <span m='4200090'>notation.</span> </p><p><span
  m='4202560'>OK,</span> <span m='4203160'>and</span> <span m='4203750'>descendants</span>
  <span m='4204380'>of</span> <span m='4204470'>y--</span> <span m='4204680'>this</span>
  <span m='4204830'>is</span> <span m='4204950'>including</span> <span m='4205400'>y</span>
  <span m='4206090'>itself.</span> <span m='4206540'>So</span> <span m='4206690'>there's</span>
  <span m='4206840'>y</span> <span m='4207080'>and</span> <span m='4207290'>all</span>
  <span m='4207380'>of</span> <span m='4207470'>its</span> <span m='4207590'>children--</span>
  <span m='4208290'>descendants--</span> <span m='4208670'>whatever--</span> <span
  m='4210430'>which</span> <span m='4210610'>are</span> <span m='4210650'>those</span>
  <span m='4210830'>that will</span> <span m='4210920'>overtake</span> <span m='4211430'>x.</span>
  <span m='4212330'>If</span> <span m='4212450'>I</span> <span m='4212740'>add</span>
  <span m='4212990'>that</span> <span m='4213210'>up</span> <span m='4213290'>for</span>
  <span m='4213440'>both</span> <span m='4213620'>children,</span> <span m='4214100'>that</span>
  <span m='4214280'>is</span> <span m='4214400'>the</span> <span m='4214520'>total</span>
  <span m='4214820'>number</span> <span m='4215030'>of</span> <span m='4215090'>descendants</span>
  <span m='4215510'>of</span> <span m='4215630'>x</span> <span m='4215870'>that</span>
  <span m='4216020'>will</span> <span m='4216590'>overtake</span> <span m='4216980'>x.</span>
  <span m='4218060'>So</span> <span m='4218270'>this</span> <span m='4218650'>equality</span>
  <span m='4219060'>is</span> <span m='4219140'>trivial.</span> <span m='4220190'>Mainly,</span>
  <span m='4220400'>I</span> <span m='4220460'>wanted</span> <span m='4220670'>to</span>
  <span m='4220760'>introduce</span> <span m='4221150'>that.</span> </p><p><span m='4223730'>OK.</span>
  <span m='4224900'>So</span> <span m='4225470'>what</span> <span m='4225770'>now?</span>
  <span m='4226010'>Let's</span> <span m='4226160'>look</span> <span m='4226340'>at</span>
  <span m='4226400'>an</span> <span m='4226520'>event,</span> <span m='4227315'>and</span>
  <span m='4227660'>see</span> <span m='4227900'>what</span> <span m='4228050'>changes.</span>
  </p><p><span m='4246530'>So--</span> <span m='4249570'>try</span> <span m='4250010'>a
  little</span> <span m='4250340'>bigger--</span> <span m='4251460'>x,</span> <span
  m='4251820'>y,</span> <span m='4252245'>z.</span> <span m='4254370'>Let's</span>
  <span m='4254550'>say</span> <span m='4254880'>we</span> <span m='4255000'>need</span>
  <span m='4255150'>to</span> <span m='4255240'>change</span> <span m='4255540'>it</span>
  <span m='4255600'>to</span> <span m='4255870'>y,</span> <span m='4256350'>x,</span>
  <span m='4256806'>z.</span> <span m='4258630'>Because</span> <span m='4258990'>y</span>
  <span m='4259260'>is</span> <span m='4259380'>about</span> <span m='4259620'>to</span>
  <span m='4259740'>overtake</span> <span m='4260250'>x.</span> <span m='4262920'>How</span>
  <span m='4263130'>does</span> <span m='4263320'>the</span> <span m='4263400'>potential</span>
  <span m='4263910'>change?</span> </p><p><span m='4265316'>OK,</span> <span m='4265790'>well,</span>
  <span m='4266100'>potential</span> <span m='4266670'>is</span> <span m='4266820'>the</span>
  <span m='4266880'>sum</span> <span m='4267240'>of</span> <span m='4267360'>all</span>
  <span m='4267640'>these</span> <span m='4268140'>phi</span> <span m='4268430'>t,</span>
  <span m='4268830'>x's.</span> <span m='4269970'>So</span> <span m='4272490'>which</span>
  <span m='4272730'>of</span> <span m='4272790'>these</span> <span m='4273000'>phi</span>
  <span m='4273370'>t, x's</span> <span m='4273690'>change?</span> <span m='4274650'>I</span>
  <span m='4274770'>claim</span> <span m='4275250'>that</span> <span m='4275670'>phi</span>
  <span m='4276000'>of--</span> <span m='4276530'>I'm</span> <span m='4276600'>going</span>
  <span m='4276720'>to</span> <span m='4276780'>call</span> <span m='4276960'>it</span>
  <span m='4277050'>t-plus,</span> <span m='4277680'>which</span> <span m='4277860'>is</span>
  <span m='4277950'>the</span> <span m='4278070'>moment</span> <span m='4278370'>right</span>
  <span m='4278670'>after</span> <span m='4278940'>now--</span> <span m='4279300'>infintesimally</span>
  <span m='4279960'>larger--</span> <span m='4282750'>I</span> <span m='4283620'>claim</span>
  <span m='4283920'>it</span> <span m='4284010'>does</span> <span m='4284160'>not</span>
  <span m='4284430'>change</span> <span m='4285000'>for</span> <span m='4285150'>most</span>
  <span m='4285420'>vertices.</span> <span m='4289050'>It</span> <span m='4289170'>only</span>
  <span m='4289470'>changes</span> <span m='4289860'>for</span> <span m='4290040'>x</span>
  <span m='4290310'>and</span> <span m='4290400'>y.</span> <span m='4290730'>If</span>
  <span m='4291120'>x</span> <span m='4291510'>and</span> <span m='4291600'>y</span>
  <span m='4291780'>are</span> <span m='4291840'>the</span> <span m='4291930'>guys</span>
  <span m='4292140'>that</span> <span m='4292190'>are</span> <span m='4292260'>switching</span>
  <span m='4292650'>order,</span> <span m='4293980'>this</span> <span m='4294210'>will</span>
  <span m='4294300'>not</span> <span m='4294450'>change</span> <span m='4294810'>for</span>
  <span m='4294900'>any</span> <span m='4295110'>others.</span> </p><p><span m='4296230'>Why</span>
  <span m='4296340'>is</span> <span m='4296430'>that?</span> <span m='4296830'>Because</span>
  <span m='4296910'>we're</span> <span m='4297000'>looking</span> <span m='4297240'>at</span>
  <span m='4297300'>number of</span> <span m='4297570'>descendants</span> <span m='4298050'>to</span>
  <span m='4298110'>some</span> <span m='4298350'>vertex</span> <span m='4298890'>that</span>
  <span m='4299040'>will</span> <span m='4299310'>overtake</span> <span m='4299760'>that</span>
  <span m='4299940'>vertex.</span> <span m='4301270'>So</span> <span m='4301560'>do</span>
  <span m='4301710'>the</span> <span m='4301920'>descendants</span> <span m='4302430'>change?</span>
  <span m='4302910'>No.</span> <span m='4303630'>Descendants</span> <span m='4304020'>of</span>
  <span m='4304110'>x</span> <span m='4304260'>and</span> <span m='4304350'>y</span>
  <span m='4304500'>change,</span> <span m='4304800'>but</span> <span m='4304890'>no</span>
  <span m='4305040'>one</span> <span m='4305190'>else,</span> <span m='4305730'>their</span>
  <span m='4305850'>descendants</span> <span m='4306270'>change.</span> <span m='4307190'>This
  is</span> <span m='4307350'>just</span> <span m='4307650'>a</span> <span m='4307680'>swap</span>
  <span m='4308130'>of</span> <span m='4308250'>two</span> <span m='4308490'>adjacent</span>
  <span m='4309000'>elements.</span> </p><p><span m='4310980'>Will</span> <span m='4311160'>overtaking</span>
  <span m='4311700'>change?</span> <span m='4312030'>No.</span> <span m='4312270'>I</span>
  <span m='4312330'>mean,</span> <span m='4313140'>overtaking</span> <span m='4313620'>doesn't</span>
  <span m='4313830'>change.</span> <span m='4314130'>If</span> <span m='4314220'>you're</span>
  <span m='4314310'>going</span> <span m='4314430'>to</span> <span m='4314490'>be</span>
  <span m='4314580'>overtaken</span> <span m='4315030'>by</span> <span m='4315180'>x</span>
  <span m='4315360'>before,</span> <span m='4316100'>you</span> <span m='4316210'>still</span>
  <span m='4316380'>be</span> <span m='4316500'>overtaken</span> <span m='4316950'>by</span>
  <span m='4317080'>x.</span> <span m='4318120'>And it's</span> <span m='4318240'>still</span>
  <span m='4318480'>a</span> <span m='4318540'>descendant--</span> <span m='4319410'>unless</span>
  <span m='4319710'>it</span> <span m='4319770'>was</span> <span m='4319920'>y.</span>
  <span m='4320250'>y</span> <span m='4320490'>is</span> <span m='4320580'>the</span>
  <span m='4320670'>only</span> <span m='4320850'>one</span> <span m='4321090'>for</span>
  <span m='4321450'>which</span> <span m='4321630'>it</span> <span m='4321720'>changed.</span>
  <span m='4322830'>OK,</span> <span m='4322980'>so</span> <span m='4323130'>we</span>
  <span m='4323340'>only</span> <span m='4323670'>have</span> <span m='4323790'>to</span>
  <span m='4323880'>think</span> <span m='4324090'>about</span> <span m='4324330'>x</span>
  <span m='4324510'>and</span> <span m='4324600'>y</span> <span m='4325400'>and</span>
  <span m='4325500'>how</span> <span m='4325740'>their</span> <span m='4325950'>potentials</span>
  <span m='4326520'>are</span> <span m='4326640'>changing.</span> <span m='4328680'>OK.</span>
  </p><p><span m='4332250'>So</span> <span m='4333720'>let's</span> <span m='4333990'>look</span>
  <span m='4334260'>at</span> <span m='4334530'>x.</span> <span m='4335660'>x</span>
  <span m='4336000'>is</span> <span m='4336090'>pretty</span> <span m='4336300'>simple.</span>
  <span m='4337500'>x</span> <span m='4337710'>went</span> <span m='4337950'>down.</span>
  <span m='4341700'>So</span> <span m='4341850'>we</span> <span m='4341940'>care</span>
  <span m='4342090'>about</span> <span m='4342400'>now</span> <span m='4342480'>the</span>
  <span m='4342600'>descendants</span> <span m='4343140'>of</span> <span m='4343290'>x.</span>
  <span m='4343600'>Those</span> <span m='4343860'>are</span> <span m='4343950'>what</span>
  <span m='4344160'>used</span> <span m='4344430'>to</span> <span m='4344550'>be</span>
  <span m='4344670'>the</span> <span m='4344760'>descendants</span> <span m='4345240'>of</span>
  <span m='4345360'>y.</span> </p><p><span m='4347290'>So</span> <span m='4348180'>what</span>
  <span m='4348360'>are</span> <span m='4348420'>the</span> <span m='4348540'>descendants</span>
  <span m='4348990'>of</span> <span m='4349110'>y</span> <span m='4349890'>that</span>
  <span m='4350010'>will</span> <span m='4350130'>overtake</span> <span m='4350580'>x?</span>
  <span m='4351480'>That</span> <span m='4351720'>is</span> <span m='4352710'>phi</span>
  <span m='4353140'>of</span> <span m='4353460'>t,</span> <span m='4353940'>x,</span>
  <span m='4354862'>y.</span> <span m='4357630'>That's</span> <span m='4357840'>the</span>
  <span m='4357930'>definition</span> <span m='4358440'>here.</span> <span m='4358740'>The</span>
  <span m='4358890'>descendants</span> <span m='4359400'>of</span> <span m='4359520'>y</span>
  <span m='4360170'>that</span> <span m='4360340'>will</span> <span m='4360450'>overtake</span>
  <span m='4360840'>x--</span> <span m='4361200'>we</span> <span m='4361440'>had</span>
  <span m='4361680'>that</span> <span m='4362280'>written</span> <span m='4362460'>down.</span>
  <span m='4363240'>So</span> <span m='4363600'>that</span> <span m='4363840'>is</span>
  <span m='4364020'>its</span> <span m='4364170'>new</span> <span m='4364350'>potential,</span>
  <span m='4365160'>except</span> <span m='4365970'>as</span> <span m='4366120'>a</span>
  <span m='4366180'>minus</span> <span m='4366510'>1,</span> <span m='4366915'>because</span>
  <span m='4368130'>y</span> <span m='4368850'>used</span> <span m='4369030'>to</span>
  <span m='4369120'>be</span> <span m='4369210'>a</span> <span m='4369240'>descendant</span>
  <span m='4369690'>that</span> <span m='4369840'>would</span> <span m='4370020'>overtake</span>
  <span m='4370440'>x.</span> <span m='4370690'>But</span> <span m='4370860'>it</span>
  <span m='4370950'>just</span> <span m='4371130'>overtook</span> <span m='4371580'>x--</span>
  <span m='4371820'>not</span> <span m='4371970'>going</span> <span m='4372120'>to</span>
  <span m='4372180'>happen</span> <span m='4372480'>again.</span> <span m='4373652'>Not</span>
  <span m='4374090'>gonna</span> <span m='4374310'>happen</span> <span m='4374580'>again.</span>
  </p><p><span m='4375120'>I'm</span> <span m='4375270'>assuming</span> <span m='4375600'>here</span>
  <span m='4375760'>affine</span> <span m='4376170'>motion,</span> <span m='4376800'>I</span>
  <span m='4376860'>suppose.</span> <span m='4377400'>It</span> <span m='4377850'>could</span>
  <span m='4378060'>really</span> <span m='4378270'>happen</span> <span m='4378570'>a</span>
  <span m='4378620'>constant</span> <span m='4378890'>number</span> <span m='4379080'>of</span>
  <span m='4379170'>times.</span> <span m='4379800'>But</span> <span m='4380640'>let's</span>
  <span m='4380820'>keep</span> <span m='4381030'>it</span> <span m='4381090'>simple.</span>
  <span m='4383430'>OK.</span> <span m='4384840'>That</span> <span m='4384990'>was</span>
  <span m='4385140'>easy.</span> <span m='4385950'>Next one's</span> <span m='4386210'>a
  little</span> <span m='4386430'>harder.</span> </p><p><span m='4390360'>The</span>
  <span m='4390450'>other</span> <span m='4390600'>one</span> <span m='4390750'>is</span>
  <span m='4390900'>y.</span> <span m='4394050'>What</span> <span m='4394350'>is</span>
  <span m='4394560'>the</span> <span m='4394680'>new</span> <span m='4394890'>potential</span>
  <span m='4396120'>of</span> <span m='4396960'>y?</span> <span m='4398310'>y</span>
  <span m='4398580'>has</span> <span m='4398790'>new</span> <span m='4399000'>descendants</span>
  <span m='4399510'>now.</span> <span m='4399720'>It used</span> <span m='4399960'>to</span>
  <span m='4400050'>just</span> <span m='4400260'>have</span> <span m='4400440'>this</span>
  <span m='4400920'>many</span> <span m='4401160'>descendants.</span> <span m='4402700'>It</span>
  <span m='4403140'>still</span> <span m='4403440'>has</span> <span m='4403680'>those</span>
  <span m='4403890'>descendants.</span> <span m='4404700'>It</span> <span m='4404820'>now</span>
  <span m='4405000'>has</span> <span m='4405220'>x,</span> <span m='4405570'>which</span>
  <span m='4405780'>doesn't</span> <span m='4406110'>matter,</span> <span m='4406590'>if</span>
  <span m='4406770'>we</span> <span m='4406890'>assume</span> <span m='4407160'>it</span>
  <span m='4407200'>will</span> <span m='4407340'>never</span> <span m='4407610'>be</span>
  <span m='4407760'>overtaken</span> <span m='4408240'>again.</span> <span m='4409380'>And</span>
  <span m='4409620'>now,</span> <span m='4409800'>it</span> <span m='4409890'>has</span>
  <span m='4410100'>this</span> <span m='4410220'>whole</span> <span m='4410460'>subtree</span>
  <span m='4410850'>of</span> <span m='4410910'>z.</span> <span m='4412980'>So</span>
  <span m='4414030'>we</span> <span m='4414180'>have</span> <span m='4415440'>whatever</span>
  <span m='4415770'>it</span> <span m='4415860'>used</span> <span m='4416100'>to</span>
  <span m='4416220'>have,</span> <span m='4416770'>which</span> <span m='4416880'>is</span>
  <span m='4417000'>phi of</span> <span m='4417255'>t, y.</span> <span m='4417960'>That's</span>
  <span m='4418170'>all</span> <span m='4418320'>it's</span> <span m='4418470'>old</span>
  <span m='4418710'>descendants.</span> <span m='4420210'>And</span> <span m='4420360'>now</span>
  <span m='4420630'>we</span> <span m='4420780'>have</span> <span m='4421050'>this</span>
  <span m='4421200'>new</span> <span m='4421410'>thing</span> <span m='4422712'>phi</span>
  <span m='4423200'>of</span> <span m='4423660'>t,</span> <span m='4423945'>y,</span>
  <span m='4424230'>z.</span> </p><p><span m='4426450'>If</span> <span m='4426540'>you</span>
  <span m='4426630'>plug</span> <span m='4426870'>that</span> <span m='4427080'>into</span>
  <span m='4427320'>here,</span> <span m='4428430'>that is</span> <span m='4428550'>the</span>
  <span m='4428640'>number</span> <span m='4428910'>of</span> <span m='4429000'>descendants</span>
  <span m='4429450'>of</span> <span m='4429630'>z</span> <span m='4430620'>that</span>
  <span m='4430770'>will</span> <span m='4430890'>overtake</span> <span m='4431610'>y.</span>
  <span m='4434970'>That's</span> <span m='4435300'>the</span> <span m='4435480'>new</span>
  <span m='4435630'>thing</span> <span m='4435840'>that</span> <span m='4435930'>we</span>
  <span m='4436080'>add</span> <span m='4436260'>on.</span> <span m='4437890'>So</span>
  <span m='4438000'>this</span> <span m='4438180'>is</span> <span m='4438300'>an</span>
  <span m='4438390'>increase.</span> <span m='4438840'>This was</span> <span m='4439070'>a</span>
  <span m='4439160'>decrease</span> <span m='4439840'>and</span> <span m='4439940'>this</span>
  <span m='4440010'>is</span> <span m='4440130'>an</span> <span m='4440220'>increase.</span>
  <span m='4440580'>We</span> <span m='4440700'>hope</span> <span m='4440850'>that</span>
  <span m='4441000'>they're</span> <span m='4441150'>about</span> <span m='4441390'>the</span>
  <span m='4441480'>same.</span> <span m='4442040'>In fact,</span> <span m='4442310'>they</span>
  <span m='4442440'>will</span> <span m='4442590'>be</span> <span m='4442860'>basically</span>
  <span m='4443280'>equal.</span> <span m='4445500'>So</span> <span m='4445680'>first</span>
  <span m='4445920'>claim</span> <span m='4446700'>is</span> <span m='4446880'>this</span>
  <span m='4447090'>is,</span> <span m='4447240'>at</span> <span m='4447410'>most,</span>
  <span m='4450200'>this</span> <span m='4450630'>other</span> <span m='4450890'>thing--</span>
  <span m='4451870'>phi</span> <span m='4452220'>of</span> <span m='4452600'>t, y--</span>
  <span m='4454204'>phi</span> <span m='4454652'>of</span> <span m='4455100'>t,</span>
  <span m='4456090'>x,</span> <span m='4456570'>z.</span> <span m='4462970'>So</span>
  <span m='4463210'>I'm</span> <span m='4463300'>just</span> <span m='4463450'>replacing</span>
  <span m='4463720'>this</span> <span m='4463990'>y</span> <span m='4464470'>with</span>
  <span m='4464620'>an</span> <span m='4464710'>x.</span> </p><p><span m='4466432'>Why</span>
  <span m='4467260'>is</span> <span m='4467410'>this</span> <span m='4467560'>true?</span>
  <span m='4468520'>Because</span> <span m='4470680'>this</span> <span m='4470890'>is</span>
  <span m='4471130'>overtaking</span> <span m='4472820'>y.</span> <span m='4474200'>If</span>
  <span m='4474850'>you're</span> <span m='4474970'>going</span> <span m='4475090'>to</span>
  <span m='4475150'>overtake</span> <span m='4475660'>y</span> <span m='4476710'>at</span>
  <span m='4476800'>this</span> <span m='4476980'>time,</span> <span m='4477910'>you</span>
  <span m='4478060'>would</span> <span m='4478210'>overtake</span> <span m='4478660'>x</span>
  <span m='4478930'>at</span> <span m='4479020'>this</span> <span m='4479200'>time.</span>
  <span m='4479790'>Because</span> <span m='4479980'>x</span> <span m='4480160'>and</span>
  <span m='4480250'>y</span> <span m='4480370'>are</span> <span m='4480580'>equal</span>
  <span m='4480910'>right</span> <span m='4481090'>now.</span> <span m='4481650'>I'm</span>
  <span m='4481750'>pretty</span> <span m='4481930'>sure</span> <span m='4482080'>this</span>
  <span m='4482200'>is</span> <span m='4482290'>actually</span> <span m='4482560'>equal.</span>
  <span m='4482890'>I</span> <span m='4482920'>don't</span> <span m='4483070'>know</span>
  <span m='4483190'>why</span> <span m='4483370'>I</span> <span m='4483400'>wrote</span>
  <span m='4483760'>my</span> <span m='4483910'>notes</span> <span m='4484150'>"less
  than</span> <span m='4484410'>or equal</span> <span m='4484660'>to."</span> <span
  m='4485140'>Less</span> <span m='4485290'>than or equal to</span> <span m='4485550'>is</span>
  <span m='4485710'>all</span> <span m='4485830'>I</span> <span m='4485920'>need.</span>
  <span m='4486630'>But</span> <span m='4487010'>I</span> <span m='4487070'>think,</span>
  <span m='4487270'>at</span> <span m='4487360'>this</span> <span m='4487540'>moment</span>
  <span m='4487810'>in</span> <span m='4487930'>time,</span> <span m='4488170'>when</span>
  <span m='4488320'>they're</span> <span m='4488560'>actually</span> <span m='4489010'>equal</span>
  <span m='4489280'>to</span> <span m='4489430'>each</span> <span m='4489580'>other,</span>
  <span m='4491798'>it</span> <span m='4492270'>doesn't</span> <span m='4492520'>matter</span>
  <span m='4492760'>whether</span> <span m='4492910'>you</span> <span m='4493000'>have</span>
  <span m='4493150'>x</span> <span m='4493330'>and</span> <span m='4493420'>y</span>
  <span m='4493630'>here.</span> <span m='4493810'>You</span> <span m='4493960'>will</span>
  <span m='4494050'>overtake</span> <span m='4494440'>one</span> <span m='4494620'>if</span>
  <span m='4494740'>and</span> <span m='4494830'>only</span> <span m='4495040'>if</span>
  <span m='4495100'>you</span> <span m='4495340'>overtake</span> <span m='4495760'>the</span>
  <span m='4495880'>other</span> <span m='4496475'>at</span> <span m='4496800'>this
  moment.</span> </p><p><span m='4497580'>AUDIENCE:</span> <span m='4497810'>[INAUDIBLE]</span>
  </p><p><span m='4498500'>ERIK DEMAINE:</span> <span m='4498660'>No,</span> <span
  m='4498820'>I</span> <span m='4498910'>see.</span> <span m='4499210'>Right.</span>
  <span m='4499630'>Actually,</span> <span m='4500410'>this</span> <span m='4500590'>is</span>
  <span m='4500680'>about</span> <span m='4500860'>future</span> <span m='4501190'>time.</span>
  <span m='4502060'>In</span> <span m='4502180'>future</span> <span m='4502540'>time,</span>
  <span m='4502930'>we</span> <span m='4503050'>know</span> <span m='4503230'>that</span>
  <span m='4503380'>y</span> <span m='4503680'>is</span> <span m='4503830'>always</span>
  <span m='4504220'>going</span> <span m='4504370'>to</span> <span m='4504460'>be</span>
  <span m='4504700'>less</span> <span m='4505090'>than</span> <span m='4505270'>x,</span>
  <span m='4505600'>because</span> <span m='4505780'>it's</span> <span m='4505930'>moving</span>
  <span m='4506230'>up.</span> <span m='4507520'>In</span> <span m='4507640'>future</span>
  <span m='4507970'>time,</span> <span m='4508330'>if</span> <span m='4508570'>you</span>
  <span m='4508750'>overtake</span> <span m='4509290'>y,</span> <span m='4510070'>you'll</span>
  <span m='4510220'>certainly</span> <span m='4510670'>overtake</span> <span m='4511140'>x,</span>
  <span m='4512110'>because--</span> <span m='4513890'>no,</span> <span m='4514190'>the
  other</span> <span m='4514360'>way</span> <span m='4514540'>around.</span> <span
  m='4514710'>If</span> <span m='4514860'>you</span> <span m='4515040'>overtake</span>
  <span m='4515530'>x,</span> <span m='4516940'>meaning</span> <span m='4517360'>you</span>
  <span m='4517450'>go</span> <span m='4517660'>below</span> <span m='4518540'>x,</span>
  <span m='4520040'>one</span> <span m='4520540'>of</span> <span m='4520600'>these</span>
  <span m='4520750'>ways--</span> <span m='4522710'>overtaking</span> <span m='4523360'>is</span>
  <span m='4523480'>actually</span> <span m='4523930'>going</span> <span m='4524260'>up</span>
  <span m='4524470'>in</span> <span m='4524590'>the</span> <span m='4524680'>tree,</span>
  <span m='4524920'>but</span> <span m='4525070'>it's</span> <span m='4525190'>actually</span>
  <span m='4525430'>getting</span> <span m='4525640'>smaller</span> <span m='4526000'>in</span>
  <span m='4526090'>value.</span> </p><p><span m='4526900'>If</span> <span m='4527050'>you</span>
  <span m='4527140'>get</span> <span m='4527320'>smaller</span> <span m='4527800'>than</span>
  <span m='4527980'>y,</span> <span m='4528460'>you</span> <span m='4528580'>rise</span>
  <span m='4528850'>above</span> <span m='4529150'>y.</span> <span m='4529510'>That</span>
  <span m='4529720'>means</span> <span m='4529960'>you</span> <span m='4530080'>will</span>
  <span m='4530290'>have</span> <span m='4530530'>already</span> <span m='4530890'>risen</span>
  <span m='4531160'>above</span> <span m='4531460'>x.</span> <span m='4531730'>You</span>
  <span m='4531850'>already</span> <span m='4532240'>be</span> <span m='4533080'>a</span>
  <span m='4533200'>value</span> <span m='4533530'>smaller</span> <span m='4533950'>than</span>
  <span m='4534100'>x.</span> <span m='4535020'>So</span> <span m='4535300'>hopefully,</span>
  <span m='4535600'>that</span> <span m='4535750'>is</span> <span m='4535870'>the</span>
  <span m='4535960'>way</span> <span m='4536110'>that</span> <span m='4536180'>it's</span>
  <span m='4536320'>less</span> <span m='4536530'>than</span> <span m='4536650'>or</span>
  <span m='4536680'>equal</span> <span m='4536920'>to.</span> <span m='4538110'>Because</span>
  <span m='4538320'>that's</span> <span m='4538480'>what</span> <span m='4538570'>we</span>
  <span m='4538660'>need.</span> <span m='4539510'>OK,</span> <span m='4540400'>good.</span>
  <span m='4540610'>Now,</span> <span m='4540940'>I</span> <span m='4541000'>understand.</span>
  </p><p><span m='4542821'>AUDIENCE:</span> <span m='4542932'>So</span> <span m='4543043'>at</span>
  <span m='4543154'>this</span> <span m='4543268'>point,</span> <span m='4543715'>we're</span>
  <span m='4544162'>assuming</span> <span m='4544609'>affine?</span> </p><p><span
  m='4545510'>ERIK DEMAINE:</span> <span m='4545610'>We're</span> <span m='4545930'>assuming</span>
  <span m='4546270'>affine.</span> <span m='4546770'>Yeah.</span> <span m='4547180'>Sorry.</span>
  <span m='4548140'>Forgot</span> <span m='4548380'>to</span> <span m='4548440'>mention</span>
  <span m='4548710'>that.</span> <span m='4549700'>I</span> <span m='4549730'>think</span>
  <span m='4549910'>this</span> <span m='4550060'>works</span> <span m='4550240'>for</span>
  <span m='4550360'>pseudo</span> <span m='4550600'>algebraic,</span> <span m='4551130'>but</span>
  <span m='4551320'>this</span> <span m='4551530'>proof</span> <span m='4551890'>does</span>
  <span m='4552100'>not,</span> <span m='4553150'>assuming</span> <span m='4553510'>that</span>
  <span m='4553960'>x</span> <span m='4554140'>and</span> <span m='4554230'>y</span>
  <span m='4554380'>only</span> <span m='4554620'>switch</span> <span m='4554860'>places</span>
  <span m='4555220'>once.</span> </p><p><span m='4556860'>OK,</span> <span m='4557500'>then</span>
  <span m='4561430'>we</span> <span m='4561580'>have</span> <span m='4561730'>this</span>
  <span m='4561850'>simple</span> <span m='4562180'>equation,</span> <span m='4562630'>which</span>
  <span m='4562840'>is</span> <span m='4563060'>phi of</span> <span m='4563380'>t,</span>
  <span m='4563650'>x</span> <span m='4563920'>equals</span> <span m='4564210'>phi</span>
  <span m='4564500'>of</span> <span m='4564590'>t,</span> <span m='4565040'>x,</span>
  <span m='4565365'>y</span> <span m='4565690'>plus</span> <span m='4566050'>phi</span>
  <span m='4566200'>of</span> <span m='4566290'>t, x,</span> <span m='4566710'>z,</span>
  <span m='4567490'>where</span> <span m='4567580'>you</span> <span m='4567670'>just</span>
  <span m='4567820'>sum</span> <span m='4568060'>over</span> <span m='4568240'>the</span>
  <span m='4568360'>two</span> <span m='4568510'>children.</span> <span m='4569900'>So</span>
  <span m='4569950'>this</span> <span m='4570160'>is</span> <span m='4570310'>phi</span>
  <span m='4570560'>of</span> <span m='4570910'>t, x,</span> <span m='4571240'>z.</span>
  <span m='4572470'>So--</span> <span m='4573270'>I</span> <span m='4573440'>need</span>
  <span m='4573670'>more</span> <span m='4573850'>space,</span> <span m='4574420'>I
  guess.</span> </p><p><span m='4582550'>So</span> <span m='4582980'>phi</span> <span
  m='4583240'>of</span> <span m='4583440'>t, x,</span> <span m='4583855'>z,</span>
  <span m='4585100'>that</span> <span m='4585370'>is</span> <span m='4585580'>phi</span>
  <span m='4585790'>of</span> <span m='4585910'>t, x</span> <span m='4586720'>minus</span>
  <span m='4587440'>phi of</span> <span m='4587730'>t,</span> <span m='4588020'>x,</span>
  <span m='4588430'>y.</span> <span m='4590260'>So</span> <span m='4590680'>we</span>
  <span m='4590860'>have,</span> <span m='4592042'>let's</span> <span m='4592410'>say,</span>
  <span m='4592440'>on</span> <span m='4592695'>the</span> <span m='4592950'>left-hand</span>
  <span m='4593380'>side,</span> <span m='4595270'>is</span> <span m='4595630'>less</span>
  <span m='4596020'>than</span> <span m='4596500'>or</span> <span m='4596650'>equal</span>
  <span m='4596920'>to</span> <span m='4598440'>phi</span> <span m='4598750'>of</span>
  <span m='4598990'>t, y</span> <span m='4601900'>plus--</span> <span m='4603490'>this</span>
  <span m='4603670'>is</span> <span m='4603850'>what</span> <span m='4604240'>we</span>
  <span m='4604300'>had</span> <span m='4604450'>before--</span> <span m='4604840'>t
  of x,</span> <span m='4605250'>z.</span> <span m='4606090'>But</span> <span m='4606250'>now,</span>
  <span m='4606760'>that</span> <span m='4607000'>is</span> <span m='4607120'>the</span>
  <span m='4607180'>same</span> <span m='4607510'>as</span> <span m='4607660'>phi</span>
  <span m='4607915'>of</span> <span m='4608170'>t, x</span> <span m='4608650'>minus</span>
  <span m='4609190'>the</span> <span m='4609310'>other</span> <span m='4609520'>child.</span>
  <span m='4614700'>Sorry--</span> <span m='4615190'>y.</span> <span m='4618230'>OK,</span>
  <span m='4618550'>that</span> <span m='4618730'>was</span> <span m='4618910'>just</span>
  <span m='4619090'>that</span> <span m='4619300'>equation.</span> </p><p><span m='4621340'>Now,</span>
  <span m='4621610'>do</span> <span m='4621760'>things</span> <span m='4622060'>simplify?</span>
  <span m='4622690'>Hope</span> <span m='4622870'>so.</span> <span m='4624124'>Phi</span>
  <span m='4624541'>of</span> <span m='4624960'>t, y--</span> <span m='4630370'>these</span>
  <span m='4630610'>two</span> <span m='4630760'>things--</span> <span m='4636170'>OK.</span>
  <span m='4638330'>Not</span> <span m='4638500'>so</span> <span m='4638600'>pretty.</span>
  <span m='4639890'>What</span> <span m='4640100'>we</span> <span m='4640250'>care</span>
  <span m='4640460'>about</span> <span m='4642050'>is</span> <span m='4642260'>the</span>
  <span m='4642350'>sum</span> <span m='4642620'>of</span> <span m='4642710'>these</span>
  <span m='4642890'>things.</span> <span m='4644950'>We</span> <span m='4645100'>care</span>
  <span m='4645290'>about</span> <span m='4645470'>sum--</span> <span m='4645830'>the</span>
  <span m='4645920'>overall</span> <span m='4646280'>potential.</span> </p><p><span
  m='4648960'>So</span> <span m='4649070'>we</span> <span m='4649220'>want</span>
  <span m='4649460'>phi of</span> <span m='4649910'>t-plus</span> <span m='4651410'>is</span>
  <span m='4652300'>phi of</span> <span m='4652680'>t</span> <span m='4654770'>plus</span>
  <span m='4654980'>something.</span> <span m='4656270'>How</span> <span m='4656480'>it</span>
  <span m='4656570'>changes</span> <span m='4657020'>is,</span> <span m='4657910'>well,</span>
  <span m='4658970'>how</span> <span m='4659210'>does</span> <span m='4659510'>phi</span>
  <span m='4659860'>of t</span> <span m='4660740'>prime</span> <span m='4661520'>x</span>
  <span m='4661840'>change?</span> <span m='4662780'>Well,</span> <span m='4662890'>it</span>
  <span m='4662960'>went</span> <span m='4663110'>down</span> <span m='4663320'>a</span>
  <span m='4663380'>lot.</span> <span m='4663590'>It</span> <span m='4663650'>went</span>
  <span m='4663830'>all</span> <span m='4663920'>the</span> <span m='4664010'>way</span>
  <span m='4664100'>down</span> <span m='4664280'>to</span> <span m='4664370'>phi
  of</span> <span m='4664670'>t,</span> <span m='4664970'>x,</span> <span m='4665270'>y.</span>
  <span m='4667990'>Well,</span> <span m='4668110'>actually,</span> <span m='4668410'>we</span>
  <span m='4668500'>just</span> <span m='4669180'>add</span> <span m='4669400'>these</span>
  <span m='4669580'>together.</span> <span m='4672390'>Add them</span> <span m='4672750'>up.</span>
  <span m='4674160'>This is</span> <span m='4674630'>messy.</span> <span m='4674900'>Sorry.</span>
  </p><p><span m='4680500'>Let's</span> <span m='4680680'>look</span> <span m='4680830'>at</span>
  <span m='4680890'>this</span> <span m='4681040'>sum--</span> <span m='4682280'>phi</span>
  <span m='4682700'>of</span> <span m='4682900'>t</span> <span m='4683620'>plus</span>
  <span m='4685210'>x</span> <span m='4685540'>and</span> <span m='4685780'>y.</span>
  <span m='4687250'>So</span> <span m='4687460'>we</span> <span m='4687580'>get</span>
  <span m='4687790'>this</span> <span m='4688030'>thing--</span> <span m='4689290'>phi
  of</span> <span m='4690850'>t,</span> <span m='4691160'>x,</span> <span m='4691590'>y</span>
  <span m='4693810'>minus</span> <span m='4694170'>1.</span> <span m='4695210'>And</span>
  <span m='4695310'>then</span> <span m='4695320'>we</span> <span m='4695410'>get</span>
  <span m='4695620'>this</span> <span m='4695830'>thing--</span> <span m='4696170'>so</span>
  <span m='4696430'>phi</span> <span m='4696850'>of</span> <span m='4697900'>t, y,</span>
  <span m='4699640'>plus</span> <span m='4700110'>phi</span> <span m='4700390'>of</span>
  <span m='4700840'>t,</span> <span m='4701140'>x,</span> <span m='4702760'>minus</span>
  <span m='4703480'>phi</span> <span m='4703750'>of</span> <span m='4705040'>t, x,</span>
  <span m='4705430'>y.</span> <span m='4707220'>It's an</span> <span m='4707410'>elaborate</span>
  <span m='4707800'>way</span> <span m='4707950'>of</span> <span m='4708040'>saying</span>
  <span m='4708730'>this</span> <span m='4709060'>cancels</span> <span m='4709390'>with</span>
  <span m='4709720'>this.</span> </p><p><span m='4711220'>So</span> <span m='4711370'>we</span>
  <span m='4711460'>are</span> <span m='4711550'>left</span> <span m='4711820'>with</span>
  <span m='4711970'>the</span> <span m='4712120'>old</span> <span m='4712420'>value--</span>
  <span m='4713200'>phi of</span> <span m='4713650'>t, x,</span> <span m='4713860'>plus</span>
  <span m='4714070'>phi of</span> <span m='4714460'>t, y,</span> <span m='4715030'>minus</span>
  <span m='4715420'>1.</span> <span m='4716690'>So</span> <span m='4716710'>that</span>
  <span m='4716890'>means</span> <span m='4717790'>phi--</span> <span m='4718990'>sorry,</span>
  <span m='4719200'>this</span> <span m='4719350'>is</span> <span m='4719440'>less</span>
  <span m='4719670'>than or equal</span> <span m='4719980'>to.</span> <span m='4722650'>This</span>
  <span m='4722860'>means</span> <span m='4723100'>phi of</span> <span m='4723490'>t-plus</span>
  <span m='4724090'>is</span> <span m='4724240'>less</span> <span m='4724510'>than
  or equal</span> <span m='4724840'>phi</span> <span m='4725590'>of</span> <span m='4726160'>t</span>
  <span m='4727090'>minus</span> <span m='4727510'>1.</span> <span m='4728210'>In</span>
  <span m='4728560'>other</span> <span m='4728710'>words,</span> <span m='4729080'>every</span>
  <span m='4729250'>time</span> <span m='4729490'>an</span> <span m='4729580'>event</span>
  <span m='4729880'>happens,</span> <span m='4730990'>the</span> <span m='4731110'>potential</span>
  <span m='4731500'>goes</span> <span m='4731680'>down</span> <span m='4731920'>by</span>
  <span m='4732070'>at</span> <span m='4732130'>least</span> <span m='4732520'>one.</span>
  <span m='4734710'>This</span> <span m='4734920'>is</span> <span m='4735010'>basically</span>
  <span m='4735370'>confirming</span> <span m='4735970'>this</span> <span m='4736150'>intuition,</span>
  <span m='4737200'>but</span> <span m='4738430'>roughly.</span> </p><p><span m='4740020'>But</span>
  <span m='4740170'>our</span> <span m='4740260'>definition</span> <span m='4740710'>was</span>
  <span m='4740860'>this--</span> <span m='4741175'>the</span> <span m='4741490'>number</span>
  <span m='4741730'>of</span> <span m='4742210'>descendants</span> <span m='4742660'>of</span>
  <span m='4742780'>x</span> <span m='4743230'>that</span> <span m='4743650'>overtake</span>
  <span m='4744160'>x</span> <span m='4744430'>in</span> <span m='4744490'>the</span>
  <span m='4744580'>future.</span> <span m='4746761'>How</span> <span m='4747160'>big</span>
  <span m='4747430'>could</span> <span m='4747610'>this</span> <span m='4747790'>thing</span>
  <span m='4748000'>be?</span> <span m='4749140'>It</span> <span m='4749230'>is,</span>
  <span m='4749350'>at</span> <span m='4749440'>most,</span> <span m='4749780'>the</span>
  <span m='4749800'>sum</span> <span m='4750040'>over</span> <span m='4750300'>all</span>
  <span m='4750480'>nodes</span> <span m='4750790'>of the</span> <span m='4750880'>number</span>
  <span m='4751210'>of</span> <span m='4751300'>descendants</span> <span m='4751840'>of</span>
  <span m='4751960'>that</span> <span m='4752110'>node.</span> <span m='4753160'>So
  it is,</span> <span m='4753340'>by</span> <span m='4753550'>definition,</span> <span
  m='4754120'>at</span> <span m='4754210'>most,</span> <span m='4754450'>n</span>
  <span m='4754600'>log</span> <span m='4754810'>n.</span> <span m='4756520'>If</span>
  <span m='4756610'>we</span> <span m='4756700'>look</span> <span m='4756880'>at</span>
  <span m='4757000'>phi</span> <span m='4757210'>of</span> <span m='4757280'>0,</span>
  <span m='4759820'>it's</span> <span m='4761050'>order</span> <span m='4761290'>n</span>
  <span m='4761440'>log</span> <span m='4761710'>n.</span> </p><p><span m='4761820'>And
  what we're doing</span> <span m='4762030'>is using</span> <span m='4762420'>a</span>
  <span m='4762480'>balanced</span> <span m='4762800'>heap</span> <span m='4763030'>here.</span>
  <span m='4764210'>And</span> <span m='4764310'>so</span> <span m='4765460'>for</span>
  <span m='4765910'>order</span> <span m='4766210'>n</span> <span m='4766350'>log</span>
  <span m='4766540'>n,</span> <span m='4766720'>initially,</span> <span m='4767230'>in</span>
  <span m='4767320'>every</span> <span m='4767740'>event</span> <span m='4768070'>that</span>
  <span m='4768190'>happens,</span> <span m='4768490'>we</span> <span m='4768580'>go</span>
  <span m='4768700'>down</span> <span m='4768830'>by</span> <span m='4769000'>one.</span>
  <span m='4769570'>And</span> <span m='4769600'>we're</span> <span m='4769690'>never</span>
  <span m='4770620'>negative.</span> <span m='4771690'>That</span> <span m='4772030'>thing</span>
  <span m='4772210'>is</span> <span m='4772330'>always</span> <span m='4772810'>non-negative.</span>
  <span m='4774360'>Then</span> <span m='4774490'>the</span> <span m='4774580'>number</span>
  <span m='4774850'>of</span> <span m='4774970'>events</span> <span m='4775300'>is,</span>
  <span m='4775390'>at</span> <span m='4775480'>most,</span> <span m='4775720'>order</span>
  <span m='4775940'>n</span> <span m='4776100'>log</span> <span m='4776513'>n.</span>
  <span m='4777340'>Cool?</span> <span m='4779010'>OK,</span> <span m='4779740'>I</span>
  <span m='4779880'>only</span> <span m='4780010'>have</span> <span m='4780100'>one</span>
  <span m='4780250'>more</span> <span m='4780370'>page</span> <span m='4780640'>of</span>
  <span m='4780700'>notes</span> <span m='4780940'>to</span> <span m='4781030'>cover</span>
  <span m='4781360'>in</span> <span m='4781600'>zero</span> <span m='4781960'>minutes--</span>
  <span m='4782770'>about</span> <span m='4783180'>15</span> <span m='4783550'>seconds.</span>
  </p><p><span m='4784820'>Let</span> <span m='4784840'>me</span> <span m='4784990'>quickly</span>
  <span m='4785500'>tell</span> <span m='4785770'>you</span> <span m='4786040'>about</span>
  <span m='4786820'>what's</span> <span m='4787030'>on</span> <span m='4787180'>this</span>
  <span m='4787330'>page,</span> <span m='4787690'>and</span> <span m='4787780'>you</span>
  <span m='4787900'>can</span> <span m='4788020'>read</span> <span m='4788230'>it</span>
  <span m='4788410'>at</span> <span m='4788530'>home.</span> <span m='4789730'>It's</span>
  <span m='4789910'>a</span> <span m='4789970'>little</span> <span m='4790180'>survey</span>
  <span m='4790660'>of</span> <span m='4790900'>lots</span> <span m='4791170'>of</span>
  <span m='4791230'>different</span> <span m='4791470'>kinetic</span> <span m='4791800'>data</span>
  <span m='4792010'>structures,</span> <span m='4792910'>in</span> <span m='4793030'>particular,</span>
  <span m='4793540'>for</span> <span m='4794350'>more</span> <span m='4794620'>than</span>
  <span m='4794740'>one</span> <span m='4794920'>dimension.</span> <span m='4796330'>So</span>
  <span m='4796540'>there's</span> <span m='4796690'>a</span> <span m='4796750'>lot</span>
  <span m='4796900'>of</span> <span m='4796990'>work</span> <span m='4797230'>on</span>
  <span m='4797590'>2D</span> <span m='4797980'>convex</span> <span m='4798410'>hull.
  You have</span> <span m='4798700'>moving</span> <span m='4799030'>points</span>
  <span m='4799330'>in</span> <span m='4799390'>two</span> <span m='4799540'>dimensions.</span>
  <span m='4799990'>You</span> <span m='4800050'>want</span> <span m='4800200'>to</span>
  <span m='4800260'>maintain</span> <span m='4800710'>the</span> <span m='4800800'>convex</span>
  <span m='4801160'>hull.</span> </p><p><span m='4802120'>The</span> <span m='4802240'>number</span>
  <span m='4802600'>of</span> <span m='4802690'>events--</span> <span m='4803920'>the</span>
  <span m='4804040'>best</span> <span m='4804430'>we</span> <span m='4804610'>know</span>
  <span m='4804850'>how</span> <span m='4804970'>to</span> <span m='4805120'>achieve</span>
  <span m='4805660'>is</span> <span m='4805900'>order</span> <span m='4806590'>n to</span>
  <span m='4806890'>the</span> <span m='4807040'>two</span> <span m='4807280'>plus</span>
  <span m='4807580'>epsilon--</span> <span m='4808420'>a</span> <span m='4808570'>little</span>
  <span m='4808810'>bit</span> <span m='4808900'>bigger</span> <span m='4809110'>than</span>
  <span m='4809240'>n</span> <span m='4809360'>squared.</span> <span m='4810420'>And</span>
  <span m='4810550'>there's</span> <span m='4810700'>a</span> <span m='4810730'>lower</span>
  <span m='4811000'>bound</span> <span m='4811240'>that</span> <span m='4811360'>it</span>
  <span m='4811420'>can</span> <span m='4811570'>change</span> <span m='4811990'>n</span>
  <span m='4812140'>squared</span> <span m='4812410'>times.</span> <span m='4813100'>So</span>
  <span m='4813190'>it's</span> <span m='4813340'>almost</span> <span m='4813760'>optimal--</span>
  <span m='4815590'>unknown</span> <span m='4816040'>how</span> <span m='4816160'>to</span>
  <span m='4816250'>do</span> <span m='4816370'>that</span> <span m='4816550'>in</span>
  <span m='4816610'>3D.</span> </p><p><span m='4818680'>A</span> <span m='4818740'>problem</span>
  <span m='4819040'>that</span> <span m='4819130'>we</span> <span m='4819280'>solved</span>
  <span m='4819760'>in</span> <span m='4819970'>the</span> <span m='4820060'>open</span>
  <span m='4820240'>problems</span> <span m='4820750'>in</span> <span m='4820840'>this</span>
  <span m='4820990'>class</span> <span m='4821800'>two</span> <span m='4822040'>years</span>
  <span m='4822280'>ago</span> <span m='4822700'>is</span> <span m='4822940'>smallest</span>
  <span m='4823195'>enclosing</span> <span m='4823930'>disk.</span> <span m='4824360'>So
  you</span> <span m='4824680'>have</span> <span m='4824790'>points</span> <span m='4825160'>moving</span>
  <span m='4825610'>in</span> <span m='4825760'>the</span> <span m='4825850'>plane,</span>
  <span m='4826750'>and</span> <span m='4827140'>you</span> <span m='4827290'>want</span>
  <span m='4827500'>to</span> <span m='4827590'>maintain,</span> <span m='4828040'>what</span>
  <span m='4828190'>is</span> <span m='4828280'>the</span> <span m='4828340'>smallest</span>
  <span m='4828700'>enclosing</span> <span m='4829080'>disk</span> <span m='4829330'>of</span>
  <span m='4829420'>those</span> <span m='4829630'>points?</span> <span m='4830440'>Number</span>
  <span m='4830680'>of</span> <span m='4830780'>events</span> <span m='4830960'>we</span>
  <span m='4831070'>got</span> <span m='4831220'>was</span> <span m='4831360'>n</span>
  <span m='4831550'>to</span> <span m='4831700'>the</span> <span m='4831850'>3</span>
  <span m='4832180'>plus</span> <span m='4832450'>epsilon,</span> <span m='4833000'>which</span>
  <span m='4833080'>is</span> <span m='4833200'>a</span> <span m='4833290'>little</span>
  <span m='4833530'>bit</span> <span m='4833650'>painful.</span> <span m='4834460'>Best</span>
  <span m='4834670'>lower</span> <span m='4834910'>round</span> <span m='4835100'>is
  n</span> <span m='4835410'>squared--</span> <span m='4836200'>so</span> <span m='4836380'>still</span>
  <span m='4836590'>a</span> <span m='4836650'>gap</span> <span m='4836950'>there.</span>
  </p><p><span m='4837800'>Those</span> <span m='4837970'>closely</span> <span m='4838360'>related</span>
  <span m='4838720'>to</span> <span m='4838810'>another</span> <span m='4839140'>open</span>
  <span m='4839350'>problem,</span> <span m='4839870'>which</span> <span m='4839950'>is,</span>
  <span m='4840070'>you</span> <span m='4840190'>want</span> <span m='4840340'>to</span>
  <span m='4840400'>maintain</span> <span m='4840790'>something</span> <span m='4841090'>called</span>
  <span m='4841270'>a</span> <span m='4841330'>Delaunay</span> <span m='4841780'>triangulation.</span>
  <span m='4842530'>If</span> <span m='4842860'>you</span> <span m='4842920'>know</span>
  <span m='4843010'>what</span> <span m='4843100'>that</span> <span m='4843250'>is,</span>
  <span m='4843400'>great.</span> <span m='4843770'>If</span> <span m='4843820'>not,</span>
  <span m='4844520'>it's</span> <span m='4844630'>a</span> <span m='4844720'>big</span>
  <span m='4844960'>open</span> <span m='4845200'>problem--</span> <span m='4846080'>how</span>
  <span m='4846160'>many</span> <span m='4846370'>times</span> <span m='4846730'>can</span>
  <span m='4846880'>the</span> <span m='4846970'>Delaunay</span> <span m='4847330'>triangulation</span>
  <span m='4847900'>change</span> <span m='4849070'>if</span> <span m='4849250'>you</span>
  <span m='4849370'>have</span> <span m='4849550'>just</span> <span m='4849730'>points</span>
  <span m='4850000'>moving</span> <span m='4850270'>along</span> <span m='4850480'>straight</span>
  <span m='4850690'>lines?</span> <span m='4851410'>Best</span> <span m='4851620'>upper</span>
  <span m='4851830'>bound</span> <span m='4852010'>is</span> <span m='4852220'>n cubed.</span>
  <span m='4852550'>Best</span> <span m='4852790'>lower</span> <span m='4852970'>bound</span>
  <span m='4853150'>is</span> <span m='4853250'>n</span> <span m='4853410'>squared--</span>
  <span m='4853850'>so</span> <span m='4853970'>similar</span> <span m='4854500'>linear</span>
  <span m='4854830'>gap.</span> </p><p><span m='4855820'>If</span> <span m='4855880'>you</span>
  <span m='4855940'>just</span> <span m='4856120'>want</span> <span m='4856270'>to</span>
  <span m='4856330'>maintain</span> <span m='4856690'>some</span> <span m='4857050'>triangulation</span>
  <span m='4857680'>on</span> <span m='4857770'>your</span> <span m='4857890'>points,</span>
  <span m='4859370'>you</span> <span m='4859600'>can</span> <span m='4859750'>do</span>
  <span m='4859840'>better.</span> <span m='4860390'>Best</span> <span m='4860500'>upper</span>
  <span m='4860670'>bound</span> <span m='4860790'>is</span> <span m='4860960'>n</span>
  <span m='4861130'>to</span> <span m='4861260'>the</span> <span m='4861430'>2.33333.</span>
  <span m='4863490'>Best</span> <span m='4863800'>lower</span> <span m='4864030'>bound</span>
  <span m='4864260'>is</span> <span m='4864460'>n</span> <span m='4864760'>squared.</span>
  <span m='4865060'>So</span> <span m='4865330'>a</span> <span m='4865360'>smaller</span>
  <span m='4865780'>gap--</span> <span m='4867710'>just</span> <span m='4867880'>cube
  root</span> <span m='4868200'>of</span> <span m='4868300'>n</span> <span m='4868480'>gap.</span>
  </p><p><span m='4870460'>Collision</span> <span m='4870910'>detection</span> <span
  m='4871420'>is</span> <span m='4871540'>probably</span> <span m='4871870'>the</span>
  <span m='4871990'>most</span> <span m='4872260'>obvious</span> <span m='4872530'>application</span>
  <span m='4873070'>here.</span> <span m='4873640'>You</span> <span m='4873730'>have</span>
  <span m='4873830'>a</span> <span m='4873850'>video</span> <span m='4874160'>game.</span>
  <span m='4875320'>Things</span> <span m='4875560'>are</span> <span m='4875650'>moving</span>
  <span m='4876460'>with</span> <span m='4876580'>known</span> <span m='4876940'>velocities.</span>
  <span m='4878320'>You</span> <span m='4878500'>update</span> <span m='4878890'>those</span>
  <span m='4879040'>velocities--</span> <span m='4879310'>like,</span> <span m='4879580'>you
  have</span> <span m='4879820'>bullets,</span> <span m='4880390'>and</span> <span
  m='4880510'>people</span> <span m='4880990'>running</span> <span m='4881260'>around,</span>
  <span m='4881530'>and whatever</span> <span m='4881770'>you</span> <span m='4881860'>want</span>
  <span m='4882010'>to</span> <span m='4882070'>know</span> <span m='4882220'>when</span>
  <span m='4882310'>they</span> <span m='4882400'>bounce</span> <span m='4882670'>into</span>
  <span m='4882850'>each</span> <span m='4883000'>other--</span> <span m='4883210'>walls,</span>
  <span m='4883570'>which</span> <span m='4883720'>are</span> <span m='4883780'>stationary.</span>
  <span m='4884920'>When</span> <span m='4885100'>does</span> <span m='4885220'>that</span>
  <span m='4885370'>happen?</span> <span m='4886210'>There's</span> <span m='4886600'>pretty</span>
  <span m='4886990'>good</span> <span m='4887170'>algorithms</span> <span m='4887590'>for</span>
  <span m='4887980'>kinetic</span> <span m='4888310'>collision</span> <span m='4888640'>detection.</span>
  <span m='4889060'>Although,</span> <span m='4889720'>it's</span> <span m='4889840'>very</span>
  <span m='4890110'>unclear</span> <span m='4890500'>what</span> <span m='4890710'>efficient</span>
  <span m='4891160'>means.</span> </p><p><span m='4892810'>Because</span> <span m='4893050'>you</span>
  <span m='4893620'>want</span> <span m='4893770'>to</span> <span m='4893860'>optimize</span>
  <span m='4894280'>for</span> <span m='4894370'>the</span> <span m='4894460'>case</span>
  <span m='4894670'>when</span> <span m='4894780'>not</span> <span m='4894940'>many</span>
  <span m='4895120'>collisions</span> <span m='4895480'>happen.</span> <span m='4896500'>And</span>
  <span m='4896650'>these</span> <span m='4897520'>algorithms</span> <span m='4897940'>do--</span>
  <span m='4898360'>in</span> <span m='4898480'>a</span> <span m='4898510'>certain</span>
  <span m='4898990'>sense,</span> <span m='4899290'>they're</span> <span m='4899410'>optimal.</span>
  <span m='4899800'>But</span> <span m='4899890'>it's</span> <span m='4900130'>much</span>
  <span m='4900340'>harder</span> <span m='4900550'>to</span> <span m='4900700'>state</span>
  <span m='4900970'>what</span> <span m='4901090'>that</span> <span m='4901270'>sense</span>
  <span m='4901560'>is.</span> <span m='4902950'>Minimum</span> <span m='4903280'>spanning</span>
  <span m='4903730'>tree</span> <span m='4903910'>is</span> <span m='4904000'>another</span>
  <span m='4904240'>one</span> <span m='4904360'>I</span> <span m='4904420'>have.</span>
  <span m='4904630'>This</span> <span m='4904850'>is</span> <span m='4905800'>tough.</span>
  <span m='4906580'>Easy</span> <span m='4906850'>thing</span> <span m='4907000'>to</span>
  <span m='4907090'>do</span> <span m='4907270'>is,</span> <span m='4907600'>you do</span>
  <span m='4907870'>kinetic</span> <span m='4908230'>predecessor</span> <span m='4909400'>on</span>
  <span m='4909610'>the</span> <span m='4909730'>entire</span> <span m='4910210'>sorted</span>
  <span m='4910540'>order</span> <span m='4910810'>of</span> <span m='4910960'>the</span>
  <span m='4911110'>edge</span> <span m='4911380'>lengths.</span> <span m='4912590'>And</span>
  <span m='4912610'>then</span> <span m='4912760'>you</span> <span m='4912850'>just</span>
  <span m='4913030'>run</span> <span m='4913360'>a</span> <span m='4914080'>[? stem
  ?]</span> <span m='4914530'>thing</span> <span m='4914740'>that</span> <span m='4914860'>processes</span>
  <span m='4915460'>the</span> <span m='4916000'>edges</span> <span m='4916300'>in</span>
  <span m='4916420'>order.</span> <span m='4917440'>So</span> <span m='4917590'>that</span>
  <span m='4917740'>gets</span> <span m='4917920'>a</span> <span m='4917980'>quadratic</span>
  <span m='4918430'>number</span> <span m='4918670'>of</span> <span m='4918730'>events.</span>
  <span m='4919060'>It's</span> <span m='4919210'>unknown</span> <span m='4919540'>whether</span>
  <span m='4919720'>you</span> <span m='4919780'>can</span> <span m='4919930'>do</span>
  <span m='4920050'>any</span> <span m='4920230'>better</span> <span m='4920530'>for</span>
  <span m='4920660'>minimum</span> <span m='4920950'>spanning</span> <span m='4921310'>tree.</span>
  </p><p><span m='4922280'>So</span> <span m='4922460'>that</span> <span m='4922640'>was
  your</span> <span m='4922750'>quick</span> <span m='4923530'>survey</span> <span
  m='4924040'>of</span> <span m='4924220'>kinetic.</span> <span m='4925080'>And</span>
  <span m='4925240'>that</span> <span m='4925420'>ends</span> <span m='4925750'>geometry.</span>
  <span m='4927550'>The end.</span> </p>
type: course
uid: 552da32ec5bd3c68ad33cdd36c4e1075

---
None
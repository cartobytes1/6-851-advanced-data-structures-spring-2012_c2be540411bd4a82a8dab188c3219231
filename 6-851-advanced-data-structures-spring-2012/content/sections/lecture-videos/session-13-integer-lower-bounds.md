---
about_this_resource_text: <p><strong>Description:</strong> Integer data structure
  lower bounds. In particular, we'll prove that the min of van Emde Boas and fusion
  trees is an optimal (static) predecessor data structure up to a log log factor,
  assuming polynomial space.</p> <p><strong>Speaker:</strong> Prof. Erik Demaine</p>
course_id: 6-851-advanced-data-structures-spring-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: RecEYrnvGPM
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Video-YouTube-Stream
  type: Video
  uid: c969a1d40d389b33ca3348757656cfc8
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/session-13-integer-lower-bounds/id735348884?i=169609956
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Video-iTunes U-MP4
  type: Video
  uid: 3c8e43383b04d1c3d3344a5772d9b932
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.851S12/MIT6_851S12_lec13_300k.mp4
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Video-Internet Archive-MP4
  type: Video
  uid: 494a3c8d1737f3899bfdcedff9446abe
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/RecEYrnvGPM/default.jpg
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4d56b165991172ad881e7ea593dfabb6
- id: 3Play-3PlayYouTubeid-MP4
  media_location: RecEYrnvGPM
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9ccf388adc69ca2e86efe2486ca9a7ce
- id: RecEYrnvGPM.srt
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-13-integer-lower-bounds/RecEYrnvGPM.srt
  title: 3play caption file
  type: null
  uid: fe684a14377ca927725a254218561e5e
- id: RecEYrnvGPM.pdf
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-13-integer-lower-bounds/RecEYrnvGPM.pdf
  title: 3play pdf file
  type: null
  uid: dec3efe2e8cf65c58d8d3f3a8a38b1ad
- id: Caption-3Play YouTube id-SRT
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 27b39f85555141764886c0e9e76bda8d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 14f25333bd634c2ae841e5e17ce09c04
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: fed85518a722b038289fd92beb941e9a
inline_embed_id: 64781179session13:integerlowerbounds40013095
layout: video
order_index: null
parent_uid: b66cbbb7b35e74ff17cdbf44e5fb6b1d
related_resources_text: ''
short_url: session-13-integer-lower-bounds
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2012/lecture-videos/session-13-integer-lower-bounds
template_type: Tabbed
title: 'Session 13: Integer Lower Bounds'
transcript: <p><span m='90'>The</span> <span m='180'>following</span> <span m='630'>content</span>
  <span m='1200'>is</span> <span m='1320'>provided</span> <span m='1770'>under</span>
  <span m='2009'>a</span> <span m='2070'>Creative</span> <span m='2490'>Commons</span>
  <span m='2910'>license.</span> <span m='4030'>Your</span> <span m='4200'>support</span>
  <span m='4710'>will</span> <span m='4860'>help</span> <span m='5100'>MIT</span>
  <span m='5550'>OpenCourseWare</span> <span m='6360'>continue</span> <span m='6870'>to</span>
  <span m='6960'>offer</span> <span m='7380'>high</span> <span m='7620'>quality</span>
  <span m='8100'>educational</span> <span m='8730'>resources</span> <span m='9330'>for</span>
  <span m='9510'>free.</span> <span m='10720'>To</span> <span m='10740'>make</span>
  <span m='10920'>a</span> <span m='10980'>donation</span> <span m='11730'>or</span>
  <span m='11940'>view</span> <span m='12390'>additional</span> <span m='12810'>materials</span>
  <span m='13320'>from</span> <span m='13500'>hundreds</span> <span m='13920'>of</span>
  <span m='14040'>MIT</span> <span m='14460'>courses,</span> <span m='15550'>visit</span>
  <span m='15780'>MIT</span> <span m='16200'>OpenCourseWare</span> <span m='17280'>at</span>
  <span m='17430'>ocw.mit.edu.</span> </p><p><span m='21310'>ERIK DEMAINE:</span>
  <span m='21340'>All</span> <span m='21370'>right,</span> <span m='21520'>today</span>
  <span m='21850'>is</span> <span m='22000'>our</span> <span m='22150'>last</span>
  <span m='22540'>lecture</span> <span m='22960'>on</span> <span m='23290'>the</span>
  <span m='23380'>predecessor</span> <span m='24010'>problem.</span> <span m='24820'>And</span>
  <span m='25520'>we</span> <span m='25740'>did</span> <span m='25930'>two</span>
  <span m='26170'>lectures</span> <span m='26530'>on</span> <span m='26770'>upper</span>
  <span m='27010'>bound,</span> <span m='27400'>started</span> <span m='27820'>with</span>
  <span m='28210'>Van</span> <span m='28450'>Emde</span> <span m='28760'>Boas</span>
  <span m='29190'>x-Fast,</span> <span m='29680'>y-Fast</span> <span m='30100'>tries.</span>
  <span m='31000'>And</span> <span m='31150'>then</span> <span m='32830'>fusion</span>
  <span m='33190'>tries was</span> <span m='33580'>last</span> <span m='33850'>class.</span>
  </p><p><span m='34750'>This</span> <span m='34900'>time,</span> <span m='35110'>we're</span>
  <span m='35170'>going</span> <span m='35290'>to</span> <span m='35350'>show</span>
  <span m='35590'>that</span> <span m='35770'>those</span> <span m='36010'>bounds</span>
  <span m='36340'>are</span> <span m='36430'>essentially</span> <span m='37000'>optimal.</span>
  <span m='38170'>And</span> <span m='38500'>we're</span> <span m='38620'>going</span>
  <span m='38690'>to</span> <span m='38800'>prove</span> <span m='39760'>this</span>
  <span m='39970'>bound.</span> <span m='41020'>So</span> <span m='41140'>we</span>
  <span m='41260'>currently</span> <span m='41560'>have</span> <span m='41890'>min</span>
  <span m='42460'>of</span> <span m='42850'>log</span> <span m='43240'>w,</span> <span
  m='44160'>and</span> <span m='44280'>log</span> <span m='44500'>base</span> <span
  m='44710'>w</span> <span m='45010'>of</span> <span m='45100'>n</span> <span m='45340'>as</span>
  <span m='45430'>an</span> <span m='45550'>upper</span> <span m='45820'>bound.</span>
  <span m='46600'>That</span> <span m='46750'>was Van</span> <span m='47080'>Emde</span>
  <span m='47410'>Boas</span> <span m='47810'>and</span> <span m='47920'>fusion</span>
  <span m='48250'>tires.</span> </p><p><span m='48980'>Were</span> <span m='49080'>going</span>
  <span m='49170'>to</span> <span m='49250'>prove an</span> <span m='49540'>almost</span>
  <span m='49900'>matching</span> <span m='50290'>lower</span> <span m='50500'>bound.</span>
  <span m='50750'>There's</span> <span m='50920'>a</span> <span m='50980'>log</span>
  <span m='51310'>log</span> <span m='51550'>w</span> <span m='51910'>factor</span>
  <span m='52330'>here.</span> <span m='53230'>And</span> <span m='53410'>this</span>
  <span m='53590'>bound</span> <span m='53860'>holds</span> <span m='54460'>for</span>
  <span m='55180'>even</span> <span m='55450'>a</span> <span m='55510'>static</span>
  <span m='56260'>predecessor</span> <span m='56830'>data</span> <span m='57010'>structure</span>
  <span m='57460'>no</span> <span m='57700'>updates,</span> <span m='59080'>as</span>
  <span m='59230'>long</span> <span m='59470'>as</span> <span m='59560'>the</span>
  <span m='59650'>data</span> <span m='59800'>structure</span> <span m='60100'>has</span>
  <span m='60250'>polynomial</span> <span m='60880'>space,</span> <span m='62070'>which</span>
  <span m='62470'>if</span> <span m='62560'>you</span> <span m='62620'>have</span>
  <span m='62740'>any</span> <span m='62980'>hope</span> <span m='63220'>of</span>
  <span m='63310'>making</span> <span m='63610'>something</span> <span m='63940'>dynamic,</span>
  <span m='64510'>you</span> <span m='64620'>definitely</span> <span m='64900'>want</span>
  <span m='65080'>polynomial</span> <span m='65590'>space.</span> </p><p><span m='66400'>Now,</span>
  <span m='66550'>it's</span> <span m='66670'>known</span> <span m='67090'>that</span>
  <span m='67270'>this</span> <span m='67420'>log</span> <span m='67630'>log</span>
  <span m='67810'>factor</span> <span m='68170'>is</span> <span m='68260'>not</span>
  <span m='68500'>real</span> <span m='69280'>if</span> <span m='69430'>you</span>
  <span m='69550'>have,</span> <span m='69820'>essentially,</span> <span m='70360'>linear</span>
  <span m='70810'>space</span> <span m='71190'>or n</span> <span m='71290'>log</span>
  <span m='71590'>n</span> <span m='71740'>space,</span> <span m='72100'>or</span>
  <span m='72190'>something</span> <span m='72490'>like</span> <span m='72640'>that.</span>
  <span m='73550'>But</span> <span m='73600'>that's</span> <span m='73780'>much</span>
  <span m='73990'>harder</span> <span m='74230'>to</span> <span m='74350'>prove.</span>
  <span m='74830'>So</span> <span m='75010'>this</span> <span m='75220'>is</span>
  <span m='75340'>where</span> <span m='75490'>we</span> <span m='75670'>will</span>
  <span m='75850'>end</span> <span m='76840'>our</span> <span m='77320'>coverage</span>
  <span m='77800'>of</span> <span m='77920'>predecessor.</span> <span m='78490'>But</span>
  <span m='78590'>I'm</span> <span m='78640'>going</span> <span m='78740'>to</span>
  <span m='78810'>start</span> <span m='79030'>out</span> <span m='79150'>with</span>
  <span m='79360'>an</span> <span m='79450'>overview</span> <span m='79840'>of</span>
  <span m='79900'>what's</span> <span m='80110'>known.</span> </p><p><span m='81160'>And</span>
  <span m='81960'>proving</span> <span m='82300'>this</span> <span m='82450'>lower</span>
  <span m='82690'>bound</span> <span m='82900'>is</span> <span m='83050'>actually</span>
  <span m='83770'>pretty</span> <span m='84010'>cool,</span> <span m='84870'>because</span>
  <span m='85060'>at</span> <span m='85150'>this</span> <span m='85300'>point,</span>
  <span m='85760'>especially</span> <span m='86050'>seeing</span> <span m='86260'>fusion</span>
  <span m='86590'>tries,</span> <span m='86890'>you</span> <span m='87010'>might</span>
  <span m='87160'>think</span> <span m='87840'>bit</span> <span m='88030'>tricks</span>
  <span m='88360'>are</span> <span m='88480'>kind</span> <span m='88720'>of</span>
  <span m='88840'>all</span> <span m='89080'>about</span> <span m='91150'>magic,</span>
  <span m='91810'>and</span> <span m='91960'>doing</span> <span m='92320'>crazy</span>
  <span m='92710'>things,</span> <span m='93160'>and</span> <span m='93250'>using</span>
  <span m='93580'>these</span> <span m='93730'>operations</span> <span m='94330'>in</span>
  <span m='94450'>bizarre</span> <span m='94780'>ways</span> <span m='95030'>they</span>
  <span m='95140'>weren't</span> <span m='95320'>intended.</span> <span m='96670'>Bit</span>
  <span m='97015'>tricks</span> <span m='98920'>are</span> <span m='99050'>necessary</span>
  <span m='99970'>as</span> <span m='100210'>an</span> <span m='100300'>upper</span>
  <span m='100510'>bound</span> <span m='100810'>tool,</span> <span m='102070'>given</span>
  <span m='102490'>our</span> <span m='102880'>weird</span> <span m='104050'>historical</span>
  <span m='105010'>precedent,</span> <span m='105520'>which</span> <span m='105700'>is</span>
  <span m='105820'>computers</span> <span m='106240'>are</span> <span m='106330'>built</span>
  <span m='106540'>to</span> <span m='106630'>do</span> <span m='106780'>arithmetic.</span>
  <span m='107860'>And</span> <span m='108550'>why</span> <span m='108760'>not</span>
  <span m='108940'>do</span> <span m='109060'>bit</span> <span m='109240'>operations</span>
  <span m='109750'>too?</span> </p><p><span m='110380'>And</span> <span m='110560'>so</span>
  <span m='112090'>it's</span> <span m='112300'>sort</span> <span m='112450'>of</span>
  <span m='112510'>an</span> <span m='112600'>artifact</span> <span m='113260'>of</span>
  <span m='113500'>computers</span> <span m='113980'>as</span> <span m='114100'>we</span>
  <span m='114190'>know</span> <span m='114340'>them</span> <span m='114460'>today.</span>
  <span m='114760'>That's</span> <span m='115000'>why</span> <span m='115180'>we</span>
  <span m='115270'>have</span> <span m='115420'>the</span> <span m='115540'>word</span>
  <span m='115720'>RAM,</span> <span m='116170'>because</span> <span m='116410'>it's</span>
  <span m='116500'>based</span> <span m='116770'>on</span> <span m='116860'>C,</span>
  <span m='117220'>because</span> <span m='117430'>it's</span> <span m='117520'>based</span>
  <span m='117850'>on</span> <span m='118000'>computers</span> <span m='118480'>that</span>
  <span m='119020'>exist</span> <span m='119350'>now.</span> <span m='121360'>And</span>
  <span m='121670'>that's</span> <span m='122140'>legitimate</span> <span m='122480'>in</span>
  <span m='122820'>that</span> <span m='122950'>that's</span> <span m='123190'>the</span>
  <span m='123280'>computers</span> <span m='123640'>we</span> <span m='123730'>have.</span>
  <span m='124030'>So we</span> <span m='124150'>might</span> <span m='124270'>as</span>
  <span m='124360'>well</span> <span m='124450'>try</span> <span m='124630'>to</span>
  <span m='124720'>use</span> <span m='124960'>them.</span> </p><p><span m='125560'>The</span>
  <span m='125650'>lower</span> <span m='125950'>bounds,</span> <span m='126220'>on</span>
  <span m='126310'>the</span> <span m='126430'>other</span> <span m='126610'>hand,</span>
  <span m='127160'>are,</span> <span m='128590'>in</span> <span m='128710'>some</span>
  <span m='128949'>ways,</span> <span m='129220'>more</span> <span m='129460'>beautiful,</span>
  <span m='130330'>because</span> <span m='130720'>they're</span> <span m='130930'>just</span>
  <span m='131260'>about</span> <span m='131680'>how</span> <span m='131920'>much</span>
  <span m='132100'>information</span> <span m='132670'>has</span> <span m='132880'>to</span>
  <span m='133000'>go</span> <span m='133420'>between</span> <span m='135640'>Alice</span>
  <span m='135970'>and</span> <span m='136090'>Bob,</span> <span m='136470'>actually.</span>
  <span m='137940'>This</span> <span m='138120'>is</span> <span m='138220'>the</span>
  <span m='138340'>communication</span> <span m='138940'>complexity</span> <span m='139420'>perspective</span>
  <span m='139930'>of</span> <span m='139990'>data</span> <span m='140230'>structures.</span>
  <span m='141280'>And</span> <span m='141490'>it's</span> <span m='141850'>nice.</span>
  <span m='142120'>We</span> <span m='142240'>will</span> <span m='142360'>get,</span>
  <span m='143230'>in</span> <span m='143320'>some</span> <span m='143530'>ways,</span>
  <span m='143800'>cleaner,</span> <span m='144410'>simpler</span> <span m='145450'>arguments</span>
  <span m='145930'>because</span> <span m='146590'>in</span> <span m='146920'>lower</span>
  <span m='147250'>bound</span> <span m='147390'>land,</span> <span m='147700'>you</span>
  <span m='147790'>don't</span> <span m='147910'>have</span> <span m='148060'>to</span>
  <span m='148150'>worry</span> <span m='148330'>about,</span> <span m='148730'>oh,</span>
  <span m='148780'>can</span> <span m='148960'>I</span> <span m='148990'>use</span>
  <span m='149140'>this</span> <span m='149350'>operation or</span> <span m='149830'>this</span>
  <span m='150010'>operation</span> <span m='150400'>to</span> <span m='150490'>do?</span>
  </p><p><span m='150610'>It's</span> <span m='150720'>just,</span> <span m='151180'>is</span>
  <span m='151300'>there</span> <span m='151420'>any</span> <span m='151600'>operation</span>
  <span m='152080'>at</span> <span m='152170'>all</span> <span m='152590'>to</span>
  <span m='152740'>do</span> <span m='152920'>it?</span> <span m='153430'>And</span>
  <span m='153580'>then</span> <span m='153700'>it's</span> <span m='153790'>just</span>
  <span m='154000'>about</span> <span m='154180'>information.</span> <span m='154720'>It's</span>
  <span m='154780'>just</span> <span m='154960'>about</span> <span m='155140'>information</span>
  <span m='155650'>theory.</span> <span m='156430'>And</span> <span m='156910'>it's,</span>
  <span m='157390'>in</span> <span m='157600'>some</span> <span m='157810'>ways,</span>
  <span m='157930'>cleaner.</span> </p><p><span m='158470'>And</span> <span m='158590'>this</span>
  <span m='158770'>proof,</span> <span m='159070'>in</span> <span m='159190'>particular</span>
  <span m='160150'>using</span> <span m='160710'>a</span> <span m='160750'>technique</span>
  <span m='161140'>called</span> <span m='161340'>round</span> <span m='161560'>elimination</span>
  <span m='162100'>is</span> <span m='162190'>actually</span> <span m='163300'>simple.</span>
  <span m='164140'>And</span> <span m='164320'>we</span> <span m='164440'>will</span>
  <span m='164590'>see</span> <span m='164920'>in</span> <span m='165100'>it</span>
  <span m='165370'>the</span> <span m='165700'>concepts</span> <span m='166420'>of</span>
  <span m='166540'>Van Emde Boas</span> <span m='167230'>and</span> <span m='167380'>fusion</span>
  <span m='167650'>tries</span> <span m='167980'>again,</span> <span m='169270'>but</span>
  <span m='170170'>without</span> <span m='170590'>having</span> <span m='170830'>to</span>
  <span m='170890'>do</span> <span m='170980'>any</span> <span m='171130'>bit</span>
  <span m='171280'>tricks</span> <span m='171520'>to</span> <span m='171580'>actually</span>
  <span m='171940'>make</span> <span m='172120'>them</span> <span m='172270'>happen.</span>
  <span m='175030'>So</span> <span m='175690'>if</span> <span m='175870'>you</span>
  <span m='175960'>felt</span> <span m='176110'>like</span> <span m='176290'>all</span>
  <span m='176390'>of</span> <span m='176440'>these bit</span> <span m='176670'>tricks</span>
  <span m='176950'>are</span> <span m='177010'>kind</span> <span m='177220'>of</span>
  <span m='177280'>weird,</span> <span m='177880'>what</span> <span m='178030'>is</span>
  <span m='178120'>the</span> <span m='178240'>real</span> <span m='178450'>essence</span>
  <span m='178760'>of</span> <span m='178810'>the</span> <span m='178900'>problem?</span>
  </p><p><span m='179730'>This,</span> <span m='179920'>in</span> <span m='180040'>some</span>
  <span m='180250'>sense,</span> <span m='180580'>provides</span> <span m='181000'>an</span>
  <span m='181090'>answer.</span> <span m='181420'>And</span> <span m='181510'>it</span>
  <span m='181570'>says,</span> <span m='181840'>well,</span> <span m='181990'>really</span>
  <span m='182530'>those</span> <span m='182770'>were</span> <span m='182950'>the</span>
  <span m='183070'>right</span> <span m='183250'>answers.</span> <span m='183700'>That's</span>
  <span m='183850'>what</span> <span m='183970'>you</span> <span m='184060'>should</span>
  <span m='184270'>have</span> <span m='184480'>been</span> <span m='184660'>getting.</span>
  </p><p><span m='186490'>So</span> <span m='186730'>let</span> <span m='186880'>me</span>
  <span m='187030'>start</span> <span m='187420'>with</span> <span m='187840'>the</span>
  <span m='187960'>survey.</span> <span m='190710'>This is</span> <span m='190870'>more</span>
  <span m='191050'>of</span> <span m='191110'>a</span> <span m='191170'>historical</span>
  <span m='191740'>survey.</span> <span m='196900'>So</span> <span m='197140'>the</span>
  <span m='197230'>first</span> <span m='197650'>bound</span> <span m='199090'>for</span>
  <span m='199720'>predecessor</span> <span m='200260'>problem,</span> <span m='200510'>first</span>
  <span m='200730'>lower</span> <span m='201010'>bound,</span> <span m='202270'>Asvab
  Atjai</span> <span m='203230'>in</span> <span m='203530'>1988.</span> <span m='205630'>And</span>
  <span m='205840'>he</span> <span m='205960'>proved</span> <span m='207190'>that</span>
  <span m='208870'>for</span> <span m='209050'>every</span> <span m='209290'>word</span>
  <span m='209530'>size,</span> <span m='210590'>there's</span> <span m='211060'>a</span>
  <span m='211120'>problem</span> <span m='211480'>size</span> <span m='212770'>such</span>
  <span m='213130'>that</span> <span m='213880'>there</span> <span m='214100'>is</span>
  <span m='214270'>an</span> <span m='214420'>omega</span> <span m='215230'>square</span>
  <span m='215720'>root</span> <span m='217560'>log</span> <span m='217840'>w</span>
  <span m='218770'>lower</span> <span m='219060'>bound.</span> </p><p><span m='220420'>You
  can</span> <span m='220900'>compare</span> <span m='221200'>that</span> <span m='221380'>with</span>
  <span m='221530'>this</span> <span m='221740'>one.</span> <span m='221890'>This</span>
  <span m='222070'>is</span> <span m='222160'>log</span> <span m='222430'>w</span>
  <span m='222760'>over</span> <span m='222920'>log</span> <span m='223140'>log</span>
  <span m='223330'>w.</span> <span m='225440'>Now,</span> <span m='225910'>this</span>
  <span m='226180'>is</span> <span m='226270'>a</span> <span m='226330'>bound</span>
  <span m='226690'>that</span> <span m='226840'>works</span> <span m='227050'>for</span>
  <span m='227170'>all</span> <span m='227350'>values</span> <span m='227820'>of</span>
  <span m='227940'>n</span> <span m='228070'>and</span> <span m='228160'>w,</span>
  <span m='228580'>which</span> <span m='228790'>is</span> <span m='228880'>more</span>
  <span m='229060'>interesting.</span> </p><p><span m='230320'>Here,</span> <span
  m='230560'>we're</span> <span m='230680'>saying</span> <span m='231100'>that</span>
  <span m='231220'>if</span> <span m='231340'>you</span> <span m='231460'>just</span>
  <span m='231790'>want</span> <span m='231980'>a</span> <span m='232060'>bound</span>
  <span m='232360'>in</span> <span m='232450'>terms</span> <span m='232720'>of</span>
  <span m='232880'>w,</span> <span m='235010'>you</span> <span m='235210'>need</span>
  <span m='235450'>at</span> <span m='235540'>least</span> <span m='235900'>square</span>
  <span m='236260'>root</span> <span m='236440'>log</span> <span m='236710'>w.</span>
  <span m='239260'>The</span> <span m='239380'>original</span> <span m='239740'>paper</span>
  <span m='240040'>claimed</span> <span m='240370'>log</span> <span m='240710'>w.</span>
  <span m='241020'>But</span> <span m='241150'>that's</span> <span m='241360'>not</span>
  <span m='241570'>true,</span> <span m='242440'>in</span> <span m='242590'>general.</span>
  </p><p><span m='243530'>But</span> <span m='244090'>the</span> <span m='244240'>proof</span>
  <span m='244630'>actually</span> <span m='244930'>establishes</span> <span m='245410'>square</span>
  <span m='245840'>root</span> <span m='246100'>log w.</span> <span m='246250'>And</span>
  <span m='246430'>in</span> <span m='246610'>this</span> <span m='246760'>proof</span>
  <span m='246970'>is</span> <span m='247060'>complicated.</span> <span m='247630'>It
  was</span> <span m='247750'>the</span> <span m='247840'>first</span> <span m='248140'>one.</span>
  <span m='248530'>It got</span> <span m='248710'>the</span> <span m='248770'>field</span>
  <span m='249020'>started.</span> <span m='250010'>There's</span> <span m='250180'>been</span>
  <span m='250330'>many</span> <span m='250540'>papers</span> <span m='250870'>since</span>
  <span m='251110'>then.</span> </p><p><span m='251620'>Next</span> <span m='251860'>one</span>
  <span m='252070'>was</span> <span m='252250'>by</span> <span m='252490'>Miltersen,</span>
  <span m='253190'>who</span> <span m='255010'>we've</span> <span m='255220'>cited</span>
  <span m='255640'>a</span> <span m='255700'>few</span> <span m='255880'>times.</span>
  <span m='261260'>And</span> <span m='261670'>so</span> <span m='261820'>this</span>
  <span m='262060'>a</span> <span m='262120'>few</span> <span m='262330'>years</span>
  <span m='262570'>later.</span> <span m='262900'>Miltersen,</span> <span m='263350'>essentially,</span>
  <span m='263740'>took</span> <span m='263950'>the</span> <span m='264070'>same</span>
  <span m='264370'>proof,</span> <span m='264940'>presented</span> <span m='265450'>it</span>
  <span m='265630'>in</span> <span m='265990'>a</span> <span m='266050'>more</span>
  <span m='267130'>coherent</span> <span m='267730'>way,</span> <span m='267940'>and</span>
  <span m='268030'>sort</span> <span m='268180'>of</span> <span m='268270'>really</span>
  <span m='268510'>got</span> <span m='268720'>to</span> <span m='268840'>the</span>
  <span m='268960'>essence</span> <span m='269290'>of</span> <span m='269380'>what</span>
  <span m='269500'>the</span> <span m='269620'>proof</span> <span m='269830'>was</span>
  <span m='269920'>showing,</span> <span m='270850'>and</span> <span m='271680'>could</span>
  <span m='271900'>prove</span> <span m='273520'>the</span> <span m='273670'>same</span>
  <span m='273970'>bound,</span> <span m='277210'>but</span> <span m='277360'>also</span>
  <span m='279250'>a</span> <span m='279370'>complementary</span> <span m='280060'>bound,</span>
  <span m='281100'>because</span> <span m='281290'>there</span> <span m='281380'>is</span>
  <span m='281500'>a</span> <span m='281590'>symmetry</span> <span m='282070'>between</span>
  <span m='282400'>word</span> <span m='282610'>size</span> <span m='283090'>and</span>
  <span m='283930'>problem</span> <span m='284260'>size,</span> <span m='284560'>which</span>
  <span m='284740'>we</span> <span m='284860'>will</span> <span m='284980'>see</span>
  <span m='286990'>when</span> <span m='287140'>we</span> <span m='287230'>get</span>
  <span m='287410'>to</span> <span m='287500'>the</span> <span m='287620'>communication</span>
  <span m='288190'>complexity</span> <span m='288730'>perspective,</span> <span m='289370'>which</span>
  <span m='289430'>will</span> <span m='289520'>be</span> <span m='289660'>right</span>
  <span m='289840'>after</span> <span m='290140'>the</span> <span m='290240'>survey.</span>
  </p><p><span m='292840'>It's</span> <span m='292960'>not</span> <span m='293200'>completely</span>
  <span m='293650'>symmetric.</span> <span m='298120'>But</span> <span m='298780'>Miltersen</span>
  <span m='299270'>proved</span> <span m='299530'>this</span> <span m='299710'>lower</span>
  <span m='299950'>bound</span> <span m='300280'>that for</span> <span m='300400'>every</span>
  <span m='300670'>problem</span> <span m='301000'>size,</span> <span m='301750'>there</span>
  <span m='301930'>is</span> <span m='302110'>a</span> <span m='302170'>machine,</span>
  <span m='302560'>there</span> <span m='302680'>is</span> <span m='302770'>a</span>
  <span m='302860'>word</span> <span m='303100'>size,</span> <span m='303790'>where</span>
  <span m='303910'>you</span> <span m='304060'>need</span> <span m='304390'>omega</span>
  <span m='305170'>cube</span> <span m='305470'>root</span> <span m='305710'>of</span>
  <span m='305890'>log</span> <span m='306160'>n.</span> <span m='306430'>Now,</span>
  <span m='306550'>we</span> <span m='306700'>know</span> <span m='306850'>how</span>
  <span m='307000'>to</span> <span m='307090'>get</span> <span m='307960'>order</span>
  <span m='308260'>square</span> <span m='308560'>root</span> <span m='308680'>of</span>
  <span m='308770'>log</span> <span m='309110'>n</span> <span m='309160'>by</span>
  <span m='309280'>taking</span> <span m='309640'>them</span> <span m='309760'>in.</span>
  <span m='311470'>So</span> <span m='311680'>this</span> <span m='311890'>is</span>
  <span m='312660'>matching</span> <span m='313630'>up</span> <span m='313750'>to</span>
  <span m='313900'>the</span> <span m='314020'>exponent.</span> </p><p><span m='316070'>And</span>
  <span m='316120'>we</span> <span m='316210'>know</span> <span m='316360'>how</span>
  <span m='316420'>to</span> <span m='316540'>do</span> <span m='316690'>log</span>
  <span m='317100'>w</span> <span m='317510'>by</span> <span m='317760'>Van Emde Boas.</span>
  <span m='318490'>So</span> <span m='318730'>this</span> <span m='318910'>is</span>
  <span m='319330'>matching</span> <span m='319720'>up</span> <span m='319840'>to</span>
  <span m='319930'>the</span> <span m='320020'>exponent.</span> <span m='320540'>So</span>
  <span m='320740'>it's</span> <span m='320940'>progress.</span> <span m='322230'>But
  it</span> <span m='322440'>doesn't</span> <span m='322680'>give</span> <span m='322860'>a</span>
  <span m='322920'>complete</span> <span m='323250'>picture</span> <span m='323580'>of</span>
  <span m='323700'>w</span> <span m='324000'>versus</span> <span m='324360'>n.</span>
  <span m='327390'>And</span> <span m='327540'>this</span> <span m='327810'>is</span>
  <span m='327930'>the</span> <span m='328020'>paper</span> <span m='328320'>that</span>
  <span m='328410'>introduced</span> <span m='328950'>this</span> <span m='329160'>communication</span>
  <span m='329790'>complexity</span> <span m='330420'>idea,</span> <span m='330840'>that</span>
  <span m='331020'>this</span> <span m='331200'>would</span> <span m='331290'>be</span>
  <span m='331410'>a</span> <span m='331470'>useful</span> <span m='332010'>concept</span>
  <span m='332490'>for</span> <span m='333760'>predecessor</span> <span m='334350'>lower</span>
  <span m='334550'>bounds.</span> </p><p><span m='340690'>Then</span> <span m='342810'>the</span>
  <span m='342900'>following</span> <span m='343380'>year,</span> <span m='348550'>there's</span>
  <span m='348760'>a</span> <span m='348790'>bit</span> <span m='348940'>of</span>
  <span m='349030'>a</span> <span m='349090'>breakthrough.</span> <span m='356310'>So</span>
  <span m='356980'>here,</span> <span m='357300'>we've</span> <span m='357370'>got</span>
  <span m='357670'>the</span> <span m='357820'>idea</span> <span m='358180'>of</span>
  <span m='358360'>using</span> <span m='358600'>communication</span> <span m='359140'>complexity.</span>
  <span m='360610'>Then</span> <span m='361150'>Miltersen</span> <span m='361660'>and</span>
  <span m='361780'>others</span> <span m='362890'>had</span> <span m='363160'>the</span>
  <span m='363280'>idea</span> <span m='363610'>of</span> <span m='363820'>round</span>
  <span m='364090'>elimination.</span> </p><p><span m='373480'>And</span> <span m='373790'>so</span>
  <span m='373940'>just</span> <span m='374210'>treat</span> <span m='374450'>that</span>
  <span m='374570'>as</span> <span m='374660'>a</span> <span m='374720'>black</span>
  <span m='374960'>box</span> <span m='375340'>for</span> <span m='375470'>now.</span>
  <span m='375720'>We'll</span> <span m='376130'>explain</span> <span m='376490'>what</span>
  <span m='376640'>is</span> <span m='376820'>in</span> <span m='376910'>a</span>
  <span m='376940'>moment.</span> <span m='378330'>But</span> <span m='378480'>it</span>
  <span m='378590'>proved</span> <span m='378890'>exactly</span> <span m='379340'>the</span>
  <span m='379460'>same</span> <span m='379670'>result,</span> <span m='380250'>but</span>
  <span m='380750'>in</span> <span m='380900'>a</span> <span m='380930'>clean</span>
  <span m='381290'>way,</span> <span m='381620'>using</span> <span m='381890'>round</span>
  <span m='382070'>elimination.</span> </p><p><span m='382550'>These</span> <span
  m='382730'>proofs</span> <span m='383000'>were</span> <span m='383060'>messy.</span>
  <span m='383810'>This</span> <span m='383990'>proof</span> <span m='384290'>is</span>
  <span m='384620'>pretty</span> <span m='385190'>simple.</span> <span m='386510'>And</span>
  <span m='386780'>it's</span> <span m='388430'>the</span> <span m='388520'>beginning</span>
  <span m='388970'>of</span> <span m='389900'>the</span> <span m='389990'>proof</span>
  <span m='390290'>that</span> <span m='390500'>we</span> <span m='390740'>will</span>
  <span m='391100'>cover.</span> <span m='392420'>But</span> <span m='392570'>we're</span>
  <span m='392640'>going</span> <span m='392730'>to</span> <span m='392840'>prove</span>
  <span m='393020'>stronger</span> <span m='393320'>bounds</span> <span m='393590'>than</span>
  <span m='393740'>this.</span> </p><p><span m='396140'>Let</span> <span m='396260'>me</span>
  <span m='396440'>go</span> <span m='396650'>to</span> <span m='396980'>another</span>
  <span m='397280'>board.</span> <span m='398010'>Next,</span> <span m='398300'>we</span>
  <span m='398450'>have</span> <span m='399560'>Beame and Fich.</span> <span m='402230'>Now</span>
  <span m='402560'>is</span> <span m='402650'>about</span> <span m='402890'>the</span>
  <span m='402980'>time</span> <span m='403220'>when</span> <span m='403340'>I</span>
  <span m='403460'>entered</span> <span m='403730'>the</span> <span m='403850'>world</span>
  <span m='404060'>of</span> <span m='404120'>data</span> <span m='404330'>structures.</span>
  <span m='404720'>And</span> <span m='405110'>so</span> <span m='406310'>Beame and
  Fich</span> <span m='408530'>came</span> <span m='408740'>out</span> <span m='408920'>just</span>
  <span m='409190'>when</span> <span m='409340'>I</span> <span m='409430'>was</span>
  <span m='409520'>starting,</span> <span m='410750'>1999.</span> </p><p><span m='413810'>And</span>
  <span m='414170'>this</span> <span m='414470'>proved</span> <span m='417900'>for
  all of</span> <span m='418320'>w</span> <span m='418910'>exists</span> <span m='419360'>an</span>
  <span m='419710'>n.</span> <span m='428510'>So</span> <span m='428690'>log</span>
  <span m='428990'>w</span> <span m='429300'>over</span> <span m='429490'>log</span>
  <span m='429830'>log w,</span> <span m='430190'>which</span> <span m='430370'>is</span>
  <span m='430520'>the</span> <span m='430640'>same</span> <span m='430850'>thing</span>
  <span m='431100'>we're</span> <span m='431210'>going</span> <span m='431330'>to</span>
  <span m='431420'>prove.</span> <span m='432920'>Except</span> <span m='433700'>this</span>
  <span m='433880'>only</span> <span m='434120'>proves</span> <span m='434450'>it</span>
  <span m='435290'>for</span> <span m='435530'>certain</span> <span m='435830'>values</span>
  <span m='436220'>of</span> <span m='436370'>n,</span> <span m='438320'>whereas</span>
  <span m='438560'>we're</span> <span m='438710'>going</span> <span m='438780'>to</span>
  <span m='438890'>prove</span> <span m='439100'>it</span> <span m='439190'>for</span>
  <span m='439340'>all</span> <span m='439490'>values</span> <span m='439850'>of</span>
  <span m='439970'>n</span> <span m='440180'>where</span> <span m='440510'>this</span>
  <span m='440750'>is</span> <span m='441410'>smaller</span> <span m='442040'>than</span>
  <span m='442250'>that.</span> <span m='443690'>So</span> <span m='445040'>this</span>
  <span m='445190'>is</span> <span m='445340'>a</span> <span m='445400'>bit</span>
  <span m='445550'>more</span> <span m='445730'>special,</span> <span m='446970'>not</span>
  <span m='447140'>covering</span> <span m='447470'>the</span> <span m='447560'>whole</span>
  <span m='447860'>w</span> <span m='448280'>n</span> <span m='448920'>trade-off.</span>
  </p><p><span m='451010'>And</span> <span m='451130'>then</span> <span m='451310'>there's</span>
  <span m='451550'>this</span> <span m='452360'>symmetric</span> <span m='452960'>version.</span>
  <span m='460720'>There's</span> <span m='461120'>going</span> <span m='461280'>to</span>
  <span m='461360'>be</span> <span m='461450'>a</span> <span m='461510'>lot</span>
  <span m='461660'>of</span> <span m='461750'>log</span> <span m='461930'>log</span>
  <span m='462130'>n's</span> <span m='462410'>today.</span> <span m='463720'>So</span>
  <span m='463860'>get</span> <span m='464030'>ready</span> <span m='466790'>for</span>
  <span m='466910'>log</span> <span m='467150'>logs</span> <span m='467480'>in</span>
  <span m='467600'>general.</span> </p><p><span m='468090'>So</span> <span m='468200'>for</span>
  <span m='468350'>every</span> <span m='468590'>n,</span> <span m='469100'>there</span>
  <span m='469190'>exists</span> <span m='469490'>a</span> <span m='469520'>w</span>
  <span m='473270'>such</span> <span m='473570'>that</span> <span m='473640'>there's</span>
  <span m='473840'>an</span> <span m='473930'>omega</span> <span m='474440'>root</span>
  <span m='474860'>log</span> <span m='475190'>n</span> <span m='475310'>over</span>
  <span m='475520'>log</span> <span m='475800'>log n. So</span> <span m='476120'>this
  is</span> <span m='476450'>almost</span> <span m='476810'>matching</span> <span
  m='477350'>the</span> <span m='477800'>min</span> <span m='478220'>of</span> <span
  m='478430'>fusion</span> <span m='478790'>tries</span> <span m='479150'>and</span>
  <span m='479330'>Van Emde Boas,</span> <span m='479960'>which</span> <span m='480170'>is</span>
  <span m='480740'>order</span> <span m='480980'>square</span> <span m='481430'>root</span>
  <span m='481715'>log</span> <span m='482000'>n.</span> <span m='483680'>They</span>
  <span m='483950'>also</span> <span m='484880'>proved--</span> <span m='485960'>did</span>
  <span m='486170'>a</span> <span m='486200'>little</span> <span m='486380'>bit</span>
  <span m='486500'>on</span> <span m='486590'>the</span> <span m='486710'>upper</span>
  <span m='486950'>bound</span> <span m='487160'>side.</span> <span m='488130'>And
  they</span> <span m='488300'>found</span> <span m='488660'>a</span> <span m='488780'>static</span>
  <span m='490010'>data</span> <span m='490250'>structure</span> <span m='492030'>achieving--</span>
  <span m='505200'>I'm</span> <span m='505260'>just</span> <span m='505410'>going</span>
  <span m='505530'>to</span> <span m='506160'>cheat</span> <span m='506460'>and</span>
  <span m='506560'>use some</span> <span m='506830'>arrows.</span> </p><p><span m='508260'>So</span>
  <span m='508440'>they</span> <span m='508650'>achieved</span> <span m='508950'>the</span>
  <span m='509070'>min</span> <span m='509280'>of</span> <span m='509370'>these</span>
  <span m='509580'>two.</span> <span m='511500'>So</span> <span m='511830'>in</span>
  <span m='511950'>a</span> <span m='512010'>certain</span> <span m='512520'>sense,</span>
  <span m='512850'>this</span> <span m='513059'>is</span> <span m='513179'>tight.</span>
  <span m='513510'>This</span> <span m='513720'>is</span> <span m='513840'>not</span>
  <span m='514049'>exactly</span> <span m='514919'>what</span> <span m='515100'>you'd</span>
  <span m='515280'>want,</span> <span m='515909'>because</span> <span m='516270'>the</span>
  <span m='516480'>data</span> <span m='516780'>structures</span> <span m='517140'>achieving</span>
  <span m='517500'>the</span> <span m='517590'>min,</span> <span m='518419'>what</span>
  <span m='518520'>you'd</span> <span m='518669'>like</span> <span m='518880'>is</span>
  <span m='519000'>a</span> <span m='519030'>lower</span> <span m='519330'>bound</span>
  <span m='519570'>of</span> <span m='519720'>the</span> <span m='519840'>min.</span>
  </p><p><span m='520950'>And</span> <span m='521070'>it's</span> <span m='521159'>not</span>
  <span m='521370'>quite</span> <span m='521700'>that.</span> <span m='521909'>It's</span>
  <span m='522010'>saying,</span> <span m='522370'>there's</span> <span m='523409'>a</span>
  <span m='523470'>particular</span> <span m='524070'>pair</span> <span m='524565'>of</span>
  <span m='525060'>w</span> <span m='525420'>and</span> <span m='525510'>n</span>
  <span m='525660'>values</span> <span m='526560'>where</span> <span m='526680'>this</span>
  <span m='526830'>is</span> <span m='526950'>optimal.</span> <span m='527310'>There's</span>
  <span m='527490'>another</span> <span m='527910'>pair</span> <span m='528210'>of</span>
  <span m='528380'>n</span> <span m='528740'>and w</span> <span m='528950'>values</span>
  <span m='529330'>where</span> <span m='529450'>this is</span> <span m='529540'>optimal</span>
  <span m='529820'>with</span> <span m='530100'>respect</span> <span m='530460'>to</span>
  <span m='530580'>either</span> <span m='530850'>one</span> <span m='531060'>of</span>
  <span m='531120'>these</span> <span m='531270'>parameters.</span> <span m='533080'>But</span>
  <span m='533160'>there</span> <span m='533340'>are</span> <span m='533370'>other</span>
  <span m='533970'>pairs</span> <span m='534330'>of</span> <span m='534390'>values</span>
  <span m='534720'>of</span> <span m='534810'>w</span> <span m='535140'>and</span>
  <span m='535230'>n</span> <span m='535380'>where</span> <span m='535710'>it</span>
  <span m='536190'>may</span> <span m='536370'>or</span> <span m='536430'>may</span>
  <span m='536580'>not</span> <span m='536760'>be</span> <span m='536910'>optimal.</span>
  <span m='537540'>So</span> <span m='538410'>it's</span> <span m='538530'>kind</span>
  <span m='538920'>of</span> <span m='539010'>matching,</span> <span m='539460'>but</span>
  <span m='539580'>not</span> <span m='539730'>quite.</span> </p><p><span m='541560'>The</span>
  <span m='541710'>way</span> <span m='542330'>to</span> <span m='542520'>say</span>
  <span m='542760'>it</span> <span m='542880'>is</span> <span m='543120'>these</span>
  <span m='543900'>are</span> <span m='543990'>the</span> <span m='544080'>best--</span>
  <span m='544960'>this</span> <span m='544980'>is</span> <span m='545040'>the</span>
  <span m='545160'>best</span> <span m='545460'>pure</span> <span m='545940'>w</span>
  <span m='546330'>bound</span> <span m='547200'>you</span> <span m='547320'>could</span>
  <span m='547470'>hope</span> <span m='547590'>for.</span> <span m='547760'>And</span>
  <span m='547830'>this</span> <span m='547980'>is</span> <span m='548070'>the</span>
  <span m='548190'>best</span> <span m='548430'>pure</span> <span m='548790'>n</span>
  <span m='549030'>bound</span> <span m='549440'>that</span> <span m='549600'>you</span>
  <span m='549690'>could</span> <span m='549840'>hope</span> <span m='549960'>for.</span>
  <span m='551150'>And</span> <span m='551630'>it's</span> <span m='551820'>the</span>
  <span m='551940'>best</span> <span m='552150'>mix</span> <span m='552420'>of</span>
  <span m='552740'>two</span> <span m='552930'>pure</span> <span m='553230'>bounds.</span>
  </p><p><span m='555620'>OK,</span> <span m='557070'>then</span> <span m='557250'>we</span>
  <span m='557400'>go</span> <span m='557610'>back</span> <span m='557970'>in</span>
  <span m='558060'>time</span> <span m='558330'>a</span> <span m='558360'>little</span>
  <span m='558570'>bit,</span> <span m='559960'>which</span> <span m='560350'>is--</span>
  <span m='561720'>there's</span> <span m='562380'>a</span> <span m='562440'>funny</span>
  <span m='563550'>chain</span> <span m='563880'>here,</span> <span m='564150'>which</span>
  <span m='564390'>is</span> <span m='565710'>this</span> <span m='565980'>paper,</span>
  <span m='566760'>1995,</span> <span m='568150'>cites</span> <span m='568980'>this</span>
  <span m='569160'>paper</span> <span m='569700'>from</span> <span m='569970'>1999.</span>
  <span m='571620'>This</span> <span m='571860'>paper</span> <span m='572340'>cites</span>
  <span m='572970'>this</span> <span m='573240'>paper</span> <span m='573600'>of</span>
  <span m='573720'>1992.</span> <span m='575940'>That's</span> <span m='576510'>normal.</span>
  </p><p><span m='577880'>This</span> <span m='578190'>one's</span> <span m='578400'>a</span>
  <span m='578460'>little</span> <span m='578700'>bit</span> <span m='578880'>out</span>
  <span m='579060'>of</span> <span m='579120'>order,</span> <span m='579780'>bit</span>
  <span m='579950'>of</span> <span m='580080'>time</span> <span m='580320'>travel.</span>
  <span m='580750'>So</span> <span m='580850'>I</span> <span m='580950'>think</span>
  <span m='580980'>this</span> <span m='581160'>one</span> <span m='581310'>was</span>
  <span m='581520'>in</span> <span m='581640'>draft</span> <span m='581970'>for</span>
  <span m='582120'>a</span> <span m='582150'>long</span> <span m='582390'>time,</span>
  <span m='583110'>and</span> <span m='583260'>took</span> <span m='583500'>awhile</span>
  <span m='583830'>to</span> <span m='584490'>finish</span> <span m='584850'>it.</span>
  <span m='586200'>But</span> <span m='586410'>this</span> <span m='587130'>paper</span>
  <span m='587415'>is</span> <span m='587700'>before</span> <span m='588180'>1995.</span>
  <span m='588850'>It's</span> <span m='588960'>not</span> <span m='589140'>cited</span>
  <span m='589500'>by</span> <span m='589620'>this</span> <span m='589800'>paper.</span>
  </p><p><span m='591120'>What's</span> <span m='591570'>interesting</span> <span
  m='592020'>about</span> <span m='592320'>it</span> <span m='592710'>is</span> <span
  m='592920'>it</span> <span m='593010'>proves</span> <span m='594300'>both</span>
  <span m='594630'>of</span> <span m='594720'>these</span> <span m='594870'>lower</span>
  <span m='595110'>bounds.</span> <span m='598980'>I</span> <span m='599190'>don't</span>
  <span m='599430'>think</span> <span m='599760'>it</span> <span m='599850'>proves</span>
  <span m='600240'>the</span> <span m='600600'>upper</span> <span m='600840'>bounds.</span>
  <span m='604350'>But</span> <span m='604890'>these</span> <span m='605190'>were</span>
  <span m='605370'>independently</span> <span m='606000'>discovered</span> <span m='606420'>by</span>
  <span m='606570'>Beame and Fich</span> <span m='607650'>in</span> <span m='607770'>the</span>
  <span m='607860'>future</span> <span m='608310'>of</span> <span m='608430'>this</span>
  <span m='608580'>paper.</span> <span m='609810'>This</span> <span m='609930'>is</span>
  <span m='610020'>actually</span> <span m='610260'>a</span> <span m='610320'>PhD</span>
  <span m='610680'>thesis.</span> </p><p><span m='611160'>So I</span> <span m='611250'>think</span>
  <span m='611430'>it</span> <span m='611490'>was</span> <span m='611610'>lost,</span>
  <span m='612150'>or</span> <span m='612270'>not</span> <span m='612480'>known</span>
  <span m='612720'>about,</span> <span m='612990'>for</span> <span m='613140'>a</span>
  <span m='613170'>long</span> <span m='613380'>time.</span> <span m='614310'>But</span>
  <span m='614430'>it</span> <span m='614490'>ends</span> <span m='614700'>up</span>
  <span m='614820'>establishing</span> <span m='615360'>the</span> <span m='615450'>same</span>
  <span m='615690'>bounds.</span> <span m='617130'>And</span> <span m='617280'>then</span>
  <span m='617670'>the</span> <span m='617790'>real</span> <span m='618000'>contribution</span>
  <span m='618540'>here</span> <span m='618720'>was</span> <span m='618870'>that</span>
  <span m='619350'>those</span> <span m='619590'>were</span> <span m='619800'>the</span>
  <span m='619950'>best</span> <span m='620370'>bounds</span> <span m='620850'>that</span>
  <span m='620970'>are</span> <span m='621060'>purely</span> <span m='621450'>w</span>
  <span m='621810'>and</span> <span m='621980'>n,</span> <span m='622770'>but</span>
  <span m='622950'>still</span> <span m='623130'>not</span> <span m='623400'>a</span>
  <span m='623460'>full</span> <span m='623730'>story.</span> </p><p><span m='628320'>Next</span>
  <span m='628710'>up</span> <span m='629010'>is</span> <span m='630890'>Sen</span>
  <span m='632610'>in</span> <span m='633090'>2003,</span> <span m='638250'>which</span>
  <span m='639330'>gave</span> <span m='639540'>a round</span> <span m='639900'>elimination</span>
  <span m='640440'>proof</span> <span m='640710'>of</span> <span m='640830'>the</span>
  <span m='640950'>same</span> <span m='641220'>result.</span> <span m='648780'>And</span>
  <span m='649030'>whereas</span> <span m='649390'>both</span> <span m='649720'>the</span>
  <span m='649840'>Beame and Fich</span> <span m='650500'>and</span> <span m='650890'>the</span>
  <span m='651170'>Xiau</span> <span m='651400'>proof</span> <span m='651940'>are</span>
  <span m='652240'>messy,</span> <span m='653560'>this</span> <span m='653740'>round</span>
  <span m='653920'>elimination</span> <span m='654400'>proof</span> <span m='654610'>is</span>
  <span m='654700'>very</span> <span m='655150'>slick</span> <span m='655510'>and</span>
  <span m='655630'>clean.</span> <span m='656470'>And</span> <span m='656590'>this</span>
  <span m='656830'>is</span> <span m='656920'>the</span> <span m='657010'>proof</span>
  <span m='657280'>we're</span> <span m='657370'>going</span> <span m='657490'>to</span>
  <span m='657550'>cover</span> <span m='657850'>today.</span> </p><p><span m='659860'>And</span>
  <span m='660040'>it's</span> <span m='660130'>going</span> <span m='660270'>to</span>
  <span m='660340'>prove--</span> <span m='661450'>it</span> <span m='661600'>will</span>
  <span m='661750'>imply</span> <span m='662320'>these</span> <span m='662560'>pure</span>
  <span m='662980'>w</span> <span m='663340'>and</span> <span m='663460'>n</span>
  <span m='663940'>lower</span> <span m='664250'>bounds.</span> <span m='665800'>But</span>
  <span m='666280'>it</span> <span m='666460'>will,</span> <span m='666730'>in</span>
  <span m='666820'>some</span> <span m='667300'>sense,</span> <span m='667570'>in</span>
  <span m='668170'>a</span> <span m='668410'>stronger</span> <span m='668860'>way,</span>
  <span m='669070'>prove</span> <span m='669400'>this</span> <span m='669640'>bound,</span>
  <span m='670450'>which</span> <span m='670500'>is</span> <span m='670630'>a</span>
  <span m='670690'>real</span> <span m='670900'>min</span> <span m='671230'>thing.</span>
  <span m='672160'>And</span> <span m='672250'>so</span> <span m='672460'>we're</span>
  <span m='672580'>just</span> <span m='672880'>off</span> <span m='673180'>by</span>
  <span m='673360'>this</span> <span m='673510'>log</span> <span m='673780'>log</span>
  <span m='673990'>factor.</span> </p><p><span m='675130'>Otherwise,</span> <span
  m='675670'>we</span> <span m='675760'>were</span> <span m='675820'>proving</span>
  <span m='676630'>exactly</span> <span m='677140'>the</span> <span m='678370'>min</span>
  <span m='678580'>of</span> <span m='678640'>fusion</span> <span m='678940'>tries</span>
  <span m='679120'>in</span> <span m='679230'>Van Emde Boas</span> <span m='679780'>is</span>
  <span m='679930'>optimal.</span> <span m='681280'>Getting</span> <span m='681490'>rid</span>
  <span m='681610'>of</span> <span m='681670'>the</span> <span m='681700'>log</span>
  <span m='681930'>log</span> <span m='682090'>factor</span> <span m='682435'>is</span>
  <span m='682780'>messier.</span> <span m='684190'>That's</span> <span m='684430'>the</span>
  <span m='684520'>next</span> <span m='684760'>paper,</span> <span m='685450'>which</span>
  <span m='685660'>is</span> <span m='686530'>the</span> <span m='686620'>last--</span>
  <span m='687140'>it's</span> <span m='687250'>two</span> <span m='687440'>papers,</span>
  <span m='687790'>actually.</span> </p><p><span m='689582'>But</span> <span m='690040'>the</span>
  <span m='690160'>final</span> <span m='690820'>papers</span> <span m='691320'>in</span>
  <span m='691420'>this</span> <span m='691530'>story</span> <span m='692850'>are</span>
  <span m='693220'>by</span> <span m='693880'>Patrascu</span> <span m='694450'>and</span>
  <span m='695110'>Thorup,</span> <span m='698560'>2006</span> <span m='698990'>and</span>
  <span m='699400'>2007</span> <span m='699785'>are</span> <span m='700260'>the</span>
  <span m='700440'>two</span> <span m='700610'>papers.</span> <span m='701620'>And</span>
  <span m='701800'>they</span> <span m='701980'>give</span> <span m='702310'>a</span>
  <span m='702370'>tight</span> <span m='705628'>n,</span> <span m='706100'>versus</span>
  <span m='706780'>w,</span> <span m='707350'>versus</span> <span m='708460'>space</span>
  <span m='710500'>trade-off.</span> <span m='717040'>I</span> <span m='717070'>think</span>
  <span m='717580'>I</span> <span m='717670'>can</span> <span m='717880'>fit</span>
  <span m='718150'>it</span> <span m='718270'>on</span> <span m='718480'>this</span>
  <span m='718720'>board.</span> <span m='719320'>Let's</span> <span m='719500'>try.</span>
  </p><p><span m='722990'>So</span> <span m='723330'>it's the</span> <span m='723430'>min</span>
  <span m='723910'>of</span> <span m='724390'>four</span> <span m='725350'>terms.</span>
  <span m='726770'>The</span> <span m='726790'>first</span> <span m='727030'>term</span>
  <span m='727960'>is</span> <span m='728080'>nice,</span> <span m='728530'>log</span>
  <span m='728820'>base</span> <span m='729080'>w</span> <span m='729570'>of n.</span>
  <span m='730470'>That's</span> <span m='730660'>our</span> <span m='730750'>good</span>
  <span m='730930'>friend</span> <span m='731200'>fusion</span> <span m='731530'>tries.</span>
  <span m='734260'>The</span> <span m='734310'>next</span> <span m='734590'>one</span>
  <span m='734860'>is</span> <span m='738940'>roughly</span> <span m='739300'>log</span>
  <span m='739510'>w.</span> <span m='744660'>So</span> <span m='744840'>it's</span>
  <span m='744960'>roughly</span> <span m='745960'>Van Emde Boas.</span> <span m='746690'>But</span>
  <span m='746850'>it</span> <span m='746910'>turns</span> <span m='747150'>out</span>
  <span m='747240'>you</span> <span m='747390'>can</span> <span m='747510'>do</span>
  <span m='747630'>a</span> <span m='747660'>little</span> <span m='747870'>better.</span>
  <span m='748190'>Now,</span> <span m='748350'>I</span> <span m='748420'>need</span>
  <span m='748590'>to</span> <span m='748680'>define</span> <span m='749040'>a.</span>
  </p><p><span m='751140'>I'm</span> <span m='751290'>going</span> <span m='751470'>to</span>
  <span m='751590'>assume</span> <span m='751950'>here</span> <span m='752130'>the</span>
  <span m='752300'>space</span> <span m='753210'>is</span> <span m='753540'>n,</span>
  <span m='754260'>times</span> <span m='754770'>2</span> <span m='755150'>to</span>
  <span m='755370'>the</span> <span m='755510'>a.</span> <span m='758010'>That's</span>
  <span m='758400'>the</span> <span m='758520'>notation</span> <span m='758940'>they</span>
  <span m='759090'>use.</span> <span m='759390'>It's</span> <span m='759510'>a</span>
  <span m='759570'>little</span> <span m='759810'>bit</span> <span m='760740'>weird.</span>
  <span m='761130'>But</span> <span m='761280'>it</span> <span m='761370'>makes</span>
  <span m='762000'>this</span> <span m='762180'>bound</span> <span m='762480'>a</span>
  <span m='762540'>little</span> <span m='762750'>bit</span> <span m='762870'>easier</span>
  <span m='763170'>to</span> <span m='763260'>state.</span> </p><p><span m='764010'>So,</span>
  <span m='764340'>of</span> <span m='764460'>course,</span> <span m='764670'>you</span>
  <span m='764760'>need</span> <span m='764970'>linear</span> <span m='765300'>space</span>
  <span m='765660'>to</span> <span m='765780'>store</span> <span m='765990'>the</span>
  <span m='766080'>data.</span> <span m='766590'>This</span> <span m='766770'>is</span>
  <span m='766920'>measuring</span> <span m='767280'>words.</span> <span m='768720'>So</span>
  <span m='768810'>the</span> <span m='768900'>question</span> <span m='769140'>is,</span>
  <span m='769300'>how</span> <span m='769350'>much</span> <span m='769560'>more</span>
  <span m='769740'>than</span> <span m='769860'>linear</span> <span m='770160'>space</span>
  <span m='771030'>do</span> <span m='771120'>you</span> <span m='771270'>have?</span>
  </p><p><span m='772740'>If</span> <span m='772950'>you</span> <span m='773070'>want</span>
  <span m='773610'>poly log</span> <span m='774180'>update,</span> <span m='774680'>then</span>
  <span m='775030'>this</span> <span m='775230'>better</span> <span m='775500'>be</span>
  <span m='775650'>poly</span> <span m='775960'>log</span> <span m='776270'>n.</span>
  <span m='778800'>This</span> <span m='779040'>is</span> <span m='779160'>about</span>
  <span m='779490'>static</span> <span m='779970'>data</span> <span m='780180'>structures.</span>
  <span m='782380'>So</span> <span m='782550'>if</span> <span m='782700'>you</span>
  <span m='782780'>want</span> <span m='782920'>poly log</span> <span m='783195'>n,</span>
  <span m='783630'>then</span> <span m='783800'>a</span> <span m='784170'>to</span>
  <span m='784260'>be</span> <span m='784380'>order</span> <span m='784650'>log</span>
  <span m='784920'>log</span> <span m='785130'>n.</span> <span m='786420'>So</span>
  <span m='786540'>you</span> <span m='786600'>can</span> <span m='786750'>think</span>
  <span m='786900'>of</span> <span m='787020'>a</span> <span m='787170'>being</span>
  <span m='787410'>order</span> <span m='787660'>log</span> <span m='787950'>log n.</span>
  <span m='788650'>Or</span> <span m='788750'>you</span> <span m='788850'>can</span>
  <span m='788950'>think</span> <span m='789050'>of</span> <span m='789150'>a</span>
  <span m='789250'>being</span> <span m='789390'>constant,</span> <span m='789840'>if</span>
  <span m='789960'>you</span> <span m='790020'>want</span> <span m='790200'>linear</span>
  <span m='790500'>space.</span> <span m='791520'>Then</span> <span m='791790'>this</span>
  <span m='791930'>stuff--</span> <span m='792660'>I</span> <span m='792720'>mean,</span>
  <span m='793240'>then</span> <span m='793420'>this</span> <span m='793540'>is</span>
  <span m='793620'>basically</span> <span m='794010'>log</span> <span m='794230'>w.</span>
  <span m='795950'>OK,</span> <span m='798080'>so</span> <span m='798510'>that's</span>
  <span m='798720'>roughly</span> <span m='799080'>Van Emde Boas.</span> </p><p><span
  m='800550'>Next,</span> <span m='800880'>we</span> <span m='801030'>get</span> <span
  m='801540'>two</span> <span m='801960'>crazier</span> <span m='802560'>terms.</span>
  <span m='850030'>These</span> <span m='850210'>ones,</span> <span m='851010'>I</span>
  <span m='851100'>can't</span> <span m='851370'>give</span> <span m='851550'>you</span>
  <span m='851670'>intuition</span> <span m='852090'>for,</span> <span m='852390'>I'm</span>
  <span m='852510'>afraid.</span> <span m='854220'>You</span> <span m='854370'>see,</span>
  <span m='854640'>there's</span> <span m='854860'>the</span> <span m='854940'>log</span>
  <span m='855470'>w.</span> </p><p><span m='855890'>They're,</span> <span m='856440'>again,</span>
  <span m='857190'>versions</span> <span m='858060'>of</span> <span m='858270'>Van
  Emde Boas</span> <span m='859050'>like</span> <span m='859350'>things.</span> <span
  m='860340'>But</span> <span m='860520'>they're</span> <span m='860640'>improving</span>
  <span m='861210'>by</span> <span m='861390'>some</span> <span m='861630'>factors</span>
  <span m='862770'>that</span> <span m='863340'>make</span> <span m='863910'>you</span>
  <span m='864030'>better</span> <span m='864480'>when</span> <span m='864780'>a</span>
  <span m='864990'>is</span> <span m='865110'>large.</span> <span m='866220'>And,</span>
  <span m='866370'>in</span> <span m='866460'>particular--</span> <span m='868410'>I</span>
  <span m='868500'>mean,</span> <span m='868680'>they</span> <span m='868770'>should</span>
  <span m='869010'>match</span> <span m='869490'>this</span> <span m='869760'>thing</span>
  <span m='870720'>at</span> <span m='870810'>some</span> <span m='871050'>points.</span>
  <span m='871920'>So</span> <span m='872310'>when</span> <span m='873390'>a</span>
  <span m='873810'>is</span> <span m='874200'>order</span> <span m='874590'>log</span>
  <span m='874880'>n,</span> <span m='875370'>that's</span> <span m='875610'>when</span>
  <span m='875760'>you</span> <span m='875850'>have</span> <span m='876000'>polynomial</span>
  <span m='876720'>space,</span> <span m='877110'>which</span> <span m='877320'>would</span>
  <span m='877470'>be</span> <span m='877710'>very</span> <span m='877950'>difficult</span>
  <span m='878370'>to</span> <span m='878460'>update.</span> </p><p><span m='879710'>You</span>
  <span m='879850'>need</span> <span m='880020'>polynomial</span> <span m='880620'>time</span>
  <span m='880890'>updates.</span> <span m='881510'>But</span> <span m='882720'>that's</span>
  <span m='882930'>what</span> <span m='883290'>this</span> <span m='884030'>static</span>
  <span m='884430'>data</span> <span m='884580'>structure</span> <span m='884920'>uses</span>
  <span m='885120'>polynomial</span> <span m='885630'>space.</span> <span m='887560'>And</span>
  <span m='887660'>so</span> <span m='887940'>with</span> <span m='888150'>polynomial</span>
  <span m='888720'>space,</span> <span m='889540'>if you</span> <span m='889980'>plug
  in a</span> <span m='890370'>equals</span> <span m='890730'>log</span> <span m='891000'>n,</span>
  <span m='891600'>you</span> <span m='891780'>end</span> <span m='891900'>up</span>
  <span m='892020'>improving</span> <span m='892410'>by</span> <span m='892560'>a</span>
  <span m='892620'>log</span> <span m='893100'>log</span> <span m='893550'>n</span>
  <span m='893760'>factor.</span> </p><p><span m='895000'>And</span> <span m='895100'>so</span>
  <span m='895680'>that's</span> <span m='895880'>where</span> <span m='896070'>we</span>
  <span m='897120'>are.</span> <span m='897360'>I</span> <span m='897420'>guess</span>
  <span m='897945'>there</span> <span m='898230'>should</span> <span m='898440'>be</span>
  <span m='898560'>a</span> <span m='898590'>square</span> <span m='898890'>root</span>
  <span m='899100'>in</span> <span m='899190'>there</span> <span m='899310'>somewhere.</span>
  <span m='900270'>This</span> <span m='900420'>is</span> <span m='900640'>a</span>
  <span m='900680'>log</span> <span m='900940'>w</span> <span m='901350'>over</span>
  <span m='901560'>log</span> <span m='901800'>log</span> <span m='901980'>w.</span>
  <span m='902670'>This</span> <span m='902910'>is</span> <span m='903060'>the</span>
  <span m='903720'>part</span> <span m='903930'>that</span> <span m='904080'>diverges</span>
  <span m='904650'>a</span> <span m='904680'>little</span> <span m='904860'>bit</span>
  <span m='905010'>from</span> <span m='905210'>Van Emde Boas.</span> <span m='905720'>And</span>
  <span m='905820'>this</span> <span m='905940'>really</span> <span m='906180'>is</span>
  <span m='906330'>achievable</span> <span m='907400'>if</span> <span m='907560'>you</span>
  <span m='907630'>have</span> <span m='907710'>polynomial</span> <span m='908340'>space,</span>
  <span m='908700'>instead</span> <span m='909000'>of</span> <span m='909090'>like</span>
  <span m='909330'>n</span> <span m='910230'>or</span> <span m='910350'>n</span> <span
  m='910530'>poly</span> <span m='910810'>log.</span> </p><p><span m='912330'>So</span>
  <span m='912480'>for</span> <span m='912660'>static,</span> <span m='913130'>yes,</span>
  <span m='913530'>you</span> <span m='913650'>can</span> <span m='913770'>get</span>
  <span m='913890'>these</span> <span m='914040'>log</span> <span m='914240'>log</span>
  <span m='914400'>n</span> <span m='914490'>improvements.</span> <span m='914970'>We</span>
  <span m='915090'>won't</span> <span m='915270'>cover</span> <span m='915510'>them</span>
  <span m='916230'>here.</span> <span m='917040'>I</span> <span m='917100'>mean,</span>
  <span m='917240'>they're</span> <span m='917350'>small</span> <span m='917580'>improvements.</span>
  <span m='919380'>And</span> <span m='919560'>we're</span> <span m='919680'>mostly</span>
  <span m='920010'>interested</span> <span m='920280'>in</span> <span m='920370'>dynamic</span>
  <span m='921570'>data</span> <span m='921810'>structures.</span> </p><p><span m='922650'>And</span>
  <span m='922800'>for</span> <span m='922950'>dynamic</span> <span m='923370'>data</span>
  <span m='923580'>structures,</span> <span m='926100'>these</span> <span m='926430'>things</span>
  <span m='926730'>don't</span> <span m='926940'>turn</span> <span m='927210'>out</span>
  <span m='927630'>to</span> <span m='927780'>help.</span> <span m='928950'>So</span>
  <span m='929190'>let</span> <span m='929310'>me</span> <span m='930150'>state</span>
  <span m='930450'>the</span> <span m='930540'>consequence,</span> <span m='931260'>which</span>
  <span m='931440'>is</span> <span m='931530'>what</span> <span m='931680'>I</span>
  <span m='931740'>stated</span> <span m='932130'>a</span> <span m='932190'>couple</span>
  <span m='932460'>of</span> <span m='932490'>classes</span> <span m='932940'>ago.</span>
  <span m='934080'>If</span> <span m='934260'>you</span> <span m='934380'>have</span>
  <span m='934740'>n</span> <span m='935040'>poly</span> <span m='935400'>log</span>
  <span m='935700'>n</span> <span m='935850'>space,</span> <span m='936320'>so if</span>
  <span m='936500'>you</span> <span m='936590'>have</span> <span m='936720'>polylogarithmic</span>
  <span m='937590'>update,</span> <span m='938020'>which</span> <span m='938100'>is</span>
  <span m='938190'>usually</span> <span m='938550'>the</span> <span m='938700'>situation</span>
  <span m='939210'>we</span> <span m='939300'>care</span> <span m='939510'>about,</span>
  <span m='940380'>then</span> <span m='942120'>we</span> <span m='942270'>get</span>
  <span m='942570'>min</span> <span m='944670'>of</span> <span m='946590'>log</span>
  <span m='947170'>base</span> <span m='947640'>w</span> <span m='948220'>of</span>
  <span m='948510'>n.</span> <span m='949200'>And</span> <span m='949290'>I'd</span>
  <span m='949410'>like</span> <span m='949590'>to</span> <span m='949680'>say</span>
  <span m='949860'>log</span> <span m='950100'>w,</span> <span m='950520'>but</span>
  <span m='950760'>you</span> <span m='950940'>can</span> <span m='951180'>actually</span>
  <span m='951420'>do</span> <span m='951540'>slightly</span> <span m='951960'>better.</span>
  </p><p><span m='963380'>Oh</span> <span m='963540'>God,</span> <span m='963960'>indeed.</span>
  <span m='965820'>I</span> <span m='965940'>think</span> <span m='966180'>I</span>
  <span m='966240'>stated</span> <span m='966570'>this</span> <span m='966810'>two</span>
  <span m='966990'>lectures</span> <span m='967320'>ago.</span> <span m='968820'>So</span>
  <span m='969060'>log</span> <span m='969280'>w</span> <span m='969660'>is</span>
  <span m='969750'>what</span> <span m='969900'>we</span> <span m='969990'>know</span>
  <span m='970140'>how</span> <span m='970290'>to</span> <span m='970380'>do.</span>
  <span m='970980'>This</span> <span m='971160'>is</span> <span m='971250'>a</span>
  <span m='971370'>very</span> <span m='971880'>small</span> <span m='972210'>improvement.</span>
  </p><p><span m='973630'>Let</span> <span m='973680'>me</span> <span m='973800'>state</span>
  <span m='974130'>another</span> <span m='974520'>consequence</span> <span m='975240'>of</span>
  <span m='975360'>this,</span> <span m='976330'>which</span> <span m='976500'>is</span>
  <span m='978040'>Van Emde Boas</span> <span m='982590'>is</span> <span m='982810'>optimal</span>
  <span m='986910'>for</span> <span m='988350'>w</span> <span m='989880'>poly</span>
  <span m='990510'>log</span> <span m='990870'>n.</span> <span m='994320'>OK,</span>
  <span m='994500'>that's</span> <span m='994740'>when</span> <span m='994920'>it</span>
  <span m='994980'>gets</span> <span m='995190'>log</span> <span m='995470'>log</span>
  <span m='995620'>n</span> <span m='995760'>performance.</span> <span m='997180'>And</span>
  <span m='997230'>so</span> <span m='998070'>you</span> <span m='998220'>can</span>
  <span m='998370'>check</span> <span m='998790'>in</span> <span m='998910'>that</span>
  <span m='999060'>case</span> <span m='999390'>this</span> <span m='999930'>term</span>
  <span m='1000230'>doesn't</span> <span m='1000470'>buy</span> <span m='1000680'>you</span>
  <span m='1000800'>anything.</span> </p><p><span m='1001550'>That's</span> <span
  m='1002390'>log</span> <span m='1002630'>w</span> <span m='1003020'>would</span>
  <span m='1003170'>be</span> <span m='1003320'>order</span> <span m='1003500'>log</span>
  <span m='1003740'>log</span> <span m='1003950'>n,</span> <span m='1004130'>if</span>
  <span m='1004280'>you're</span> <span m='1004400'>poly</span> <span m='1004700'>log.</span>
  <span m='1005330'>So</span> <span m='1005450'>this</span> <span m='1005630'>disappears.</span>
  <span m='1006260'>And</span> <span m='1006350'>you</span> <span m='1006410'>just</span>
  <span m='1006560'>get</span> <span m='1006740'>log</span> <span m='1006840'>w.</span>
  <span m='1008120'>So</span> <span m='1008330'>that's</span> <span m='1008570'>one</span>
  <span m='1008750'>thing.</span> </p><p><span m='1010430'>Fusion</span> <span m='1010820'>tries</span>
  <span m='1014450'>are</span> <span m='1014600'>optimal</span> <span m='1017810'>for</span>
  <span m='1021080'>log</span> <span m='1021650'>w</span> <span m='1024560'>order</span>
  <span m='1025819'>square</span> <span m='1026390'>root log</span> <span m='1026750'>n,</span>
  <span m='1027740'>times</span> <span m='1028339'>log</span> <span m='1028609'>log</span>
  <span m='1028790'>n.</span> <span m='1033589'>So</span> <span m='1033770'>this</span>
  <span m='1033950'>is</span> <span m='1034010'>saying</span> <span m='1034310'>w</span>
  <span m='1035089'>is</span> <span m='1035599'>at</span> <span m='1035750'>least</span>
  <span m='1036140'>2</span> <span m='1036480'>to</span> <span m='1036589'>the</span>
  <span m='1036740'>root</span> <span m='1036950'>log</span> <span m='1037290'>n,</span>
  <span m='1037530'>or</span> <span m='1037790'>actually</span> <span m='1038089'>log</span>
  <span m='1038450'>n</span> <span m='1038599'>to</span> <span m='1038720'>the</span>
  <span m='1038839'>root</span> <span m='1039020'>log</span> <span m='1039270'>n,</span>
  <span m='1039460'>if</span> <span m='1039890'>you</span> <span m='1039990'>want</span>
  <span m='1040130'>to</span> <span m='1040220'>include</span> <span m='1040490'>that</span>
  <span m='1040670'>term.</span> </p><p><span m='1041910'>So</span> <span m='1041990'>that's</span>
  <span m='1042200'>a</span> <span m='1042260'>fairly</span> <span m='1042560'>large</span>
  <span m='1042920'>w.</span> <span m='1043220'>So</span> <span m='1043369'>for</span>
  <span m='1043490'>large</span> <span m='1043760'>w,</span> <span m='1044089'>fusion</span>
  <span m='1044359'>tires</span> <span m='1044540'>are</span> <span m='1044630'>optimal.</span>
  <span m='1045290'>For</span> <span m='1045380'>small</span> <span m='1045619'>w,</span>
  <span m='1045869'>Van Emde Boas</span> <span m='1046369'>is</span> <span m='1046550'>optimal.</span>
  <span m='1047130'>In</span> <span m='1047479'>between,</span> <span m='1048680'>this</span>
  <span m='1048950'>thing</span> <span m='1049190'>is</span> <span m='1049280'>optimal.</span>
  </p><p><span m='1051660'>That's</span> <span m='1052500'>the</span> <span m='1052620'>reality</span>
  <span m='1053070'>of</span> <span m='1053190'>it.</span> <span m='1053270'>It's</span>
  <span m='1053370'>a</span> <span m='1053400'>little</span> <span m='1053580'>messy.</span>
  <span m='1054420'>But</span> <span m='1054540'>this</span> <span m='1054750'>is</span>
  <span m='1055050'>tight.</span> <span m='1055590'>So</span> <span m='1055800'>this</span>
  <span m='1055980'>is</span> <span m='1056070'>the</span> <span m='1056160'>right</span>
  <span m='1056310'>answer.</span> </p><p><span m='1058620'>I</span> <span m='1058680'>think</span>
  <span m='1058920'>most</span> <span m='1059130'>of</span> <span m='1059190'>the</span>
  <span m='1059250'>time,</span> <span m='1059700'>the</span> <span m='1060120'>situations</span>
  <span m='1060630'>you</span> <span m='1060690'>care</span> <span m='1060870'>about,</span>
  <span m='1061530'>w</span> <span m='1061830'>is</span> <span m='1061920'>probably</span>
  <span m='1062190'>going</span> <span m='1062340'>to</span> <span m='1062400'>be</span>
  <span m='1062460'>small.</span> <span m='1062980'>So</span> <span m='1063030'>you</span>
  <span m='1063120'>should</span> <span m='1063260'>use</span> <span m='1063360'>Van
  Emde Boas.</span> <span m='1064140'>If</span> <span m='1064700'>w</span> <span m='1065070'>really</span>
  <span m='1065310'>large,</span> <span m='1065850'>you</span> <span m='1065940'>should</span>
  <span m='1066080'>use</span> <span m='1066170'>fusion</span> <span m='1066510'>tries.</span>
  <span m='1067380'>In</span> <span m='1067500'>between,</span> <span m='1067980'>you</span>
  <span m='1068130'>could</span> <span m='1068340'>consider</span> <span m='1068760'>this</span>
  <span m='1068970'>trade-off.</span> <span m='1069420'>But</span> <span m='1070800'>it's</span>
  <span m='1070950'>not</span> <span m='1071520'>it's</span> <span m='1071700'>not</span>
  <span m='1071970'>much</span> <span m='1072300'>better</span> <span m='1072600'>than</span>
  <span m='1072750'>Van Emde Boas.</span> <span m='1073950'>So</span> <span m='1075480'>take</span>
  <span m='1075690'>that</span> <span m='1075840'>for</span> <span m='1075960'>what</span>
  <span m='1076080'>it</span> <span m='1076170'>is.</span> </p><p><span m='1076530'>So</span>
  <span m='1076680'>that's</span> <span m='1076890'>what's</span> <span m='1077040'>known.</span>
  <span m='1077970'>As</span> <span m='1078180'>I</span> <span m='1078240'>said,</span>
  <span m='1078480'>we're</span> <span m='1078690'>going</span> <span m='1078930'>to</span>
  <span m='1079050'>cover</span> <span m='1079350'>this</span> <span m='1079950'>sen</span>
  <span m='1080360'>proof,</span> <span m='1081420'>which</span> <span m='1081630'>will</span>
  <span m='1081750'>be</span> <span m='1081880'>tight</span> <span m='1082230'>up</span>
  <span m='1082380'>to</span> <span m='1082500'>this</span> <span m='1082680'>log</span>
  <span m='1082940'>log</span> <span m='1083130'>factor.</span> <span m='1086220'>And</span>
  <span m='1086430'>this</span> <span m='1086610'>holds</span> <span m='1087450'>as</span>
  <span m='1087630'>long</span> <span m='1087930'>as</span> <span m='1088020'>your</span>
  <span m='1088140'>space</span> <span m='1088500'>is</span> <span m='1088610'>polynomial.</span>
  <span m='1089860'>So</span> <span m='1090160'>it</span> <span m='1090240'>doesn't</span>
  <span m='1090780'>assume</span> <span m='1091050'>very</span> <span m='1091260'>much</span>
  <span m='1091500'>about</span> <span m='1091740'>space.</span> </p><p><span m='1094500'>And</span>
  <span m='1094710'>it's</span> <span m='1094800'>going</span> <span m='1094950'>to</span>
  <span m='1095010'>be</span> <span m='1095160'>a</span> <span m='1095190'>lower</span>
  <span m='1095430'>bound</span> <span m='1095730'>for</span> <span m='1095940'>a</span>
  <span m='1096030'>slightly</span> <span m='1096570'>easier</span> <span m='1097020'>problem.</span>
  <span m='1098850'>If</span> <span m='1099200'>you</span> <span m='1099300'>can</span>
  <span m='1099450'>prove</span> <span m='1099630'>a</span> <span m='1099690'>lower</span>
  <span m='1099900'>bound</span> <span m='1100110'>on</span> <span m='1100230'>an</span>
  <span m='1100290'>easier</span> <span m='1100650'>problem,</span> <span m='1101010'>that</span>
  <span m='1101160'>implies</span> <span m='1101640'>a</span> <span m='1101700'>lower</span>
  <span m='1101910'>bound</span> <span m='1102210'>on</span> <span m='1102390'>the</span>
  <span m='1102480'>harder</span> <span m='1102750'>problem.</span> <span m='1107529'>The</span>
  <span m='1108010'>easier</span> <span m='1108310'>problem</span> <span m='1108610'>is</span>
  <span m='1108700'>called the</span> <span m='1109090'>colored</span> <span m='1109630'>predecessor</span>
  <span m='1110240'>problem.</span> </p><p><span m='1112040'>In</span> <span m='1112370'>colored</span>
  <span m='1112720'>predecessor,</span> <span m='1114700'>each</span> <span m='1114940'>element</span>
  <span m='1118270'>is</span> <span m='1118540'>red</span> <span m='1120160'>or</span>
  <span m='1120340'>blue.</span> <span m='1124540'>I</span> <span m='1124720'>should</span>
  <span m='1124900'>say</span> <span m='1125140'>blue,</span> <span m='1126360'>whatever,</span>
  <span m='1126960'>anyway,</span> <span m='1129780'>no</span> <span m='1129940'>Team</span>
  <span m='1130150'>Fortress</span> <span m='1130540'>fans,</span> <span m='1130930'>I</span>
  <span m='1130990'>guess.</span> <span m='1132670'>So</span> <span m='1135660'>and</span>
  <span m='1135820'>now a</span> <span m='1136030'>query</span> <span m='1139950'>just</span>
  <span m='1140260'>reports</span> <span m='1140740'>the</span> <span m='1140860'>color</span>
  <span m='1144820'>of</span> <span m='1144970'>the</span> <span m='1145060'>predecessor.</span>
  </p><p><span m='1148690'>You</span> <span m='1148780'>don't</span> <span m='1149080'>need</span>
  <span m='1149320'>to</span> <span m='1149530'>report</span> <span m='1150100'>the</span>
  <span m='1150220'>key</span> <span m='1150430'>value,</span> <span m='1151270'>just</span>
  <span m='1151510'>whether</span> <span m='1151750'>it</span> <span m='1151840'>is</span>
  <span m='1151960'>red</span> <span m='1152170'>or</span> <span m='1152260'>blue.</span>
  <span m='1153310'>So,</span> <span m='1153520'>again,</span> <span m='1154120'>you've</span>
  <span m='1154360'>got</span> <span m='1155080'>your</span> <span m='1155380'>universe.</span>
  <span m='1156400'>Some</span> <span m='1156670'>of</span> <span m='1156760'>the</span>
  <span m='1157030'>items</span> <span m='1157570'>are</span> <span m='1157750'>present.</span>
  </p><p><span m='1159880'>And</span> <span m='1160060'>your</span> <span m='1160150'>query</span>
  <span m='1160720'>is</span> <span m='1161320'>an</span> <span m='1161440'>arbitrary</span>
  <span m='1161830'>universe</span> <span m='1162250'>element.</span> <span m='1163000'>And</span>
  <span m='1163090'>you</span> <span m='1163210'>want</span> <span m='1163390'>a</span>
  <span m='1163990'>predecessor</span> <span m='1164790'>kind</span> <span m='1164980'>of</span>
  <span m='1165070'>this</span> <span m='1165280'>way.</span> <span m='1166030'>And</span>
  <span m='1166300'>this</span> <span m='1166390'>guy</span> <span m='1166660'>is</span>
  <span m='1166810'>either</span> <span m='1166990'>red</span> <span m='1167200'>or</span>
  <span m='1167290'>blue.</span> <span m='1168130'>And</span> <span m='1168220'>you</span>
  <span m='1168340'>just</span> <span m='1168490'>want</span> <span m='1168640'>to</span>
  <span m='1168700'>report</span> <span m='1169120'>which</span> <span m='1169300'>one</span>
  <span m='1169480'>is</span> <span m='1169660'>it?</span> </p><p><span m='1171070'>So</span>
  <span m='1171220'>this</span> <span m='1171400'>is,</span> <span m='1171520'>of</span>
  <span m='1171610'>course,</span> <span m='1171850'>easier,</span> <span m='1172630'>because</span>
  <span m='1173140'>you</span> <span m='1173320'>could</span> <span m='1173410'>just</span>
  <span m='1173620'>have</span> <span m='1174450'>a</span> <span m='1174520'>lookup</span>
  <span m='1174850'>table,</span> <span m='1175270'>a</span> <span m='1175300'>hash</span>
  <span m='1175570'>table</span> <span m='1175870'>for</span> <span m='1175990'>example,</span>
  <span m='1176440'>that</span> <span m='1176860'>once</span> <span m='1177070'>you</span>
  <span m='1177160'>determine</span> <span m='1177550'>the</span> <span m='1177640'>key,</span>
  <span m='1177940'>you</span> <span m='1178060'>could</span> <span m='1178210'>figure</span>
  <span m='1178420'>out</span> <span m='1178540'>whether</span> <span m='1178720'>it's</span>
  <span m='1178840'>red</span> <span m='1178990'>or</span> <span m='1179050'>blue.</span>
  <span m='1179220'>It's</span> <span m='1179350'>a</span> <span m='1179410'>static</span>
  <span m='1179860'>data</span> <span m='1180070'>structure.</span> <span m='1180610'>So</span>
  <span m='1182130'>you</span> <span m='1182270'>could</span> <span m='1182410'>use</span>
  <span m='1182590'>perfect</span> <span m='1182980'>hashing.</span> <span m='1184540'>It
  could</span> <span m='1184660'>be</span> <span m='1184750'>totally</span> <span
  m='1185050'>deterministic</span> <span m='1185680'>once</span> <span m='1185860'>you</span>
  <span m='1185950'>set</span> <span m='1186160'>it</span> <span m='1186250'>up.</span>
  </p><p><span m='1188560'>And</span> <span m='1188800'>so,</span> <span m='1189300'>OK,</span>
  <span m='1189730'>just</span> <span m='1189910'>reporting</span> <span m='1190210'>the</span>
  <span m='1190270'>colors,</span> <span m='1190660'>of</span> <span m='1190720'>course</span>
  <span m='1190900'>easier</span> <span m='1191140'>than</span> <span m='1191230'>reporting</span>
  <span m='1191680'>the</span> <span m='1191770'>key.</span> <span m='1193030'>One</span>
  <span m='1193360'>interesting</span> <span m='1193810'>thing</span> <span m='1193930'>about</span>
  <span m='1194140'>this</span> <span m='1194320'>problem</span> <span m='1194620'>is</span>
  <span m='1194740'>it's</span> <span m='1194860'>very</span> <span m='1195100'>easy</span>
  <span m='1195430'>to</span> <span m='1195610'>get</span> <span m='1195820'>a</span>
  <span m='1195880'>correct</span> <span m='1196210'>answer</span> <span m='1196510'>with</span>
  <span m='1196630'>probability</span> <span m='1197260'>50%.</span> <span m='1198640'>You</span>
  <span m='1198760'>flip</span> <span m='1199030'>a</span> <span m='1199090'>coin.</span>
  </p><p><span m='1200110'>Heads</span> <span m='1200420'>is</span> <span m='1200530'>red,</span>
  <span m='1200860'>tails is</span> <span m='1201250'>blue.</span> <span m='1203200'>And</span>
  <span m='1204250'>this</span> <span m='1204520'>lower</span> <span m='1204790'>bound</span>
  <span m='1205100'>we</span> <span m='1205200'>proved</span> <span m='1205360'>will</span>
  <span m='1205570'>actually</span> <span m='1206110'>apply</span> <span m='1206470'>to</span>
  <span m='1206590'>randomized</span> <span m='1207010'>data</span> <span m='1207190'>structures</span>
  <span m='1207700'>that</span> <span m='1207850'>work</span> <span m='1208090'>with</span>
  <span m='1208210'>some</span> <span m='1208390'>probability.</span> <span m='1209530'>But</span>
  <span m='1209590'>it</span> <span m='1209650'>has</span> <span m='1209800'>to</span>
  <span m='1209920'>be</span> <span m='1210040'>probability</span> <span m='1210700'>greater</span>
  <span m='1211000'>than</span> <span m='1211200'>half</span> <span m='1212400'>of</span>
  <span m='1212560'>succeeding.</span> </p><p><span m='1214720'>And</span> <span m='1214960'>this</span>
  <span m='1215290'>will</span> <span m='1215440'>be</span> <span m='1215590'>useful,</span>
  <span m='1216010'>because</span> <span m='1216340'>we're</span> <span m='1216430'>going</span>
  <span m='1216550'>to</span> <span m='1216700'>take</span> <span m='1216970'>our</span>
  <span m='1217060'>problem. And</span> <span m='1217540'>we're</span> <span m='1217630'>going</span>
  <span m='1217750'>to</span> <span m='1218530'>modify</span> <span m='1218815'>it</span>
  <span m='1219100'>a</span> <span m='1219160'>little</span> <span m='1219400'>bit,</span>
  <span m='1219610'>and</span> <span m='1219700'>sort</span> <span m='1219880'>of</span>
  <span m='1220000'>make</span> <span m='1220240'>it</span> <span m='1220330'>simpler</span>
  <span m='1220690'>and</span> <span m='1220810'>simpler.</span> <span m='1221710'>And</span>
  <span m='1221890'>it's</span> <span m='1222010'>easier</span> <span m='1222340'>to</span>
  <span m='1222430'>preserve</span> <span m='1222820'>this</span> <span m='1222970'>color</span>
  <span m='1223300'>property</span> <span m='1223810'>than</span> <span m='1224050'>to</span>
  <span m='1224200'>preserve</span> <span m='1225100'>actual</span> <span m='1225490'>key</span>
  <span m='1225700'>values.</span> <span m='1227750'>So</span> <span m='1227920'>that's</span>
  <span m='1228680'>the colored</span> <span m='1228880'>predecessor.</span> </p><p><span
  m='1230170'>Now,</span> <span m='1230500'>we</span> <span m='1230650'>get</span>
  <span m='1230890'>to</span> <span m='1232120'>communication</span> <span m='1232780'>complexity</span>
  <span m='1233320'>perspective.</span> <span m='1235850'>So</span> <span m='1236150'>this</span>
  <span m='1236360'>is</span> <span m='1237290'>pretty</span> <span m='1237500'>cool.</span>
  <span m='1241740'>And</span> <span m='1241800'>it</span> <span m='1241860'>brings</span>
  <span m='1242160'>us</span> <span m='1242310'>to</span> <span m='1242430'>the</span>
  <span m='1242550'>idea</span> <span m='1242760'>of round</span> <span m='1243060'>elimination.</span>
  </p><p><span m='1247680'>So</span> <span m='1248490'>communication--</span> <span
  m='1268320'>OK,</span> <span m='1269710'>why don't</span> <span m='1270100'>I</span>
  <span m='1270190'>tell</span> <span m='1270400'>you</span> <span m='1270670'>the</span>
  <span m='1271810'>generic</span> <span m='1272680'>communication</span> <span m='1273220'>complexity</span>
  <span m='1273700'>picture</span> <span m='1274930'>out of</span> <span m='1275110'>Alice</span>
  <span m='1275410'>and</span> <span m='1275500'>Bob?</span> <span m='1275800'>And</span>
  <span m='1275920'>then</span> <span m='1276070'>I'll</span> <span m='1276160'>tell</span>
  <span m='1276310'>you</span> <span m='1276430'>how</span> <span m='1276580'>it</span>
  <span m='1276640'>relates</span> <span m='1276970'>to</span> <span m='1277090'>data</span>
  <span m='1277300'>structures.</span> <span m='1278560'>They're</span> <span m='1278680'>both</span>
  <span m='1279250'>simple.</span> <span m='1279790'>But</span> <span m='1280570'>I've</span>
  <span m='1280690'>got</span> <span m='1280810'>to</span> <span m='1280900'>do</span>
  <span m='1281020'>something</span> <span m='1281410'>first.</span> </p><p><span
  m='1282850'>So</span> <span m='1283000'>let's</span> <span m='1283180'>say</span>
  <span m='1283570'>Alice</span> <span m='1284340'>is</span> <span m='1284470'>one</span>
  <span m='1285490'>person</span> <span m='1287530'>who</span> <span m='1287740'>knows</span>
  <span m='1288050'>some</span> <span m='1289420'>value</span> <span m='1289780'>x.</span>
  <span m='1291370'>Over</span> <span m='1291640'>here,</span> <span m='1291880'>we</span>
  <span m='1292000'>have</span> <span m='1292240'>Bob</span> <span m='1293920'>who</span>
  <span m='1294100'>knows</span> <span m='1295450'>some</span> <span m='1295690'>value</span>
  <span m='1296080'>y.</span> <span m='1298480'>The</span> <span m='1298600'>goal</span>
  <span m='1303930'>is</span> <span m='1304200'>to--</span> <span m='1305040'>I'll
  move</span> <span m='1305520'>this a</span> <span m='1305760'>little</span> <span
  m='1305970'>bit</span> <span m='1306090'>to</span> <span m='1306200'>the</span>
  <span m='1306270'>left.</span> </p><p><span m='1310310'>Their</span> <span m='1310460'>collective</span>
  <span m='1311030'>goal--</span> <span m='1311360'>they're</span> <span m='1311480'>trying</span>
  <span m='1311690'>to</span> <span m='1311780'>cooperate.</span> <span m='1313400'>Their</span>
  <span m='1313520'>goal</span> <span m='1313700'>is</span> <span m='1313820'>to</span>
  <span m='1313910'>compute</span> <span m='1314210'>some</span> <span m='1314390'>function</span>
  <span m='1314810'>of</span> <span m='1315020'>x</span> <span m='1315290'>and</span>
  <span m='1315380'>y.</span> <span m='1317570'>The</span> <span m='1317660'>trouble</span>
  <span m='1318020'>is</span> <span m='1318650'>only</span> <span m='1318950'>Alice</span>
  <span m='1319280'>knows</span> <span m='1319490'>x,</span> <span m='1319790'>and</span>
  <span m='1319880'>only</span> <span m='1320150'>Bob</span> <span m='1320420'>knows</span>
  <span m='1320630'>y.</span> </p><p><span m='1321680'>So</span> <span m='1321770'>how</span>
  <span m='1321890'>did</span> <span m='1322010'>they</span> <span m='1322130'>do</span>
  <span m='1322280'>it?</span> <span m='1322520'>They</span> <span m='1322640'>have</span>
  <span m='1322720'>to</span> <span m='1322780'>talk</span> <span m='1323060'>to</span>
  <span m='1323150'>each</span> <span m='1323330'>other.</span> <span m='1323990'>Ideally,</span>
  <span m='1324470'>Alice</span> <span m='1324770'>sends</span> <span m='1325130'>Bob</span>
  <span m='1325490'>x,</span> <span m='1325880'>or</span> <span m='1325970'>Bob</span>
  <span m='1326240'>sends</span> <span m='1326750'>Alice</span> <span m='1327070'>y.</span>
  <span m='1327650'>One of</span> <span m='1327740'>them</span> <span m='1327860'>could
  compute</span> <span m='1328160'>it,</span> <span m='1328460'>send</span> <span
  m='1328700'>back</span> <span m='1328910'>the</span> <span m='1329030'>answer.</span>
  </p><p><span m='1330110'>That's</span> <span m='1330290'>one</span> <span m='1330500'>possibility.</span>
  <span m='1331080'>But</span> <span m='1331130'>maybe</span> <span m='1331370'>x</span>
  <span m='1331520'>and</span> <span m='1331610'>y</span> <span m='1331790'>are</span>
  <span m='1331880'>kind</span> <span m='1332060'>of</span> <span m='1332150'>big,</span>
  <span m='1332480'>and</span> <span m='1332690'>you</span> <span m='1332810'>can't</span>
  <span m='1333020'>just</span> <span m='1333170'>send</span> <span m='1333410'>it</span>
  <span m='1333500'>in</span> <span m='1333620'>one</span> <span m='1333770'>message.</span>
  <span m='1335030'>So</span> <span m='1335750'>here's</span> <span m='1336050'>the</span>
  <span m='1337040'>restriction.</span> </p><p><span m='1338750'>Alice</span> <span
  m='1339860'>can</span> <span m='1340040'>send</span> <span m='1340280'>messages</span>
  <span m='1341960'>with</span> <span m='1343490'>less</span> <span m='1343850'>than</span>
  <span m='1343970'>or</span> <span m='1344060'>equal</span> <span m='1344330'>to</span>
  <span m='1344600'>little</span> <span m='1344960'>a</span> <span m='1345890'>bits,</span>
  <span m='1346490'>a</span> <span m='1346640'>for</span> <span m='1346850'>Alice.</span>
  <span m='1348120'>Bob</span> <span m='1348530'>can</span> <span m='1348740'>send</span>
  <span m='1349010'>messages</span> <span m='1352130'>with</span> <span m='1353360'>less</span>
  <span m='1353690'>than</span> <span m='1353810'>or</span> <span m='1353900'>equal</span>
  <span m='1354170'>to</span> <span m='1354350'>little</span> <span m='1354650'>b</span>
  <span m='1354860'>bits,</span> <span m='1355240'>b</span> <span m='1355500'>for</span>
  <span m='1355640'>Bob.</span> <span m='1358180'>So</span> <span m='1358330'>that's</span>
  <span m='1358580'>the</span> <span m='1358660'>constraint.</span> </p><p><span m='1359060'>And,</span>
  <span m='1359130'>potentially,</span> <span m='1360340'>x</span> <span m='1360670'>is</span>
  <span m='1360790'>much</span> <span m='1361030'>larger</span> <span m='1361330'>than</span>
  <span m='1361480'>a,</span> <span m='1361930'>and/or</span> <span m='1363100'>y</span>
  <span m='1363400'>is</span> <span m='1363520'>much</span> <span m='1363730'>longer</span>
  <span m='1363940'>than</span> <span m='1364090'>b.</span> <span m='1364300'>And</span>
  <span m='1364390'>so</span> <span m='1364600'>you're</span> <span m='1364780'>going</span>
  <span m='1364900'>to</span> <span m='1364990'>have</span> <span m='1365230'>to</span>
  <span m='1365350'>spend</span> <span m='1365800'>many</span> <span m='1366070'>messages.</span>
  <span m='1367510'>And</span> <span m='1368140'>let's</span> <span m='1368470'>restrict</span>
  <span m='1368920'>to</span> <span m='1369130'>protocols</span> <span m='1369760'>of</span>
  <span m='1369850'>the</span> <span m='1369970'>form</span> <span m='1370660'>Alice</span>
  <span m='1370960'>talks</span> <span m='1371170'>to</span> <span m='1371260'>Bob,</span>
  <span m='1371580'>then</span> <span m='1371710'>Bob</span> <span m='1372060'>talks</span>
  <span m='1372580'>to</span> <span m='1372670'>Alice,</span> <span m='1373030'>and</span>
  <span m='1373210'>back</span> <span m='1373450'>and</span> <span m='1373540'>forth,</span>
  <span m='1373780'>so</span> <span m='1374065'>rounds</span> <span m='1374350'>of</span>
  <span m='1374470'>communication.</span> </p><p><span m='1375540'>And</span> <span
  m='1375700'>you</span> <span m='1375790'>want</span> <span m='1375910'>to</span>
  <span m='1375970'>know,</span> <span m='1376090'>how</span> <span m='1376300'>many</span>
  <span m='1376510'>rounds</span> <span m='1376930'>does</span> <span m='1377110'>it</span>
  <span m='1377170'>take</span> <span m='1377920'>to</span> <span m='1378040'>compute</span>
  <span m='1378400'>f</span> <span m='1378640'>of</span> <span m='1378730'>xy?</span>
  <span m='1379660'>And,</span> <span m='1379780'>of</span> <span m='1379900'>course,</span>
  <span m='1380180'>it</span> <span m='1380280'>depends</span> <span m='1380470'>on</span>
  <span m='1380620'>f.</span> <span m='1382300'>OK,</span> <span m='1382900'>that's</span>
  <span m='1383170'>the</span> <span m='1383260'>totally</span> <span m='1383740'>generic</span>
  <span m='1384160'>picture.</span> <span m='1384790'>And</span> <span m='1385000'>there's</span>
  <span m='1385390'>techniques</span> <span m='1386470'>which</span> <span m='1386650'>we're</span>
  <span m='1386710'>going</span> <span m='1386830'>to</span> <span m='1386920'>use</span>
  <span m='1387310'>for</span> <span m='1388240'>lower</span> <span m='1388540'>bounds</span>
  <span m='1388930'>on</span> <span m='1389080'>how</span> <span m='1389290'>long</span>
  <span m='1389500'>these</span> <span m='1389650'>protocols</span> <span m='1390040'>have</span>
  <span m='1390220'>to</span> <span m='1390310'>be.</span> </p><p><span m='1391030'>How</span>
  <span m='1391300'>does</span> <span m='1391480'>this</span> <span m='1391630'>relate</span>
  <span m='1392140'>to</span> <span m='1393820'>colored</span> <span m='1394240'>predecessor?</span>
  <span m='1395170'>And,</span> <span m='1395290'>remember,</span> <span m='1395650'>also</span>
  <span m='1396040'>there's</span> <span m='1396340'>the</span> <span m='1396520'>model</span>
  <span m='1396910'>of</span> <span m='1397000'>computation,</span> <span m='1397810'>which</span>
  <span m='1398340'>I</span> <span m='1398410'>should</span> <span m='1398560'>mention,</span>
  <span m='1398950'>cell</span> <span m='1399420'>probe</span> <span m='1399810'>model.</span>
  <span m='1401330'>Cell</span> <span m='1402400'>probe</span> <span m='1402770'>model,</span>
  <span m='1403090'>we</span> <span m='1403270'>just</span> <span m='1403540'>count</span>
  <span m='1405220'>the</span> <span m='1405370'>number</span> <span m='1406180'>of--</span>
  <span m='1407140'>in</span> <span m='1407250'>this</span> <span m='1407440'>case,</span>
  <span m='1407770'>because</span> <span m='1407950'>it's</span> <span m='1408060'>a</span>
  <span m='1408160'>static</span> <span m='1408520'>data</span> <span m='1408730'>structure,</span>
  <span m='1409150'>we</span> <span m='1409270'>don't</span> <span m='1409420'>really</span>
  <span m='1409630'>change</span> <span m='1409960'>it.</span> </p><p><span m='1412110'>Let's</span>
  <span m='1412270'>say</span> <span m='1412540'>memory</span> <span m='1413680'>word</span>
  <span m='1415350'>reads.</span> <span m='1417590'>We</span> <span m='1417690'>want</span>
  <span m='1417730'>to</span> <span m='1417790'>know</span> <span m='1417910'>how</span>
  <span m='1418150'>many</span> <span m='1418870'>words</span> <span m='1419530'>of</span>
  <span m='1419740'>the</span> <span m='1419830'>data</span> <span m='1420040'>structure</span>
  <span m='1420370'>do</span> <span m='1420490'>we</span> <span m='1420580'>need</span>
  <span m='1420730'>to</span> <span m='1420850'>read</span> <span m='1421120'>in</span>
  <span m='1421240'>order</span> <span m='1421420'>to</span> <span m='1421540'>answer</span>
  <span m='1421990'>a</span> <span m='1422170'>colored</span> <span m='1422440'>predecessor</span>
  <span m='1423010'>data</span> <span m='1423190'>structure?</span> <span m='1423670'>If
  we</span> <span m='1423760'>can</span> <span m='1423880'>prove</span> <span m='1424030'>a</span>
  <span m='1424060'>lower</span> <span m='1424210'>bound</span> <span m='1424420'>on</span>
  <span m='1424540'>this,</span> <span m='1424780'>of</span> <span m='1424870'>course</span>
  <span m='1425210'>it</span> <span m='1425310'>applies</span> <span m='1425620'>lower</span>
  <span m='1425980'>bound</span> <span m='1426130'>on</span> <span m='1426430'>the</span>
  <span m='1426520'>word</span> <span m='1426700'>RAM,</span> <span m='1427060'>or</span>
  <span m='1427150'>pick</span> <span m='1427330'>your</span> <span m='1427420'>favorite</span>
  <span m='1427750'>model</span> <span m='1428650'>that</span> <span m='1428770'>works</span>
  <span m='1428980'>with</span> <span m='1429100'>words,</span> <span m='1430710'>transdichotomous</span>
  <span m='1431890'>RAM,</span> <span m='1432430'>whatever.</span> </p><p><span m='1434410'>OK,</span>
  <span m='1434680'>so</span> <span m='1434830'>I</span> <span m='1434920'>want</span>
  <span m='1435100'>to</span> <span m='1435190'>cast</span> <span m='1435640'>that</span>
  <span m='1435820'>cell</span> <span m='1436150'>probe</span> <span m='1436390'>picture</span>
  <span m='1437170'>in</span> <span m='1437290'>terms</span> <span m='1437590'>of</span>
  <span m='1437680'>this</span> <span m='1437860'>picture.</span> <span m='1439760'>So</span>
  <span m='1439810'>here's</span> <span m='1440020'>the</span> <span m='1440140'>idea.</span>
  <span m='1441190'>Maybe</span> <span m='1441520'>I'll</span> <span m='1441670'>switch</span>
  <span m='1441910'>colors.</span> </p><p><span m='1446440'>Alice</span> <span m='1448660'>is</span>
  <span m='1450370'>the--</span> <span m='1451810'>I</span> <span m='1452290'>guess</span>
  <span m='1453100'>what</span> <span m='1453280'>do</span> <span m='1453340'>you</span>
  <span m='1453460'>want</span> <span m='1453640'>to</span> <span m='1453700'>call</span>
  <span m='1453880'>it,</span> <span m='1454000'>the</span> <span m='1454150'>algorithm,</span>
  <span m='1458850'>the</span> <span m='1459100'>query</span> <span m='1459450'>algorithm.</span>
  <span m='1461370'>OK,</span> <span m='1461970'>Alice</span> <span m='1462490'>is</span>
  <span m='1462640'>the</span> <span m='1462760'>poor</span> <span m='1463210'>soul</span>
  <span m='1463630'>who</span> <span m='1463780'>has</span> <span m='1464080'>to</span>
  <span m='1464320'>compute</span> <span m='1464920'>the</span> <span m='1465010'>color</span>
  <span m='1465340'>of</span> <span m='1465460'>a</span> <span m='1465490'>predecessor.</span>
  <span m='1467890'>And</span> <span m='1468010'>so</span> <span m='1468190'>what's</span>
  <span m='1468460'>x?</span> <span m='1468820'>x</span> <span m='1469180'>is</span>
  <span m='1469480'>the</span> <span m='1469600'>query.</span> </p><p><span m='1471610'>We're</span>
  <span m='1471710'>used</span> <span m='1471880'>to</span> <span m='1472000'>that.</span>
  <span m='1472990'>That</span> <span m='1473200'>is</span> <span m='1473320'>the</span>
  <span m='1473440'>input</span> <span m='1473890'>to</span> <span m='1474640'>the</span>
  <span m='1474700'>predecessor.</span> <span m='1475300'>So</span> <span m='1475450'>it's</span>
  <span m='1476710'>a</span> <span m='1476770'>single</span> <span m='1477070'>word,</span>
  <span m='1478520'>which is</span> <span m='1478870'>I</span> <span m='1478990'>want</span>
  <span m='1479150'>another</span> <span m='1479410'>predecessor</span> <span m='1480010'>of</span>
  <span m='1480070'>some</span> <span m='1480280'>value.</span> </p><p><span m='1483640'>Bob,</span>
  <span m='1484505'>on</span> <span m='1484830'>the</span> <span m='1484970'>other</span>
  <span m='1485110'>hand,</span> <span m='1485920'>is</span> <span m='1486130'>the</span>
  <span m='1486250'>data</span> <span m='1486460'>structure.</span> <span m='1490470'>That's</span>
  <span m='1490860'>the</span> <span m='1490980'>static</span> <span m='1492270'>thing.</span>
  <span m='1492750'>Where</span> <span m='1492840'>Bob</span> <span m='1493080'>represents</span>
  <span m='1493350'>the</span> <span m='1493620'>data</span> <span m='1493740'>structure,</span>
  <span m='1494180'>y</span> <span m='1494550'>actually</span> <span m='1494970'>is</span>
  <span m='1495270'>the</span> <span m='1495390'>data</span> <span m='1495600'>structure.</span>
  </p><p><span m='1498660'>I</span> <span m='1498750'>guess</span> <span m='1499950'>if</span>
  <span m='1500290'>I</span> <span m='1500390'>want</span> <span m='1500460'>to</span>
  <span m='1500530'>be</span> <span m='1501210'>a</span> <span m='1501300'>little</span>
  <span m='1501570'>bit</span> <span m='1501750'>more</span> <span m='1503250'>prosaic</span>
  <span m='1503850'>or</span> <span m='1503940'>something,</span> <span m='1505080'>Bob</span>
  <span m='1505620'>you</span> <span m='1505710'>can</span> <span m='1505860'>think</span>
  <span m='1506100'>of</span> <span m='1506370'>as</span> <span m='1506700'>memory.</span>
  <span m='1512240'>We'll call</span> <span m='1512380'>it</span> <span m='1512655'>RAM,</span>
  <span m='1512930'>to</span> <span m='1513110'>be</span> <span m='1513260'>a</span>
  <span m='1513290'>little</span> <span m='1513500'>more</span> <span m='1515300'>space</span>
  <span m='1515630'>saving.</span> <span m='1516590'>So</span> <span m='1516770'>Bob</span>
  <span m='1517070'>is</span> <span m='1517190'>the</span> <span m='1517310'>memory</span>
  <span m='1517610'>which</span> <span m='1517760'>you</span> <span m='1517880'>can</span>
  <span m='1518030'>access</span> <span m='1518660'>in</span> <span m='1518870'>random</span>
  <span m='1520580'>access.</span> <span m='1521750'>And</span> <span m='1521930'>what</span>
  <span m='1522140'>it</span> <span m='1522230'>knows</span> <span m='1522830'>is</span>
  <span m='1523070'>the</span> <span m='1523190'>data</span> <span m='1523370'>structure.</span>
  <span m='1523690'>I</span> <span m='1523730'>mean,</span> <span m='1523850'>that's</span>
  <span m='1524030'>what</span> <span m='1524150'>it's</span> <span m='1524240'>storing.</span>
  <span m='1525050'>That's</span> <span m='1525200'>all</span> <span m='1525380'>it's</span>
  <span m='1525490'>storing.</span> <span m='1526460'>That's</span> <span m='1526670'>y.</span>
  </p><p><span m='1528710'>Now,</span> <span m='1528950'>what</span> <span m='1529190'>are</span>
  <span m='1529280'>these</span> <span m='1529700'>rounds?</span> <span m='1531200'>They</span>
  <span m='1531380'>are</span> <span m='1531800'>memory</span> <span m='1532250'>reads.</span>
  <span m='1534020'>So</span> <span m='1534980'>what's</span> <span m='1535310'>a?</span>
  </p><p><span m='1537690'>a</span> <span m='1537970'>is</span> <span m='1538030'>a</span>
  <span m='1538880'>log</span> <span m='1539480'>of</span> <span m='1539600'>the</span>
  <span m='1539690'>size</span> <span m='1540110'>of</span> <span m='1540200'>the</span>
  <span m='1540320'>data</span> <span m='1540560'>structure,</span> <span m='1542240'>because</span>
  <span m='1542420'>that's</span> <span m='1542660'>how</span> <span m='1542750'>many</span>
  <span m='1542960'>bits</span> <span m='1543170'>you</span> <span m='1543290'>need</span>
  <span m='1543530'>in</span> <span m='1543650'>order</span> <span m='1543830'>to</span>
  <span m='1543950'>specify</span> <span m='1544640'>which</span> <span m='1544850'>word</span>
  <span m='1545090'>you</span> <span m='1545180'>want</span> <span m='1545360'>to</span>
  <span m='1545420'>read.</span> <span m='1546910'>So</span> <span m='1546950'>if</span>
  <span m='1547070'>you</span> <span m='1547190'>have,</span> <span m='1548090'>let's</span>
  <span m='1548210'>say,</span> <span m='1548420'>s</span> <span m='1548750'>words</span>
  <span m='1549320'>of</span> <span m='1549410'>space,</span> <span m='1550610'>a</span>
  <span m='1551120'>is</span> <span m='1551270'>going</span> <span m='1551480'>to</span>
  <span m='1551570'>be</span> <span m='1552200'>log</span> <span m='1553330'>s.</span>
  <span m='1556840'>OK,</span> <span m='1557140'>you</span> <span m='1557230'>could</span>
  <span m='1557380'>make</span> <span m='1557590'>it</span> <span m='1557680'>larger.</span>
  <span m='1558080'>But</span> <span m='1558220'>it</span> <span m='1558310'>doesn't</span>
  <span m='1558550'>help</span> <span m='1558820'>you.</span> </p><p><span m='1559000'>So</span>
  <span m='1559180'>we're</span> <span m='1559240'>going</span> <span m='1559360'>to</span>
  <span m='1559420'>make</span> <span m='1559570'>it</span> <span m='1559660'>as</span>
  <span m='1559720'>small</span> <span m='1559990'>as</span> <span m='1560080'>possible,</span>
  <span m='1560620'>because</span> <span m='1560800'>that</span> <span m='1560920'>will</span>
  <span m='1561010'>let</span> <span m='1561160'>us</span> <span m='1561250'>prove</span>
  <span m='1561490'>things.</span> <span m='1563080'>It's</span> <span m='1563890'>fine</span>
  <span m='1564250'>to</span> <span m='1564460'>let</span> <span m='1564640'>a</span>
  <span m='1564850'>be</span> <span m='1564970'>log</span> <span m='1565210'>s,</span>
  <span m='1565360'>because</span> <span m='1566350'>Bob</span> <span m='1566680'>is</span>
  <span m='1566800'>not</span> <span m='1566980'>very</span> <span m='1567160'>intelligent.</span>
  <span m='1568350'>Bob,</span> <span m='1569050'>you</span> <span m='1569140'>just</span>
  <span m='1569320'>say,</span> <span m='1569830'>look,</span> <span m='1570190'>I</span>
  <span m='1570400'>would</span> <span m='1570550'>like</span> <span m='1570940'>word</span>
  <span m='1571270'>five</span> <span m='1571660'>please.</span> <span m='1571960'>And
  it</span> <span m='1572050'>says,</span> <span m='1572450'>here's</span> <span m='1572560'>word</span>
  <span m='1572740'>five.</span> </p><p><span m='1573580'>So</span> <span m='1573730'>it's</span>
  <span m='1573820'>not</span> <span m='1573970'>doing</span> <span m='1574180'>any</span>
  <span m='1574300'>computation.</span> <span m='1574960'>Alice</span> <span m='1575290'>can</span>
  <span m='1575440'>do</span> <span m='1575560'>lots</span> <span m='1575740'>of</span>
  <span m='1575830'>computation</span> <span m='1576295'>and</span> <span m='1576760'>whatnot.</span>
  <span m='1577140'>In</span> <span m='1577210'>fact,</span> <span m='1577970'>free</span>
  <span m='1578110'>computation,</span> <span m='1578740'>we</span> <span m='1578830'>don't</span>
  <span m='1578980'>count</span> <span m='1579220'>that.</span> </p><p><span m='1580390'>The</span>
  <span m='1580510'>question</span> <span m='1580900'>is</span> <span m='1580960'>just,</span>
  <span m='1581140'>how</span> <span m='1581320'>many</span> <span m='1581560'>things</span>
  <span m='1581800'>do</span> <span m='1581860'>you</span> <span m='1581920'>have</span>
  <span m='1582010'>to</span> <span m='1582130'>read</span> <span m='1582280'>from</span>
  <span m='1582430'>Bob?</span> <span m='1582760'>Now,</span> <span m='1582940'>in</span>
  <span m='1583000'>this</span> <span m='1583150'>picture,</span> <span m='1583480'>Bob</span>
  <span m='1583780'>could</span> <span m='1583960'>potentially</span> <span m='1584500'>compute</span>
  <span m='1584830'>stuff.</span> <span m='1585670'>But</span> <span m='1585850'>we</span>
  <span m='1586030'>know,</span> <span m='1586450'>in</span> <span m='1586630'>reality,</span>
  <span m='1587170'>it</span> <span m='1587230'>won't.</span> <span m='1589030'>Lower</span>
  <span m='1589300'>bounds</span> <span m='1589540'>aren't</span> <span m='1589600'>going</span>
  <span m='1589750'>to</span> <span m='1589810'>use</span> <span m='1589960'>that</span>
  <span m='1590140'>fact.</span> <span m='1590590'>But</span> <span m='1591190'>that's</span>
  <span m='1591370'>why</span> <span m='1591580'>we</span> <span m='1591730'>can</span>
  <span m='1591880'>set</span> <span m='1592150'>a</span> <span m='1592360'>to</span>
  <span m='1592480'>just</span> <span m='1592660'>be</span> <span m='1592780'>log</span>
  <span m='1593050'>s, because</span> <span m='1593440'>Bob</span> <span m='1593740'>wouldn't</span>
  <span m='1593980'>do</span> <span m='1594160'>anything</span> <span m='1594610'>with</span>
  <span m='1594820'>the</span> <span m='1594940'>extra</span> <span m='1595180'>information.</span>
  </p><p><span m='1597480'>How</span> <span m='1597720'>big</span> <span m='1597860'>is</span>
  <span m='1598000'>b?</span> <span m='1598350'>b</span> <span m='1598720'>is</span>
  <span m='1598930'>just</span> <span m='1599200'>w,</span> <span m='1600310'>because</span>
  <span m='1600910'>the</span> <span m='1601030'>response</span> <span m='1601600'>to</span>
  <span m='1602590'>a</span> <span m='1602710'>word</span> <span m='1602950'>read</span>
  <span m='1603160'>is</span> <span m='1603310'>a</span> <span m='1603430'>word.</span>
  <span m='1604840'>So</span> <span m='1604990'>this</span> <span m='1605170'>is</span>
  <span m='1605230'>the</span> <span m='1605320'>picture.</span> <span m='1606560'>Query</span>
  <span m='1607960'>can</span> <span m='1608920'>probe</span> <span m='1609700'>the</span>
  <span m='1609790'>data</span> <span m='1610030'>structure.</span> </p><p><span m='1610900'>It</span>
  <span m='1611170'>says,</span> <span m='1611380'>give</span> <span m='1611590'>me</span>
  <span m='1611740'>word</span> <span m='1613150'>something,</span> <span m='1613870'>which</span>
  <span m='1614050'>is</span> <span m='1614150'>only</span> <span m='1614350'>log</span>
  <span m='1614730'>s</span> <span m='1615130'>bits.</span> <span m='1615700'>The</span>
  <span m='1615820'>response</span> <span m='1616390'>is</span> <span m='1617200'>w</span>
  <span m='1617500'>bits.</span> <span m='1618250'>And</span> <span m='1618430'>you</span>
  <span m='1618910'>repeat</span> <span m='1619300'>this</span> <span m='1619450'>process</span>
  <span m='1620020'>over</span> <span m='1620260'>and</span> <span m='1620350'>over.</span>
  <span m='1621310'>And</span> <span m='1621460'>then,</span> <span m='1621730'>somehow,</span>
  <span m='1622390'>Alice</span> <span m='1622840'>has</span> <span m='1623020'>to</span>
  <span m='1623140'>compute</span> <span m='1623470'>f</span> <span m='1623670'>of</span>
  <span m='1624113'>xy.</span> </p><p><span m='1625000'>In</span> <span m='1625090'>this</span>
  <span m='1625210'>model,</span> <span m='1625990'>Bob</span> <span m='1626260'>doesn't</span>
  <span m='1626500'>need</span> <span m='1626620'>to</span> <span m='1626710'>know</span>
  <span m='1626860'>the</span> <span m='1626950'>answer.</span> <span m='1627410'>Of</span>
  <span m='1627430'>course,</span> <span m='1627670'>it's</span> <span m='1627760'>just</span>
  <span m='1627940'>a</span> <span m='1628000'>single</span> <span m='1628390'>bit.</span>
  <span m='1628570'>What</span> <span m='1628720'>is</span> <span m='1628840'>f</span>
  <span m='1628990'>of</span> <span m='1629110'>xy?</span> <span m='1629950'>This</span>
  <span m='1630160'>is</span> <span m='1630370'>colored</span> <span m='1630700'>predecessor.</span>
  </p><p><span m='1638890'>x</span> <span m='1639190'>is</span> <span m='1639370'>the</span>
  <span m='1639460'>query.</span> <span m='1640210'>y</span> <span m='1640450'>is</span>
  <span m='1640600'>the</span> <span m='1640690'>data</span> <span m='1640900'>structure.</span>
  <span m='1641910'>And</span> <span m='1642040'>f</span> <span m='1642190'>of</span>
  <span m='1642310'>xy,</span> <span m='1643190'>is</span> <span m='1643540'>it</span>
  <span m='1643630'>red</span> <span m='1643840'>or</span> <span m='1643930'>blue?</span>
  <span m='1644590'>Is</span> <span m='1644770'>the</span> <span m='1644890'>predecessor</span>
  <span m='1645490'>of</span> <span m='1645580'>x</span> <span m='1646180'>in</span>
  <span m='1646330'>this</span> <span m='1646450'>data</span> <span m='1646690'>structure</span>
  <span m='1647080'>in</span> <span m='1647170'>the</span> <span m='1647260'>set</span>
  <span m='1647470'>represented</span> <span m='1647920'>by</span> <span m='1648040'>this</span>
  <span m='1648190'>data</span> <span m='1648370'>structure</span> <span m='1648700'>red</span>
  <span m='1648880'>or</span> <span m='1648970'>blue?</span> </p><p><span m='1649180'>So</span>
  <span m='1649680'>it's</span> <span m='1649840'>one</span> <span m='1650050'>bit</span>
  <span m='1650170'>of</span> <span m='1650290'>information.</span> <span m='1651590'>Alice</span>
  <span m='1651920'>could</span> <span m='1652090'>then</span> <span m='1652510'>tell</span>
  <span m='1652720'>the</span> <span m='1653170'>bit</span> <span m='1653440'>to Bob.</span>
  <span m='1653740'>But</span> <span m='1653890'>actually,</span> <span m='1654160'>in</span>
  <span m='1654220'>this</span> <span m='1654370'>model,</span> <span m='1654700'>we</span>
  <span m='1654820'>just</span> <span m='1655480'>want</span> <span m='1655720'>Alice</span>
  <span m='1656080'>to</span> <span m='1656200'>know</span> <span m='1656320'>the</span>
  <span m='1656440'>answer.</span> </p><p><span m='1658900'>So</span> <span m='1659110'>if</span>
  <span m='1659230'>you</span> <span m='1659350'>can</span> <span m='1659470'>prove</span>
  <span m='1659680'>a</span> <span m='1659710'>lower</span> <span m='1659980'>bound</span>
  <span m='1660160'>on</span> <span m='1660280'>how</span> <span m='1660430'>many</span>
  <span m='1660640'>rounds</span> <span m='1661000'>of</span> <span m='1661090'>communication</span>
  <span m='1662080'>you</span> <span m='1662260'>need,</span> <span m='1663790'>then</span>
  <span m='1664030'>you</span> <span m='1664120'>prove</span> <span m='1664360'>a</span>
  <span m='1664390'>lower</span> <span m='1664600'>bound</span> <span m='1664960'>on</span>
  <span m='1665140'>the</span> <span m='1665230'>number</span> <span m='1665470'>of</span>
  <span m='1665560'>memory</span> <span m='1665890'>reads.</span> <span m='1670090'>Each</span>
  <span m='1670300'>round</span> <span m='1670750'>corresponds</span> <span m='1671290'>to</span>
  <span m='1671440'>one</span> <span m='1672010'>word</span> <span m='1672520'>read</span>
  <span m='1672850'>from</span> <span m='1673120'>memory.</span> <span m='1675760'>Clear?</span>
  <span m='1676980'>So</span> <span m='1677130'>a</span> <span m='1677160'>very</span>
  <span m='1677340'>simple</span> <span m='1677670'>idea,</span> <span m='1678750'>but</span>
  <span m='1679050'>a</span> <span m='1679410'>powerful</span> <span m='1679920'>one,</span>
  <span m='1680160'>as</span> <span m='1680370'>we</span> <span m='1680550'>will</span>
  <span m='1680700'>see,</span> <span m='1683080'>because</span> <span m='1683280'>it</span>
  <span m='1683400'>lets</span> <span m='1683640'>us</span> <span m='1683760'>talk</span>
  <span m='1684030'>about</span> <span m='1685320'>an</span> <span m='1685470'>idea</span>
  <span m='1685830'>which</span> <span m='1686070'>makes</span> <span m='1686310'>sense</span>
  <span m='1686940'>when</span> <span m='1687090'>you're</span> <span m='1687210'>thinking</span>
  <span m='1687540'>about</span> <span m='1687870'>protocols</span> <span m='1688350'>of</span>
  <span m='1688830'>rounds</span> <span m='1689280'>of</span> <span m='1689490'>communication,</span>
  <span m='1690690'>but</span> <span m='1690900'>does</span> <span m='1691050'>not</span>
  <span m='1691290'>really</span> <span m='1691530'>make</span> <span m='1691710'>sense</span>
  <span m='1691950'>from</span> <span m='1692130'>a</span> <span m='1692190'>data</span>
  <span m='1692400'>structure</span> <span m='1692790'>perspective--</span> <span
  m='1694110'>well,</span> <span m='1694590'>I</span> <span m='1694650'>mean,</span>
  <span m='1696090'>not</span> <span m='1696240'>as</span> <span m='1696360'>much</span>
  <span m='1696540'>sense.</span> </p><p><span m='1701460'>Round</span> <span m='1701790'>elimination</span>
  <span m='1702450'>is</span> <span m='1702660'>a</span> <span m='1702780'>concept</span>
  <span m='1703320'>that</span> <span m='1703440'>makes</span> <span m='1703680'>sense</span>
  <span m='1707910'>for</span> <span m='1708090'>any</span> <span m='1708330'>communication</span>
  <span m='1709440'>style</span> <span m='1710040'>protocol--</span> <span m='1710970'>not</span>
  <span m='1711150'>just</span> <span m='1711330'>the</span> <span m='1711450'>red</span>
  <span m='1711600'>one,</span> <span m='1712330'>but</span> <span m='1712440'>the</span>
  <span m='1712530'>generic</span> <span m='1712980'>white</span> <span m='1713190'>picture.</span>
  <span m='1717630'>I</span> <span m='1717690'>need</span> <span m='1717840'>to</span>
  <span m='1717960'>define</span> <span m='1718350'>a</span> <span m='1718410'>little</span>
  <span m='1718650'>bit</span> <span m='1718830'>before</span> <span m='1719130'>I</span>
  <span m='1719160'>can</span> <span m='1719340'>get</span> <span m='1719490'>to</span>
  <span m='1719790'>the</span> <span m='1719910'>claim.</span> <span m='1721460'>This</span>
  <span m='1722130'>will</span> <span m='1722250'>seem</span> <span m='1722670'>weird</span>
  <span m='1723120'>and</span> <span m='1723270'>arbitrary</span> <span m='1724500'>for</span>
  <span m='1724680'>a</span> <span m='1724710'>little</span> <span m='1724920'>while,</span>
  <span m='1725400'>until</span> <span m='1725760'>I</span> <span m='1725820'>draw</span>
  <span m='1726060'>the</span> <span m='1726180'>red</span> <span m='1726360'>picture,</span>
  <span m='1726720'>which</span> <span m='1726930'>is</span> <span m='1727050'>what</span>
  <span m='1727200'>it</span> <span m='1727290'>corresponds</span> <span m='1727830'>to</span>
  <span m='1728090'>in</span> <span m='1728190'>the</span> <span m='1728280'>predecessor</span>
  <span m='1728820'>problem.</span> </p><p><span m='1729900'>But</span> <span m='1729990'>just</span>
  <span m='1730380'>bear</span> <span m='1730590'>with</span> <span m='1730740'>me</span>
  <span m='1730890'>for</span> <span m='1731010'>a</span> <span m='1731070'>minute.</span>
  <span m='1731770'>Imagine</span> <span m='1732090'>this</span> <span m='1732270'>weird</span>
  <span m='1733170'>variation</span> <span m='1734040'>on</span> <span m='1734400'>whatever</span>
  <span m='1734760'>problem</span> <span m='1735150'>you're</span> <span m='1735300'>starting</span>
  <span m='1735630'>with.</span> <span m='1741710'>So</span> <span m='1741980'>we</span>
  <span m='1742130'>have</span> <span m='1742250'>some</span> <span m='1742400'>problem</span>
  <span m='1742650'>f,</span> <span m='1742910'>which</span> <span m='1743060'>happens</span>
  <span m='1743360'>to</span> <span m='1743450'>be</span> <span m='1743510'>colored</span>
  <span m='1743750'>predecessor.</span> <span m='1744300'>We're</span> <span m='1744400'>going</span>
  <span m='1744490'>to</span> <span m='1744590'>make</span> <span m='1744770'>a</span>
  <span m='1744830'>new</span> <span m='1745010'>version</span> <span m='1745370'>of</span>
  <span m='1745460'>that</span> <span m='1745610'>problem,</span> <span m='1745940'>called</span>
  <span m='1746360'>f to</span> <span m='1746540'>the</span> <span m='1746630'>k.</span>
  <span m='1748610'>And</span> <span m='1748910'>here</span> <span m='1749210'>is</span>
  <span m='1749360'>the</span> <span m='1749480'>setup.</span> </p><p><span m='1750830'>It's</span>
  <span m='1750950'>going</span> <span m='1751120'>to</span> <span m='1751190'>be</span>
  <span m='1751250'>a</span> <span m='1751280'>little</span> <span m='1751520'>different</span>
  <span m='1751820'>from</span> <span m='1752030'>this,</span> <span m='1753600'>and
  kind</span> <span m='1753830'>of</span> <span m='1753900'>fits</span> <span m='1754100'>the</span>
  <span m='1754160'>same</span> <span m='1754400'>framework.</span> <span m='1754970'>But</span>
  <span m='1755120'>now,</span> <span m='1755870'>Alice</span> <span m='1756170'>has</span>
  <span m='1756380'>k</span> <span m='1756740'>inputs,</span> <span m='1758930'>x1,</span>
  <span m='1760430'>x2,</span> <span m='1762320'>up</span> <span m='1762740'>to</span>
  <span m='1763160'>xk.</span> <span m='1767060'>Bob</span> <span m='1769040'>has</span>
  <span m='1771860'>y,</span> <span m='1772790'>as</span> <span m='1773000'>before.</span>
  <span m='1774320'>And</span> <span m='1775700'>it</span> <span m='1775790'>has</span>
  <span m='1776060'>an</span> <span m='1776150'>integer,</span> <span m='1777580'>i,</span>
  <span m='1779210'>which</span> <span m='1779420'>is</span> <span m='1779570'>between</span>
  <span m='1780110'>1</span> <span m='1781190'>and</span> <span m='1781400'>k.</span>
  </p><p><span m='1784550'>Also,</span> <span m='1787050'>this</span> <span m='1787230'>is</span>
  <span m='1787350'>a</span> <span m='1787410'>technicality</span> <span m='1788280'>because</span>
  <span m='1788480'>we'll</span> <span m='1788610'>need</span> <span m='1788850'>it</span>
  <span m='1788970'>for</span> <span m='1789270'>colored</span> <span m='1789540'>predecessor--</span>
  <span m='1791320'>we</span> <span m='1791420'>won't</span> <span m='1791580'>see</span>
  <span m='1791730'>that</span> <span m='1791940'>for</span> <span m='1792390'>a</span>
  <span m='1792420'>few</span> <span m='1792570'>minutes.</span> <span m='1793280'>But</span>
  <span m='1794880'>Bob</span> <span m='1795240'>happens</span> <span m='1795630'>to</span>
  <span m='1795750'>know</span> <span m='1797160'>all</span> <span m='1797370'>the</span>
  <span m='1797520'>xi's</span> <span m='1799350'>up</span> <span m='1799560'>to</span>
  <span m='1799860'>xi</span> <span m='1800190'>minus</span> <span m='1800520'>1.</span>
  <span m='1803630'>And the</span> <span m='1803750'>goal</span> <span m='1806570'>is</span>
  <span m='1806780'>to</span> <span m='1806900'>compute</span> <span m='1810200'>f</span>
  <span m='1811250'>of</span> <span m='1811510'>x</span> <span m='1811970'>i,</span>
  <span m='1813260'>y.</span> <span m='1816930'>Maybe</span> <span m='1817200'>I</span>
  <span m='1817290'>should</span> <span m='1818860'>draw</span> <span m='1819170'>a</span>
  <span m='1819210'>picture</span> <span m='1819690'>of</span> <span m='1820580'>this.</span>
  </p><p><span m='1840780'>So</span> <span m='1840930'>we have</span> <span m='1841240'>Alice.</span>
  <span m='1842530'>Alice</span> <span m='1842920'>has</span> <span m='1845920'>x1</span>
  <span m='1849190'>up</span> <span m='1849670'>to</span> <span m='1851155'>xk.</span>
  <span m='1853150'>Bob</span> <span m='1854530'>has</span> <span m='1855010'>y</span>
  <span m='1856240'>and</span> <span m='1856510'>i,</span> <span m='1859410'>same</span>
  <span m='1859830'>communication</span> <span m='1860400'>setup.</span> <span m='1861400'>And</span>
  <span m='1861490'>the</span> <span m='1861580'>goal</span> <span m='1863250'>is</span>
  <span m='1863320'>to</span> <span m='1863440'>compute</span> <span m='1863920'>f</span>
  <span m='1864240'>of</span> <span m='1864400'>xi,</span> <span m='1865240'>y.</span>
  <span m='1867640'>Before</span> <span m='1868030'>it</span> <span m='1868090'>was</span>
  <span m='1868270'>x,</span> <span m='1868780'>y.</span> <span m='1869950'>And</span>
  <span m='1870040'>now,</span> <span m='1870190'>we're</span> <span m='1870280'>saying,</span>
  <span m='1870620'>well,</span> <span m='1870800'>actually,</span> <span m='1871360'>x</span>
  <span m='1871630'>consists</span> <span m='1872050'>of</span> <span m='1872140'>these</span>
  <span m='1872320'>k</span> <span m='1872560'>parts.</span> <span m='1873400'>We</span>
  <span m='1873550'>really</span> <span m='1873880'>just</span> <span m='1874060'>care</span>
  <span m='1874270'>about</span> <span m='1874480'>the i-th</span> <span m='1874770'>part.</span>
  </p><p><span m='1875380'>So</span> <span m='1875530'>this</span> <span m='1875710'>function</span>
  <span m='1876100'>does</span> <span m='1876220'>not</span> <span m='1876400'>depend</span>
  <span m='1876760'>on</span> <span m='1876880'>any</span> <span m='1877210'>other</span>
  <span m='1877900'>of</span> <span m='1878080'>the</span> <span m='1878230'>xj's,</span>
  <span m='1878890'>just</span> <span m='1879190'>xi.</span> <span m='1880570'>So</span>
  <span m='1880720'>naturally,</span> <span m='1881170'>Alice</span> <span m='1881470'>should</span>
  <span m='1881650'>just</span> <span m='1882460'>communicate</span> <span m='1882940'>to</span>
  <span m='1883030'>Bob</span> <span m='1883300'>about</span> <span m='1883600'>xi.</span>
  <span m='1884440'>Trouble</span> <span m='1884770'>is,</span> <span m='1885010'>Alice</span>
  <span m='1885310'>doesn't</span> <span m='1885550'>know</span> <span m='1885670'>what</span>
  <span m='1885820'>i</span> <span m='1886030'>is.</span> <span m='1886720'>Only</span>
  <span m='1886960'>Bob</span> <span m='1887230'>knows</span> <span m='1887470'>what</span>
  <span m='1887620'>i</span> <span m='1887770'>is.</span> <span m='1889420'>So</span>
  <span m='1889540'>if</span> <span m='1889600'>you</span> <span m='1889720'>think</span>
  <span m='1889900'>about</span> <span m='1890430'>a</span> <span m='1890530'>communication</span>
  <span m='1891130'>protocol,</span> <span m='1891630'>where</span> <span m='1891910'>initially</span>
  <span m='1892390'>Alice sends</span> <span m='1892870'>a</span> <span m='1892900'>message,</span>
  <span m='1893290'>then</span> <span m='1893440'>Bob</span> <span m='1893680'>responds,</span>
  <span m='1895060'>that</span> <span m='1895270'>first</span> <span m='1895600'>message</span>
  <span m='1895990'>that</span> <span m='1896140'>Alice</span> <span m='1896380'>sends</span>
  <span m='1897430'>is</span> <span m='1897610'>probably</span> <span m='1898300'>useless.</span>
  </p><p><span m='1900950'>I</span> <span m='1901050'>mean,</span> <span m='1901150'>probably</span>
  <span m='1901510'>the</span> <span m='1901630'>first</span> <span m='1901840'>question</span>
  <span m='1902200'>is,</span> <span m='1902370'>what's</span> <span m='1902720'>i?</span>
  <span m='1903340'>That</span> <span m='1903520'>has</span> <span m='1903670'>no</span>
  <span m='1903880'>information.</span> <span m='1904610'>It's</span> <span m='1904710'>just</span>
  <span m='1904960'>every</span> <span m='1905230'>time</span> <span m='1905630'>in</span>
  <span m='1905740'>the</span> <span m='1905830'>beginning,</span> <span m='1906110'>you</span>
  <span m='1906200'>say,</span> <span m='1906390'>what's</span> <span m='1906580'>i?</span>
  <span m='1907180'>Then</span> <span m='1907330'>Bob</span> <span m='1907570'>says,</span>
  <span m='1907810'>here's</span> <span m='1908080'>i.</span> <span m='1909490'>And</span>
  <span m='1909580'>then</span> <span m='1909760'>after</span> <span m='1910060'>that</span>
  <span m='1910240'>one</span> <span m='1910420'>round,</span> <span m='1911230'>Alice</span>
  <span m='1911560'>can</span> <span m='1912450'>you</span> <span m='1912640'>just</span>
  <span m='1913570'>think</span> <span m='1913780'>about</span> <span m='1914620'>xi,</span>
  <span m='1915250'>from</span> <span m='1915430'>then</span> <span m='1915580'>on.</span>
  </p><p><span m='1918310'>OK,</span> <span m='1920870'>one</span> <span m='1921110'>message</span>
  <span m='1921470'>may</span> <span m='1921620'>seem</span> <span m='1921830'>like</span>
  <span m='1922160'>nothing.</span> <span m='1923060'>But</span> <span m='1924968'>it's</span>
  <span m='1925370'>like</span> <span m='1926450'>every</span> <span m='1926660'>time</span>
  <span m='1926900'>you</span> <span m='1927020'>put</span> <span m='1927170'>a</span>
  <span m='1927230'>penny</span> <span m='1927470'>in</span> <span m='1927530'>the</span>
  <span m='1927620'>jar.</span> <span m='1927890'>After</span> <span m='1928070'>you</span>
  <span m='1928310'>do</span> <span m='1928490'>that</span> <span m='1928670'>enough</span>
  <span m='1928910'>times,</span> <span m='1929910'>you</span> <span m='1929990'>have</span>
  <span m='1930110'>a</span> <span m='1930170'>lot</span> <span m='1930320'>of</span>
  <span m='1930380'>money.</span> </p><p><span m='1931740'>So</span> <span m='1932240'>one</span>
  <span m='1932510'>message</span> <span m='1932840'>may</span> <span m='1932990'>seem</span>
  <span m='1933230'>like</span> <span m='1933410'>very</span> <span m='1933620'>few.</span>
  <span m='1934250'>But</span> <span m='1934400'>we</span> <span m='1934550'>just</span>
  <span m='1934730'>need</span> <span m='1934940'>to</span> <span m='1935090'>prove</span>
  <span m='1935480'>a</span> <span m='1935540'>lower</span> <span m='1935810'>bound</span>
  <span m='1936110'>of</span> <span m='1936620'>log</span> <span m='1936910'>w</span>
  <span m='1937150'>over</span> <span m='1937320'>log</span> <span m='1937550'>log</span>
  <span m='1937700'>w</span> <span m='1938030'>messages.</span> <span m='1938610'>So</span>
  <span m='1939170'>you</span> <span m='1939260'>do</span> <span m='1939410'>this</span>
  <span m='1939650'>a</span> <span m='1939710'>few</span> <span m='1939890'>times.</span>
  <span m='1941690'>Eventually,</span> <span m='1942110'>you'll</span> <span m='1942230'>get</span>
  <span m='1942380'>rid</span> <span m='1942500'>of</span> <span m='1942590'>all</span>
  <span m='1942770'>the</span> <span m='1942860'>messages.</span> </p><p><span m='1944140'>Now,</span>
  <span m='1944290'>if we can</span> <span m='1944540'>get</span> <span m='1944750'>rid</span>
  <span m='1944930'>of</span> <span m='1945470'>all</span> <span m='1945710'>the</span>
  <span m='1945830'>messages,</span> <span m='1946780'>it</span> <span m='1947040'>may</span>
  <span m='1947240'>seem</span> <span m='1947450'>crazy.</span> <span m='1947960'>But</span>
  <span m='1948170'>it</span> <span m='1948230'>turns</span> <span m='1948440'>out</span>
  <span m='1948530'>you</span> <span m='1948620'>can</span> <span m='1948740'>iterate</span>
  <span m='1949040'>this</span> <span m='1949160'>process</span> <span m='1949730'>of</span>
  <span m='1950570'>eliminating</span> <span m='1951710'>that</span> <span m='1951890'>first</span>
  <span m='1952130'>message.</span> <span m='1952820'>If we</span> <span m='1953010'>get</span>
  <span m='1953150'>rid</span> <span m='1953270'>of</span> <span m='1953360'>all</span>
  <span m='1953660'>the</span> <span m='1953780'>messages,</span> <span m='1954890'>the</span>
  <span m='1955010'>best</span> <span m='1955370'>we</span> <span m='1955490'>could</span>
  <span m='1955610'>hope</span> <span m='1955790'>for</span> <span m='1956060'>is</span>
  <span m='1956180'>an</span> <span m='1956270'>algorithm</span> <span m='1956780'>that</span>
  <span m='1957200'>is</span> <span m='1957500'>correct</span> <span m='1957890'>with</span>
  <span m='1958070'>50%</span> <span m='1958670'>probability.</span> </p><p><span
  m='1959790'>If</span> <span m='1959960'>Alice</span> <span m='1960260'>can</span>
  <span m='1960440'>do</span> <span m='1960560'>nothing,</span> <span m='1962300'>then</span>
  <span m='1962680'>the</span> <span m='1962760'>best</span> <span m='1963050'>Alice</span>
  <span m='1963260'>could</span> <span m='1963390'>do is</span> <span m='1963530'>flip</span>
  <span m='1963710'>a</span> <span m='1963770'>coin.</span> <span m='1965040'>So</span>
  <span m='1965570'>we</span> <span m='1965750'>will</span> <span m='1965840'>get</span>
  <span m='1965960'>a</span> <span m='1966020'>contradiction</span> <span m='1966740'>if</span>
  <span m='1966860'>we</span> <span m='1966950'>get</span> <span m='1967100'>a</span>
  <span m='1967190'>zero</span> <span m='1967640'>message</span> <span m='1967970'>protocol</span>
  <span m='1968480'>that</span> <span m='1968660'>wins</span> <span m='1969530'>with</span>
  <span m='1969800'>more</span> <span m='1970130'>than</span> <span m='1970310'>50%</span>
  <span m='1970880'>probability.</span> <span m='1972290'>That's</span> <span m='1972470'>what</span>
  <span m='1972540'>we're</span> <span m='1972650'>going</span> <span m='1972740'>to</span>
  <span m='1972820'>try</span> <span m='1972980'>to</span> <span m='1973070'>do.</span>
  </p><p><span m='1975200'>But</span> <span m='1975350'>what</span> <span m='1975470'>does</span>
  <span m='1975620'>it</span> <span m='1975710'>mean</span> <span m='1975980'>to</span>
  <span m='1976190'>eliminate</span> <span m='1976790'>this</span> <span m='1977030'>first</span>
  <span m='1977360'>message?</span> <span m='1979370'>Let</span> <span m='1979520'>me</span>
  <span m='1979760'>formalize</span> <span m='1980390'>the</span> <span m='1980510'>round</span>
  <span m='1980750'>elimination</span> <span m='1981450'>a</span> <span m='1981530'>little</span>
  <span m='1981770'>bit</span> <span m='1989440'>over</span> <span m='1989770'>here.</span>
  <span m='2008950'>So</span> <span m='2028070'>here's</span> <span m='2028280'>the</span>
  <span m='2028400'>round</span> <span m='2028670'>elimination.</span> <span m='2030930'>This,</span>
  <span m='2031380'>again,</span> <span m='2031670'>works</span> <span m='2031910'>for</span>
  <span m='2032060'>any</span> <span m='2032270'>function</span> <span m='2032690'>f.</span>
  </p><p><span m='2043820'>So</span> <span m='2044000'>if</span> <span m='2044240'>there's</span>
  <span m='2044390'>a</span> <span m='2044450'>protocol</span> <span m='2045770'>for</span>
  <span m='2045890'>this</span> <span m='2046190'>f to</span> <span m='2046460'>the</span>
  <span m='2046580'>k</span> <span m='2046820'>problem,</span> <span m='2047840'>and</span>
  <span m='2048020'>Alice</span> <span m='2048380'>speaks</span> <span m='2048739'>first,</span>
  <span m='2050000'>then</span> <span m='2050210'>that</span> <span m='2050420'>first</span>
  <span m='2050690'>message</span> <span m='2051110'>is</span> <span m='2051230'>going</span>
  <span m='2051469'>to</span> <span m='2051620'>be</span> <span m='2052310'>roughly</span>
  <span m='2052670'>useless.</span> <span m='2057650'>So</span> <span m='2057830'>let's</span>
  <span m='2058040'>suppose</span> <span m='2059270'>it</span> <span m='2059389'>has</span>
  <span m='2059719'>error</span> <span m='2060020'>probability</span> <span m='2064409'>delta.</span>
  <span m='2065400'>So</span> <span m='2065480'>there's</span> <span m='2065540'>some</span>
  <span m='2065750'>probability</span> <span m='2066440'>it</span> <span m='2066560'>gives</span>
  <span m='2066770'>the</span> <span m='2066860'>wrong</span> <span m='2067100'>answer.</span>
  </p><p><span m='2070030'>And</span> <span m='2070270'>let's</span> <span m='2070420'>suppose</span>
  <span m='2071969'>that</span> <span m='2072130'>it</span> <span m='2072250'>uses</span>
  <span m='2073270'>m</span> <span m='2074409'>messages.</span> <span m='2078909'>Then</span>
  <span m='2081850'>there</span> <span m='2082030'>exists</span> <span m='2082330'>a</span>
  <span m='2082389'>protocol</span> <span m='2086620'>for</span> <span m='2086920'>f</span>
  <span m='2089650'>where</span> <span m='2089860'>Bob</span> <span m='2090250'>speaks</span>
  <span m='2090580'>first,</span> <span m='2101260'>the</span> <span m='2101410'>error</span>
  <span m='2101660'>probability</span> <span m='2102260'>goes</span> <span m='2102500'>up</span>
  <span m='2102740'>slightly.</span> <span m='2120020'>And</span> <span m='2120350'>it</span>
  <span m='2120440'>uses</span> <span m='2120890'>one</span> <span m='2121130'>fewer</span>
  <span m='2121400'>message.</span> </p><p><span m='2126890'>OK,</span> <span m='2127430'>ultimately,</span>
  <span m='2127880'>we</span> <span m='2127970'>care</span> <span m='2128120'>about</span>
  <span m='2128330'>rounds,</span> <span m='2128810'>which</span> <span m='2128990'>are</span>
  <span m='2129080'>pairs</span> <span m='2129410'>of</span> <span m='2129470'>messages.</span>
  <span m='2130220'>But</span> <span m='2132590'>we're</span> <span m='2132770'>going</span>
  <span m='2132890'>to</span> <span m='2133610'>count</span> <span m='2133880'>messages.</span>
  <span m='2134390'>And</span> <span m='2134480'>then,</span> <span m='2134600'>of</span>
  <span m='2134660'>course,</span> <span m='2134870'>divide</span> <span m='2135110'>by</span>
  <span m='2135260'>two, you</span> <span m='2135590'>get</span> <span m='2135740'>rounds.</span>
  <span m='2136940'>So</span> <span m='2137240'>the</span> <span m='2137420'>idea</span>
  <span m='2137630'>is</span> <span m='2137750'>you</span> <span m='2137840'>can</span>
  <span m='2138110'>eliminate</span> <span m='2138620'>the</span> <span m='2138770'>first</span>
  <span m='2139070'>message</span> <span m='2139430'>that</span> <span m='2139580'>Alice</span>
  <span m='2139850'>sent.</span> </p><p><span m='2141440'>The</span> <span m='2141560'>difference</span>
  <span m='2141860'>is,</span> <span m='2142160'>before</span> <span m='2142610'>you</span>
  <span m='2142740'>were</span> <span m='2142850'>solving</span> <span m='2143870'>this</span>
  <span m='2144080'>f to the</span> <span m='2144395'>k</span> <span m='2144710'>problem.</span>
  <span m='2146550'>If</span> <span m='2146600'>you</span> <span m='2146660'>start</span>
  <span m='2146900'>with</span> <span m='2147050'>Bob,</span> <span m='2147410'>then</span>
  <span m='2147560'>of</span> <span m='2147650'>course</span> <span m='2147860'>you</span>
  <span m='2147980'>know</span> <span m='2148160'>what</span> <span m='2148310'>i</span>
  <span m='2148550'>is.</span> <span m='2148790'>And</span> <span m='2148880'>so</span>
  <span m='2149030'>then</span> <span m='2149180'>your</span> <span m='2149300'>problem</span>
  <span m='2149600'>just</span> <span m='2149780'>reduces</span> <span m='2150230'>to</span>
  <span m='2150380'>computing</span> <span m='2150740'>this</span> <span m='2150950'>f</span>
  <span m='2151970'>on</span> <span m='2152180'>xi,</span> <span m='2152645'>y.</span>
  <span m='2153800'>So</span> <span m='2153950'>you</span> <span m='2154010'>don't</span>
  <span m='2154220'>get</span> <span m='2154340'>a</span> <span m='2154400'>protocol</span>
  <span m='2154790'>for</span> <span m='2154940'>f to the</span> <span m='2155180'>k</span>
  <span m='2155510'>anymore.</span> <span m='2156170'>But</span> <span m='2156400'>you</span>
  <span m='2156490'>get</span> <span m='2156620'>a</span> <span m='2156650'>protocol</span>
  <span m='2157070'>for</span> <span m='2157270'>f.</span> </p><p><span m='2160510'>And</span>
  <span m='2160700'>we're</span> <span m='2160820'>going</span> <span m='2160940'>to</span>
  <span m='2161000'>iterate</span> <span m='2161330'>this</span> <span m='2161480'>process,</span>
  <span m='2162140'>and</span> <span m='2162230'>eventually</span> <span m='2162620'>eliminate</span>
  <span m='2163040'>all</span> <span m='2163220'>the</span> <span m='2163310'>messages.</span>
  <span m='2164250'>That's</span> <span m='2164330'>the</span> <span m='2164420'>plan.</span>
  <span m='2166940'>Let</span> <span m='2167150'>me</span> <span m='2167270'>give</span>
  <span m='2167480'>you</span> <span m='2168200'>some</span> <span m='2168410'>intuition</span>
  <span m='2168950'>for</span> <span m='2169130'>why</span> <span m='2169310'>this</span>
  <span m='2170000'>dilemma</span> <span m='2170270'>is</span> <span m='2170420'>true.</span>
  </p><p><span m='2172710'>It's</span> <span m='2173510'>a</span> <span m='2173570'>little</span>
  <span m='2173900'>messy</span> <span m='2174230'>for</span> <span m='2174380'>us</span>
  <span m='2174590'>to</span> <span m='2174710'>prove.</span> <span m='2175190'>I'm</span>
  <span m='2175280'>not</span> <span m='2175430'>going</span> <span m='2175580'>to</span>
  <span m='2175640'>give</span> <span m='2175790'>a</span> <span m='2175850'>proof</span>
  <span m='2176570'>here.</span> <span m='2178280'>If</span> <span m='2178430'>there's</span>
  <span m='2178580'>time</span> <span m='2178790'>at</span> <span m='2178880'>the</span>
  <span m='2178970'>end,</span> <span m='2179120'>I'll</span> <span m='2179210'>give</span>
  <span m='2179390'>a</span> <span m='2179450'>little</span> <span m='2179690'>bit</span>
  <span m='2179840'>more</span> <span m='2180080'>of</span> <span m='2180170'>a</span>
  <span m='2180230'>proof.</span> <span m='2180560'>But</span> <span m='2180770'>it</span>
  <span m='2180860'>will</span> <span m='2180980'>still</span> <span m='2181460'>use</span>
  <span m='2182810'>some</span> <span m='2183380'>information</span> <span m='2183920'>theory</span>
  <span m='2184220'>that</span> <span m='2184430'>we</span> <span m='2184580'>will</span>
  <span m='2184700'>not</span> <span m='2184880'>prove,</span> <span m='2188120'>and</span>
  <span m='2188270'>some</span> <span m='2188450'>communication</span> <span m='2189020'>complexity</span>
  <span m='2189410'>which</span> <span m='2189590'>we</span> <span m='2189710'>won't</span>
  <span m='2189890'>prove,</span> <span m='2190640'>because</span> <span m='2190820'>it's</span>
  <span m='2190940'>a</span> <span m='2191000'>little</span> <span m='2191240'>bit</span>
  <span m='2191330'>involved</span> <span m='2191630'>to</span> <span m='2191720'>prove</span>
  <span m='2191990'>this.</span> </p><p><span m='2192170'>But</span> <span m='2192290'>once</span>
  <span m='2192560'>you</span> <span m='2192680'>have</span> <span m='2192920'>this</span>
  <span m='2193070'>lemma,</span> <span m='2194210'>this</span> <span m='2194420'>lower</span>
  <span m='2194690'>bound</span> <span m='2194930'>is</span> <span m='2195050'>actually</span>
  <span m='2195410'>quite</span> <span m='2195650'>easy,</span> <span m='2196010'>and</span>
  <span m='2196130'>intuitive,</span> <span m='2196610'>and</span> <span m='2196700'>nice.</span>
  <span m='2198410'>So</span> <span m='2198680'>that's</span> <span m='2199910'>where</span>
  <span m='2200180'>I</span> <span m='2200240'>want</span> <span m='2200420'>to</span>
  <span m='2200540'>get</span> <span m='2200810'>to</span> <span m='2201020'>today.</span>
  <span m='2202350'>But</span> <span m='2202370'>let's</span> <span m='2202520'>start</span>
  <span m='2202670'>with</span> <span m='2202760'>some</span> <span m='2202910'>intuition</span>
  <span m='2203380'>of</span> <span m='2203430'>why</span> <span m='2203630'>this</span>
  <span m='2203810'>should</span> <span m='2204020'>be</span> <span m='2204140'>true,</span>
  <span m='2207770'>why</span> <span m='2208470'>there's</span> <span m='2208670'>this</span>
  <span m='2208820'>extra</span> <span m='2209180'>error</span> <span m='2210100'>term.</span>
  <span m='2211490'>Yeah,</span> <span m='2211780'>question?</span> </p><p></p><p><span
  m='2214100'>AUDIENCE:</span> <span m='2214347'>Does</span> <span m='2214595'>it
  matter</span> <span m='2215090'>who</span> <span m='2215585'>reports</span> <span
  m='2216080'>the</span> <span m='2216567'>answer?</span> <span m='2217541'>Because</span>
  <span m='2218030'>there</span> <span m='2218481'>seems</span> <span m='2218932'>to</span>
  <span m='2219383'>be</span> <span m='2219834'>some</span> <span m='2220285'>symmetry</span>
  <span m='2220736'>there.</span> </p><p><span m='2221640'>ERIK DEMAINE:</span> <span
  m='2221795'>Right,</span> <span m='2222220'>does</span> <span m='2222440'>it</span>
  <span m='2222500'>matter</span> <span m='2222800'>who</span> <span m='2223010'>has</span>
  <span m='2223250'>the</span> <span m='2223400'>answer,</span> <span m='2223820'>Alice</span>
  <span m='2224150'>or</span> <span m='2224240'>Bob?</span> <span m='2225230'>Let's</span>
  <span m='2225500'>just</span> <span m='2225650'>say</span> <span m='2226460'>you're</span>
  <span m='2226640'>done</span> <span m='2227030'>when</span> <span m='2227420'>anyone</span>
  <span m='2227870'>knows</span> <span m='2228110'>the</span> <span m='2228230'>answer,</span>
  <span m='2228770'>either</span> <span m='2229040'>Alice</span> <span m='2229340'>or</span>
  <span m='2229400'>Bob.</span> <span m='2231470'>Yeah,</span> <span m='2231800'>that</span>
  <span m='2231920'>would</span> <span m='2232040'>be</span> <span m='2232160'>cleaner.</span>
  </p><p><span m='2232580'>Otherwise,</span> <span m='2233000'>you'd</span> <span
  m='2233150'>have</span> <span m='2233270'>to</span> <span m='2233330'>send</span>
  <span m='2233540'>a</span> <span m='2233570'>message</span> <span m='2233900'>at</span>
  <span m='2234020'>the</span> <span m='2234170'>end</span> <span m='2234500'>to</span>
  <span m='2234890'>tell</span> <span m='2235070'>it</span> <span m='2235160'>to</span>
  <span m='2235280'>Alice</span> <span m='2235700'>or</span> <span m='2235820'>something.</span>
  <span m='2236210'>So</span> <span m='2237050'>let's</span> <span m='2237290'>make</span>
  <span m='2237470'>it</span> <span m='2237560'>symmetric,</span> <span m='2237980'>by</span>
  <span m='2238130'>saying</span> <span m='2238520'>either</span> <span m='2239090'>Alice</span>
  <span m='2239390'>or</span> <span m='2239450'>Bob</span> <span m='2239690'>knows</span>
  <span m='2239960'>it.</span> <span m='2240150'>Then</span> <span m='2240320'>the</span>
  <span m='2240410'>protocol</span> <span m='2240800'>can</span> <span m='2240980'>end.</span>
  <span m='2241910'>Good</span> <span m='2242030'>question.</span> <span m='2245530'>That</span>
  <span m='2245710'>way,</span> <span m='2246010'>we</span> <span m='2246190'>won't</span>
  <span m='2246370'>pay</span> <span m='2246610'>for</span> <span m='2247270'>an</span>
  <span m='2247420'>additive</span> <span m='2247780'>one</span> <span m='2248030'>every</span>
  <span m='2248320'>time,</span> <span m='2248660'>only</span> <span m='2248860'>pay</span>
  <span m='2249040'>for</span> <span m='2249190'>it</span> <span m='2249250'>at</span>
  <span m='2249370'>the</span> <span m='2249490'>end.</span> <span m='2250830'>Good</span>
  <span m='2250970'>questions.</span> </p><p><span m='2253330'>All</span> <span m='2253400'>right,</span>
  <span m='2253730'>so</span> <span m='2255110'>there's</span> <span m='2255320'>an</span>
  <span m='2255410'>issue</span> <span m='2255770'>here.</span> <span m='2256290'>It</span>
  <span m='2256520'>said,</span> <span m='2256760'>oh,</span> <span m='2257040'>Alice's</span>
  <span m='2257420'>message</span> <span m='2257780'>is</span> <span m='2257900'>probably</span>
  <span m='2258500'>useless.</span> <span m='2258890'>But</span> <span m='2259070'>maybe</span>
  <span m='2259490'>Alice</span> <span m='2259730'>gets</span> <span m='2259940'>lucky,</span>
  <span m='2260240'>and</span> <span m='2260360'>sends</span> <span m='2260660'>xi.</span>
  <span m='2261650'>Then,</span> <span m='2261800'>that</span> <span m='2261920'>message</span>
  <span m='2262250'>is</span> <span m='2262340'>useful.</span> </p><p><span m='2263720'>What's</span>
  <span m='2263900'>the</span> <span m='2263990'>chance</span> <span m='2264500'>that</span>
  <span m='2264780'>Alice</span> <span m='2264970'>sends</span> <span m='2265660'>xi?</span>
  <span m='2268520'>Well,</span> <span m='2269270'>1</span> <span m='2269450'>out</span>
  <span m='2269570'>of</span> <span m='2269660'>k.</span> <span m='2270980'>So there's</span>
  <span m='2271400'>something</span> <span m='2271790'>going</span> <span m='2272030'>on</span>
  <span m='2272180'>there.</span> </p><p><span m='2273560'>Alice</span> <span m='2273830'>doesn't</span>
  <span m='2274070'>just</span> <span m='2274310'>have</span> <span m='2274430'>to</span>
  <span m='2274520'>send</span> <span m='2274760'>an</span> <span m='2274850'>entire</span>
  <span m='2275240'>xj,</span> <span m='2276140'>though.</span> <span m='2279390'>Alice</span>
  <span m='2279680'>could</span> <span m='2279830'>send</span> <span m='2280050'>some</span>
  <span m='2280220'>mix</span> <span m='2280520'>of</span> <span m='2280610'>these</span>
  <span m='2280820'>guys.</span> <span m='2282230'>Maybe</span> <span m='2282500'>it</span>
  <span m='2282620'>sends</span> <span m='2282720'>the</span> <span m='2282900'>x</span>
  <span m='2283140'>or</span> <span m='2283360'>of</span> <span m='2283770'>all</span>
  <span m='2284180'>the</span> <span m='2284350'>xj's.</span> <span m='2284920'>Or</span>
  <span m='2285200'>it</span> <span m='2285580'>could</span> <span m='2285710'>be</span>
  <span m='2285800'>anything.</span> </p><p><span m='2288470'>But</span> <span m='2288650'>there's</span>
  <span m='2288830'>a</span> <span m='2288890'>limit.</span> <span m='2289430'>There's</span>
  <span m='2289580'>only</span> <span m='2289960'>a</span> <span m='2290210'>bits</span>
  <span m='2291170'>being</span> <span m='2291380'>sent</span> <span m='2291680'>from</span>
  <span m='2292220'>Alice</span> <span m='2292520'>to</span> <span m='2292640'>Bob.</span>
  <span m='2294170'>So</span> <span m='2294350'>the</span> <span m='2294470'>idea</span>
  <span m='2294740'>is</span> <span m='2295070'>if</span> <span m='2295280'>the</span>
  <span m='2295400'>total</span> <span m='2295760'>number</span> <span m='2296060'>of</span>
  <span m='2296120'>bits</span> <span m='2296450'>here</span> <span m='2296810'>is</span>
  <span m='2296990'>much</span> <span m='2297350'>bigger</span> <span m='2297650'>than</span>
  <span m='2297860'>a,</span> <span m='2299150'>then</span> <span m='2299390'>very</span>
  <span m='2299780'>few</span> <span m='2300020'>of</span> <span m='2300140'>the</span>
  <span m='2300230'>bits</span> <span m='2300470'>that</span> <span m='2300590'>you</span>
  <span m='2300740'>send</span> <span m='2301880'>are</span> <span m='2302000'>going</span>
  <span m='2302210'>to</span> <span m='2302330'>be</span> <span m='2302510'>about</span>
  <span m='2303170'>a</span> <span m='2303260'>particular</span> <span m='2304160'>element</span>
  <span m='2304580'>xi,</span> <span m='2307310'>in</span> <span m='2307490'>expectation.</span>
  <span m='2308640'>So</span> <span m='2308690'>this is</span> <span m='2308840'>a</span>
  <span m='2308900'>probabilistic</span> <span m='2309590'>thing.</span> </p><p><span
  m='2320690'>So</span> <span m='2321110'>just</span> <span m='2321350'>imagine</span>
  <span m='2321800'>this</span> <span m='2323090'>for</span> <span m='2323210'>the</span>
  <span m='2323330'>moment.</span> <span m='2328550'>Basically,</span> <span m='2328940'>because</span>
  <span m='2329390'>we're</span> <span m='2329540'>in</span> <span m='2329660'>lower</span>
  <span m='2329900'>bound</span> <span m='2330230'>world,</span> <span m='2331160'>we</span>
  <span m='2331280'>get</span> <span m='2331430'>to,</span> <span m='2331880'>essentially,</span>
  <span m='2332270'>set</span> <span m='2332450'>up</span> <span m='2332540'>the</span>
  <span m='2332630'>input</span> <span m='2332900'>however</span> <span m='2333230'>we</span>
  <span m='2333350'>want.</span> <span m='2334110'>And</span> <span m='2334130'>so,</span>
  <span m='2334280'>in</span> <span m='2334340'>particular,</span> <span m='2334790'>we're</span>
  <span m='2334940'>going</span> <span m='2335180'>to</span> <span m='2335300'>prove</span>
  <span m='2336170'>a</span> <span m='2336260'>lower</span> <span m='2336500'>bound</span>
  <span m='2336800'>that,</span> <span m='2337740'>in</span> <span m='2337940'>expectation--</span>
  <span m='2339120'>so</span> <span m='2339230'>we're</span> <span m='2339350'>going</span>
  <span m='2339500'>to</span> <span m='2339560'>have</span> <span m='2339740'>a</span>
  <span m='2339830'>probability</span> <span m='2340520'>distribution</span> <span
  m='2341120'>of</span> <span m='2342260'>data</span> <span m='2342470'>structure,</span>
  <span m='2342920'>or</span> <span m='2343040'>not</span> <span m='2343190'>data</span>
  <span m='2343370'>structures,</span> <span m='2343790'>but</span> <span m='2343940'>of</span>
  <span m='2344150'>sets</span> <span m='2344480'>of</span> <span m='2344570'>values</span>
  <span m='2345760'>that are</span> <span m='2346040'>in</span> <span m='2346220'>the</span>
  <span m='2346310'>set.</span> </p><p><span m='2347900'>And</span> <span m='2348320'>the</span>
  <span m='2348500'>claim</span> <span m='2348800'>is</span> <span m='2348950'>that,</span>
  <span m='2349100'>in</span> <span m='2349280'>expectation,</span> <span m='2350060'>any</span>
  <span m='2350300'>data</span> <span m='2350540'>structure</span> <span m='2351020'>must</span>
  <span m='2351560'>do</span> <span m='2351830'>at</span> <span m='2351950'>least</span>
  <span m='2352400'>log</span> <span m='2352730'>w</span> <span m='2353030'>over</span>
  <span m='2353240'>log</span> <span m='2353400'>log</span> <span m='2353600'>w,</span>
  <span m='2354080'>minned</span> <span m='2354260'>with</span> <span m='2356240'>log</span>
  <span m='2356510'>base</span> <span m='2356700'>w</span> <span m='2357055'>of</span>
  <span m='2357410'>n</span> <span m='2358580'>queries,</span> <span m='2360260'>in</span>
  <span m='2360590'>expectation.</span> <span m='2361500'>So</span> <span m='2361580'>we</span>
  <span m='2361670'>get</span> <span m='2361820'>to</span> <span m='2361940'>assume</span>
  <span m='2362390'>that</span> <span m='2362570'>the</span> <span m='2362720'>input</span>
  <span m='2363020'>is</span> <span m='2363140'>random.</span> <span m='2364030'>And</span>
  <span m='2364370'>we'll</span> <span m='2364520'>see</span> <span m='2364730'>why</span>
  <span m='2366050'>in</span> <span m='2366230'>a</span> <span m='2366260'>bit.</span>
  </p><p><span m='2367440'>So</span> <span m='2367460'>in</span> <span m='2367550'>this</span>
  <span m='2367640'>world,</span> <span m='2367820'>we</span> <span m='2367940'>can</span>
  <span m='2368060'>assume</span> <span m='2368330'>that</span> <span m='2368490'>i
  is</span> <span m='2368780'>chosen</span> <span m='2369110'>uniformly</span> <span
  m='2369620'>at</span> <span m='2369680'>random.</span> <span m='2372620'>And</span>
  <span m='2373580'>given</span> <span m='2373820'>that</span> <span m='2373970'>assumption,</span>
  <span m='2375320'>you</span> <span m='2375470'>would</span> <span m='2375590'>expect</span>
  <span m='2379430'>exactly</span> <span m='2380240'>a over</span> <span m='2380550'>k</span>
  <span m='2380920'>bits</span> <span m='2383540'>to</span> <span m='2383720'>be</span>
  <span m='2385040'>about</span> <span m='2387410'>xi.</span> <span m='2390230'>That</span>
  <span m='2390470'>would</span> <span m='2390620'>be</span> <span m='2390770'>the</span>
  <span m='2390890'>best</span> <span m='2391700'>you</span> <span m='2391820'>could</span>
  <span m='2391940'>hope</span> <span m='2392180'>to</span> <span m='2392270'>do.</span>
  <span m='2392560'>Sort</span> <span m='2392780'>of,</span> <span m='2392990'>you</span>
  <span m='2393410'>have</span> <span m='2393650'>a</span> <span m='2393800'>bits.</span>
  </p><p><span m='2394610'>You</span> <span m='2394700'>spread</span> <span m='2395090'>them</span>
  <span m='2395210'>out</span> <span m='2395600'>evenly</span> <span m='2396170'>talk</span>
  <span m='2396470'>about</span> <span m='2396680'>all</span> <span m='2396980'>the</span>
  <span m='2397190'>xi's</span> <span m='2397610'>that</span> <span m='2397700'>you</span>
  <span m='2397820'>can.</span> <span m='2398510'>So</span> <span m='2398600'>you</span>
  <span m='2398660'>get</span> <span m='2398810'>to</span> <span m='2398900'>communicate</span>
  <span m='2399440'>a</span> <span m='2399500'>little</span> <span m='2399830'>bit</span>
  <span m='2399920'>of</span> <span m='2400040'>information</span> <span m='2400490'>about</span>
  <span m='2400670'>the</span> <span m='2400730'>particular</span> <span m='2401220'>xi</span>
  <span m='2402530'>that</span> <span m='2402800'>Bob</span> <span m='2403130'>will</span>
  <span m='2403250'>care</span> <span m='2403460'>about.</span> <span m='2404220'>You</span>
  <span m='2404320'>don't</span> <span m='2404360'>know</span> <span m='2404450'>which</span>
  <span m='2404630'>one</span> <span m='2404750'>that</span> <span m='2404900'>is.</span>
  <span m='2405140'>So you</span> <span m='2405200'>have</span> <span m='2405290'>to</span>
  <span m='2405350'>communicate</span> <span m='2405740'>about</span> <span m='2405890'>all</span>
  <span m='2406080'>of</span> <span m='2406120'>them.</span> <span m='2406360'>So
  it's</span> <span m='2406480'>going</span> <span m='2406610'>to</span> <span m='2406700'>be</span>
  <span m='2406820'>a over</span> <span m='2407110'>k</span> <span m='2407990'>in</span>
  <span m='2408110'>expectation.</span> </p><p><span m='2410880'>So</span> <span m='2411380'>here's</span>
  <span m='2411620'>the</span> <span m='2411740'>idea.</span> <span m='2414380'>We</span>
  <span m='2414560'>want</span> <span m='2414740'>to</span> <span m='2414800'>remove</span>
  <span m='2415130'>that</span> <span m='2415310'>message</span> <span m='2415730'>so</span>
  <span m='2415850'>Alice</span> <span m='2416150'>can't</span> <span m='2416420'>communicate</span>
  <span m='2417020'>those</span> <span m='2417230'>a</span> <span m='2417460'>over</span>
  <span m='2417530'>k</span> <span m='2417855'>bits.</span> <span m='2418670'>So</span>
  <span m='2418820'>what's</span> <span m='2419000'>Bob</span> <span m='2419240'>going</span>
  <span m='2419390'>to</span> <span m='2419480'>do?</span> <span m='2420170'>Bob</span>
  <span m='2420560'>is</span> <span m='2420740'>going</span> <span m='2420980'>to</span>
  <span m='2421100'>guess</span> <span m='2421400'>them</span> <span m='2426840'>by</span>
  <span m='2427200'>flipping</span> <span m='2427560'>coins</span> <span m='2431140'>so</span>
  <span m='2431520'>he gets</span> <span m='2431790'>them</span> <span m='2432210'>uniformly</span>
  <span m='2433770'>randomly,</span> <span m='2435450'>a over</span> <span m='2435880'>k</span>
  <span m='2436155'>bits.</span> </p><p><span m='2437250'>What's</span> <span m='2437520'>the</span>
  <span m='2437610'>probability</span> <span m='2439620'>that</span> <span m='2439830'>Bob</span>
  <span m='2440100'>is</span> <span m='2440220'>right?</span> <span m='2444970'>Well,</span>
  <span m='2446570'>it's</span> <span m='2446760'>going</span> <span m='2446880'>to</span>
  <span m='2446970'>be</span> <span m='2447360'>1</span> <span m='2447930'>over</span>
  <span m='2448440'>2</span> <span m='2449370'>to</span> <span m='2449600'>the a</span>
  <span m='2449820'>over</span> <span m='2450050'>k.</span> <span m='2457590'>That</span>
  <span m='2457860'>seems</span> <span m='2458580'>not</span> <span m='2458730'>so</span>
  <span m='2458910'>big.</span> <span m='2459780'>But</span> <span m='2460320'>if</span>
  <span m='2460500'>k--</span> <span m='2461820'>how</span> <span m='2462090'>does
  it</span> <span m='2462150'>go?</span> </p><p><span m='2462310'>If</span> <span
  m='2462450'>k</span> <span m='2462720'>is</span> <span m='2462870'>much</span> <span
  m='2463170'>larger</span> <span m='2463560'>than</span> <span m='2463770'>a,</span>
  <span m='2464910'>then</span> <span m='2465120'>this</span> <span m='2465270'>is</span>
  <span m='2465390'>actually</span> <span m='2465750'>a</span> <span m='2465780'>good</span>
  <span m='2465960'>thing.</span> <span m='2466450'>So</span> <span m='2466620'>let</span>
  <span m='2466770'>me--</span> <span m='2472890'>so</span> <span m='2473040'>this</span>
  <span m='2473230'>was</span> <span m='2473340'>the</span> <span m='2473400'>probability</span>
  <span m='2473940'>of</span> <span m='2474030'>being</span> <span m='2474240'>correct.</span>
  <span m='2475900'>So</span> <span m='2476010'>the</span> <span m='2476130'>probability</span>
  <span m='2476850'>of</span> <span m='2479490'>being</span> <span m='2479670'>incorrect</span>
  <span m='2481320'>is</span> <span m='2481410'>going</span> <span m='2481560'>to</span>
  <span m='2481620'>be</span> <span m='2481710'>1</span> <span m='2481890'>minus</span>
  <span m='2482250'>that.</span> </p><p><span m='2484660'>And</span> <span m='2484770'>we're</span>
  <span m='2484890'>interested</span> <span m='2485400'>in--</span> <span m='2486480'>we</span>
  <span m='2486600'>had</span> <span m='2486720'>some</span> <span m='2486900'>probability</span>
  <span m='2487950'>delta</span> <span m='2488520'>failing</span> <span m='2488880'>before.</span>
  <span m='2489990'>And</span> <span m='2490080'>now</span> <span m='2490200'>there's</span>
  <span m='2490320'>this</span> <span m='2490470'>new</span> <span m='2490680'>way</span>
  <span m='2490830'>that</span> <span m='2490950'>we</span> <span m='2491040'>can</span>
  <span m='2491190'>fail.</span> <span m='2492120'>So</span> <span m='2492510'>I'm</span>
  <span m='2492660'>using</span> <span m='2492970'>union</span> <span m='2493330'>bound</span>
  <span m='2493590'>here,</span> <span m='2493770'>saying,</span> <span m='2494040'>well,</span>
  <span m='2494220'>we</span> <span m='2494310'>could</span> <span m='2494430'>fail</span>
  <span m='2494670'>the</span> <span m='2494760'>old</span> <span m='2494910'>way,</span>
  <span m='2495120'>or</span> <span m='2495360'>fail</span> <span m='2495630'>the</span>
  <span m='2495720'>new</span> <span m='2495870'>way.</span> <span m='2496050'>Maybe</span>
  <span m='2496290'>they're</span> <span m='2496410'>correlated,</span> <span m='2496950'>maybe</span>
  <span m='2497160'>not.</span> </p><p><span m='2497400'>But</span> <span m='2498150'>the</span>
  <span m='2498240'>worst</span> <span m='2498450'>cases</span> <span m='2498850'>is</span>
  <span m='2498950'>that</span> <span m='2499020'>it</span> <span m='2499360'>wants
  the</span> <span m='2499380'>sum</span> <span m='2500250'>of</span> <span m='2500370'>the</span>
  <span m='2500490'>two</span> <span m='2501210'>errors.</span> <span m='2501680'>So</span>
  <span m='2501930'>the</span> <span m='2502260'>increase</span> <span m='2502860'>in</span>
  <span m='2502950'>error</span> <span m='2503730'>is,</span> <span m='2503880'>at</span>
  <span m='2503970'>most,</span> <span m='2505230'>1</span> <span m='2505470'>minus</span>
  <span m='2505800'>this</span> <span m='2505980'>thing.</span> <span m='2507360'>Now,</span>
  <span m='2507540'>this</span> <span m='2508050'>1</span> <span m='2508350'>minus</span>
  <span m='2508770'>1</span> <span m='2509040'>over</span> <span m='2509430'>something</span>
  <span m='2509850'>to</span> <span m='2509940'>the</span> <span m='2510030'>power
  or</span> <span m='2510330'>something,</span> <span m='2510810'>if</span> <span
  m='2510900'>this</span> <span m='2511050'>something</span> <span m='2511440'>is</span>
  <span m='2511590'>large,</span> <span m='2512850'>there's</span> <span m='2513060'>this</span>
  <span m='2513540'>fun</span> <span m='2513990'>fact</span> <span m='2514860'>1</span>
  <span m='2515190'>minus</span> <span m='2515550'>1,</span> <span m='2515820'>over</span>
  <span m='2516120'>e</span> <span m='2516220'>to</span> <span m='2516390'>the</span>
  <span m='2516540'>x</span> <span m='2517350'>is</span> <span m='2517530'>approximately</span>
  <span m='2518700'>x.</span> </p><p><span m='2521440'>So</span> <span m='2522350'>this</span>
  <span m='2522620'>is</span> <span m='2522710'>going</span> <span m='2522920'>to</span>
  <span m='2523040'>be</span> <span m='2523220'>approximately</span> <span m='2524870'>a</span>
  <span m='2525350'>over</span> <span m='2525650'>k,</span> <span m='2526790'>if</span>
  <span m='2526940'>k</span> <span m='2527150'>is</span> <span m='2527270'>large</span>
  <span m='2527540'>enough.</span> <span m='2527930'>So this</span> <span m='2528365'>is</span>
  <span m='2528800'>for</span> <span m='2528950'>large</span> <span m='2529420'>x--</span>
  <span m='2535040'>small</span> <span m='2535370'>x,</span> <span m='2535730'>sorry.</span>
  <span m='2537450'>k</span> <span m='2538150'>is</span> <span m='2538280'>large.</span>
  <span m='2539000'>And</span> <span m='2539100'>so</span> <span m='2539150'>a over</span>
  <span m='2539470'>k</span> <span m='2539770'>is</span> <span m='2539840'>small,</span>
  <span m='2541070'>very</span> <span m='2541280'>close</span> <span m='2541580'>to</span>
  <span m='2541700'>0.</span> </p><p><span m='2546590'>So</span> <span m='2546860'>if</span>
  <span m='2547010'>this</span> <span m='2547190'>were</span> <span m='2547280'>true,</span>
  <span m='2548460'>then</span> <span m='2548510'>the</span> <span m='2548630'>error</span>
  <span m='2548840'>increase</span> <span m='2549230'>would</span> <span m='2549350'>be</span>
  <span m='2550160'>order</span> <span m='2550460'>a over</span> <span m='2550810'>k.</span>
  <span m='2551450'>There's</span> <span m='2551700'>e</span> <span m='2551920'>versus</span>
  <span m='2552130'>2.</span> <span m='2552450'>So</span> <span m='2552530'>there's</span>
  <span m='2552710'>a</span> <span m='2552800'>constant</span> <span m='2553130'>factor</span>
  <span m='2553520'>I'm</span> <span m='2553610'>losing</span> <span m='2553880'>there.</span>
  </p><p><span m='2555860'>It's</span> <span m='2556670'>not</span> <span m='2556880'>quite</span>
  <span m='2557210'>that</span> <span m='2557390'>good.</span> <span m='2558200'>So</span>
  <span m='2558290'>this</span> <span m='2558440'>is</span> <span m='2558530'>only</span>
  <span m='2558770'>intuition.</span> <span m='2559820'>The</span> <span m='2559940'>real</span>
  <span m='2560180'>bound</span> <span m='2560450'>has</span> <span m='2560600'>a</span>
  <span m='2560660'>square route</span> <span m='2561110'>here.</span> <span m='2561290'>And</span>
  <span m='2561400'>it's</span> <span m='2561530'>necessary.</span> <span m='2562790'>And</span>
  <span m='2563090'>I</span> <span m='2563240'>don't</span> <span m='2563510'>have</span>
  <span m='2563660'>a</span> <span m='2563690'>great</span> <span m='2563900'>intuition</span>
  <span m='2564320'>why</span> <span m='2564500'>it's</span> <span m='2564620'>square
  root.</span> </p><p><span m='2564920'>It's</span> <span m='2565100'>just</span>
  <span m='2565460'>a</span> <span m='2565520'>little</span> <span m='2565760'>bit</span>
  <span m='2565910'>worse</span> <span m='2566530'>than</span> <span m='2566810'>this</span>
  <span m='2567020'>intuition.</span> <span m='2569540'>I</span> <span m='2569600'>mean,</span>
  <span m='2569720'>the</span> <span m='2569840'>main</span> <span m='2570050'>issue</span>
  <span m='2570380'>is,</span> <span m='2571850'>what</span> <span m='2572000'>does</span>
  <span m='2572150'>it</span> <span m='2572210'>mean</span> <span m='2572390'>for</span>
  <span m='2572550'>bits</span> <span m='2572810'>to</span> <span m='2572930'>be</span>
  <span m='2573050'>about</span> <span m='2573410'>something?</span> <span m='2574580'>And</span>
  <span m='2575330'>can</span> <span m='2575570'>you</span> <span m='2575660'>really</span>
  <span m='2575900'>just</span> <span m='2576080'>guess</span> <span m='2576380'>those</span>
  <span m='2576680'>bits?</span> </p><p><span m='2577030'>Actually,</span> <span m='2577430'>you</span>
  <span m='2577550'>have</span> <span m='2577730'>to</span> <span m='2577820'>guess</span>
  <span m='2578180'>the</span> <span m='2578300'>message</span> <span m='2578900'>that</span>
  <span m='2579050'>Bob</span> <span m='2579350'>sent.</span> <span m='2579740'>So
  it's</span> <span m='2579860'>a</span> <span m='2579890'>little</span> <span m='2580100'>bit</span>
  <span m='2580220'>more</span> <span m='2580520'>than</span> <span m='2580670'>just</span>
  <span m='2581420'>the</span> <span m='2581510'>bits</span> <span m='2581800'>that--</span>
  <span m='2582500'>sorry</span> <span m='2582740'>that</span> <span m='2582860'>Alice</span>
  <span m='2583140'>sent.</span> <span m='2584820'>So</span> <span m='2585290'>you</span>
  <span m='2585680'>lose</span> <span m='2585920'>a</span> <span m='2585980'>little</span>
  <span m='2586160'>bit</span> <span m='2586310'>more.</span> <span m='2586760'>But</span>
  <span m='2587540'>it</span> <span m='2587660'>won't</span> <span m='2587810'>make</span>
  <span m='2587960'>a</span> <span m='2588020'>huge</span> <span m='2588260'>difference</span>
  <span m='2588560'>to</span> <span m='2588710'>us,</span> <span m='2589360'>square</span>
  <span m='2589740'>root.</span> </p><p><span m='2592920'>So</span> <span m='2593100'>that's</span>
  <span m='2593280'>some</span> <span m='2593490'>rough</span> <span m='2593640'>intuition</span>
  <span m='2594180'>for</span> <span m='2594360'>round</span> <span m='2594630'>elimination.</span>
  <span m='2595770'>Let's</span> <span m='2595980'>see</span> <span m='2596760'>why</span>
  <span m='2597120'>it</span> <span m='2597210'>is</span> <span m='2597300'>so</span>
  <span m='2597510'>cool</span> <span m='2598950'>to</span> <span m='2599090'>have</span>
  <span m='2599340'>round</span> <span m='2599580'>elimination,</span> <span m='2601200'>how</span>
  <span m='2601410'>it</span> <span m='2601470'>lets</span> <span m='2601680'>us</span>
  <span m='2601800'>prove</span> <span m='2603180'>a</span> <span m='2603300'>pretty</span>
  <span m='2603720'>strong</span> <span m='2604170'>lower</span> <span m='2604410'>bound</span>
  <span m='2610180'>on</span> <span m='2610470'>colored</span> <span m='2610920'>predecessor</span>
  <span m='2612080'>in</span> <span m='2612260'>the</span> <span m='2612330'>cell</span>
  <span m='2612600'>pro</span> <span m='2612780'>model.</span> <span m='2629300'>OK,</span>
  <span m='2630880'>I think</span> <span m='2631360'>I missed</span> <span m='2631775'>a</span>
  <span m='2632190'>claimed</span> <span m='2632750'>somewhere</span> <span m='2633170'>here.</span>
  </p><p><span m='2660870'>This</span> <span m='2661050'>is</span> <span m='2661170'>the</span>
  <span m='2661260'>lower</span> <span m='2661500'>bound</span> <span m='2661800'>we're</span>
  <span m='2661890'>going</span> <span m='2662000'>to</span> <span m='2662090'>prove.</span>
  <span m='2663150'>And</span> <span m='2663330'>it's</span> <span m='2663510'>nice</span>
  <span m='2663780'>and</span> <span m='2663870'>symmetric,</span> <span m='2664560'>log</span>
  <span m='2664830'>base</span> <span m='2665110'>a of</span> <span m='2665460'>w,</span>
  <span m='2666340'>log</span> <span m='2666570'>base</span> <span m='2666790'>b of</span>
  <span m='2666990'>n.</span> <span m='2667470'>This</span> <span m='2667650'>is</span>
  <span m='2667800'>kind</span> <span m='2667980'>of</span> <span m='2668040'>perfectly</span>
  <span m='2668520'>symmetric</span> <span m='2668820'>in</span> <span m='2669120'>Alice</span>
  <span m='2669270'>and</span> <span m='2669460'>Bob.</span> </p><p><span m='2671740'>Alice,</span>
  <span m='2675170'>well</span> <span m='2675560'>I</span> <span m='2675600'>don't
  know</span> <span m='2675780'>which</span> <span m='2675960'>one</span> <span m='2676080'>represents--</span>
  <span m='2676860'>and,</span> <span m='2677040'>apparently,</span> <span m='2677400'>Alice</span>
  <span m='2677760'>represents</span> <span m='2678240'>w.</span> <span m='2680930'>Alice</span>
  <span m='2681200'>has</span> <span m='2681360'>got</span> <span m='2681630'>a</span>
  <span m='2682740'>bits</span> <span m='2682980'>to</span> <span m='2683100'>communicate</span>
  <span m='2683580'>with</span> <span m='2683875'>to</span> <span m='2684170'>Bob.</span>
  <span m='2687740'>I</span> <span m='2687780'>mean,</span> <span m='2687960'>the</span>
  <span m='2688080'>input,</span> <span m='2688440'>I</span> <span m='2688500'>guess,</span>
  <span m='2688710'>is</span> <span m='2688800'>of</span> <span m='2688920'>size</span>
  <span m='2689180'>w.</span> <span m='2689850'>That's</span> <span m='2690030'>the</span>
  <span m='2690120'>query.</span> </p><p><span m='2691200'>Bob,</span> <span m='2691560'>on</span>
  <span m='2691680'>the</span> <span m='2691740'>other</span> <span m='2691920'>hand,</span>
  <span m='2692160'>knows</span> <span m='2692400'>all</span> <span m='2692520'>the</span>
  <span m='2692610'>data.</span> <span m='2692970'>So</span> <span m='2693210'>it's,</span>
  <span m='2693510'>in</span> <span m='2693630'>some</span> <span m='2693810'>sense,</span>
  <span m='2694020'>represents</span> <span m='2694470'>the</span> <span m='2694620'>n</span>
  <span m='2694830'>side.</span> <span m='2695610'>It's</span> <span m='2695820'>able</span>
  <span m='2696060'>to</span> <span m='2696120'>communicate</span> <span m='2696540'>with</span>
  <span m='2696650'>b</span> <span m='2696830'>bits</span> <span m='2697050'>of</span>
  <span m='2697140'>information.</span> <span m='2698550'>So</span> <span m='2698700'>log</span>
  <span m='2698950'>base</span> <span m='2699140'>b</span> <span m='2699420'>of</span>
  <span m='2699710'>n,</span> <span m='2700000'>somehow</span> <span m='2700620'>enough</span>
  <span m='2701100'>to</span> <span m='2701160'>communicate</span> <span m='2701520'>n.</span>
  </p><p><span m='2703230'>It's</span> <span m='2703470'>not</span> <span m='2703590'>a</span>
  <span m='2703650'>great</span> <span m='2703860'>intuition</span> <span m='2704280'>for</span>
  <span m='2704400'>this.</span> <span m='2704550'>But</span> <span m='2704640'>at</span>
  <span m='2704700'>least</span> <span m='2704940'>it's</span> <span m='2705060'>nice</span>
  <span m='2705360'>and</span> <span m='2705450'>symmetric.</span> <span m='2706720'>Now,</span>
  <span m='2706740'>let's</span> <span m='2706890'>work</span> <span m='2707100'>out</span>
  <span m='2707280'>what</span> <span m='2707460'>it</span> <span m='2707550'>actually</span>
  <span m='2708510'>corresponds</span> <span m='2709110'>to</span> <span m='2711190'>for--</span>
  <span m='2713760'>this</span> <span m='2713910'>is</span> <span m='2714030'>a</span>
  <span m='2714090'>lower</span> <span m='2714330'>bound</span> <span m='2714540'>on</span>
  <span m='2714630'>colored</span> <span m='2714900'>predecessor.</span> <span m='2716670'>So</span>
  <span m='2716880'>for</span> <span m='2717180'>any</span> <span m='2719250'>colored,</span>
  <span m='2720690'>even</span> <span m='2720930'>static,</span> <span m='2722400'>colored</span>
  <span m='2722820'>predecessor</span> <span m='2726090'>data</span> <span m='2726360'>structure,</span>
  <span m='2728550'>static</span> <span m='2731280'>can</span> <span m='2731430'>be</span>
  <span m='2731550'>randomized.</span> <span m='2733680'>And</span> <span m='2733860'>this</span>
  <span m='2734020'>will</span> <span m='2734130'>be</span> <span m='2734460'>a</span>
  <span m='2734580'>lower</span> <span m='2734850'>bound</span> <span m='2735150'>on</span>
  <span m='2735270'>the</span> <span m='2735360'>expected</span> <span m='2735810'>performance.</span>
  </p><p><span m='2740220'>OK,</span> <span m='2741180'>so</span> <span m='2741390'>what</span>
  <span m='2741540'>this</span> <span m='2741720'>implies</span> <span m='2742890'>for</span>
  <span m='2743070'>polynomial</span> <span m='2743670'>space,</span> <span m='2744150'>which</span>
  <span m='2744360'>is</span> <span m='2744450'>kind</span> <span m='2744610'>of</span>
  <span m='2747390'>the</span> <span m='2750090'>case</span> <span m='2750330'>we</span>
  <span m='2750450'>care</span> <span m='2750630'>about,</span> <span m='2751410'>for</span>
  <span m='2751650'>polynomial</span> <span m='2752160'>space</span> <span m='2752430'>data</span>
  <span m='2752640'>structure,</span> <span m='2754260'>a</span> <span m='2755400'>is</span>
  <span m='2755550'>going</span> <span m='2755820'>to</span> <span m='2756000'>be</span>
  <span m='2757740'>order</span> <span m='2758510'>log</span> <span m='2759000'>n.</span>
  <span m='2760860'>In</span> <span m='2760950'>fact,</span> <span m='2761320'>we</span>
  <span m='2761370'>only</span> <span m='2761640'>need</span> <span m='2762000'>a</span>
  <span m='2762750'>to</span> <span m='2762840'>be</span> <span m='2762990'>poly log</span>
  <span m='2763440'>n</span> <span m='2764460'>for</span> <span m='2764640'>what</span>
  <span m='2764820'>I'm</span> <span m='2764910'>about</span> <span m='2765150'>to</span>
  <span m='2765210'>say</span> <span m='2765390'>to</span> <span m='2765510'>be</span>
  <span m='2765600'>true.</span> <span m='2767580'>So</span> <span m='2767910'>then</span>
  <span m='2768270'>this</span> <span m='2768480'>becomes</span> <span m='2769660'>min</span>
  <span m='2771960'>log--</span> <span m='2774990'>what n?</span> <span m='2780350'>I</span>
  <span m='2780840'>guess.</span> </p><p><span m='2784480'>Is that what</span> <span
  m='2784660'>I</span> <span m='2784720'>wrote</span> <span m='2784960'>over</span>
  <span m='2785110'>there?</span> <span m='2785260'>I</span> <span m='2785380'>don't
  even</span> <span m='2785560'>remember.</span> <span m='2786700'>I</span> <span
  m='2786760'>wrote</span> <span m='2786860'>a</span> <span m='2786910'>log</span>
  <span m='2787120'>log</span> <span m='2787300'>w.</span> <span m='2788210'>I</span>
  <span m='2788520'>guess I'm</span> <span m='2788680'>going</span> <span m='2788800'>to</span>
  <span m='2788860'>write</span> <span m='2789010'>log</span> <span m='2789220'>log</span>
  <span m='2789430'>n.</span> <span m='2797500'>This is the</span> <span m='2797620'>right</span>
  <span m='2797800'>answer.</span> </p><p><span m='2806730'>OK,</span> <span m='2809200'>fine,</span>
  <span m='2809760'>so</span> <span m='2809900'>we</span> <span m='2810020'>get</span>
  <span m='2811790'>a--</span> <span m='2812570'>b</span> <span m='2812810'>is</span>
  <span m='2812930'>just</span> <span m='2813080'>w.</span> <span m='2813590'>So</span>
  <span m='2813770'>that's</span> <span m='2813980'>a</span> <span m='2814040'>log</span>
  <span m='2814250'>base</span> <span m='2814450'>w of n.</span> <span m='2814880'>That's</span>
  <span m='2815120'>just</span> <span m='2815270'>fusion</span> <span m='2815570'>tries.</span>
  <span m='2816810'>This</span> <span m='2816920'>one,</span> <span m='2817430'>ideally,</span>
  <span m='2817760'>would</span> <span m='2817850'>be</span> <span m='2817940'>log</span>
  <span m='2818180'>w.</span> <span m='2818660'>But</span> <span m='2818810'>we're</span>
  <span m='2819020'>off</span> <span m='2819230'>by</span> <span m='2819380'>this</span>
  <span m='2819560'>log</span> <span m='2819800'>log</span> <span m='2819950'>factor</span>
  <span m='2820460'>if</span> <span m='2820580'>a</span> <span m='2820770'>is</span>
  <span m='2821240'>log</span> <span m='2821480'>n.</span> </p><p><span m='2822950'>That's</span>
  <span m='2823460'>the</span> <span m='2823550'>best</span> <span m='2823760'>we'll</span>
  <span m='2823850'>be</span> <span m='2823970'>able</span> <span m='2824090'>to</span>
  <span m='2824180'>prove</span> <span m='2824600'>today.</span> <span m='2827220'>So</span>
  <span m='2827460'>this is</span> <span m='2827760'>slightly</span> <span m='2828090'>less</span>
  <span m='2828450'>beautiful,</span> <span m='2829360'>because</span> <span m='2829560'>it's</span>
  <span m='2829800'>both</span> <span m='2830430'>w</span> <span m='2830850'>and</span>
  <span m='2831060'>n.</span> <span m='2831300'>But</span> <span m='2831720'>so</span>
  <span m='2831940'>was</span> <span m='2832050'>this</span> <span m='2832200'>one.</span>
  </p><p><span m='2833580'>And</span> <span m='2833790'>this</span> <span m='2833940'>is</span>
  <span m='2834030'>not</span> <span m='2834270'>the</span> <span m='2834390'>true</span>
  <span m='2834660'>answer.</span> <span m='2835000'>The</span> <span m='2835170'>true</span>
  <span m='2835380'>answer</span> <span m='2835620'>has</span> <span m='2835800'>no</span>
  <span m='2835950'>log</span> <span m='2836160'>log.</span> <span m='2836910'>But</span>
  <span m='2837030'>that's</span> <span m='2837240'>what</span> <span m='2837360'>we</span>
  <span m='2837840'>get</span> <span m='2838170'>from</span> <span m='2838380'>nice</span>
  <span m='2838590'>symmetric</span> <span m='2839250'>bound</span> <span m='2840530'>for</span>
  <span m='2840720'>polynomial</span> <span m='2841200'>space.</span> </p><p><span
  m='2843120'>You</span> <span m='2843300'>can</span> <span m='2843450'>also</span>
  <span m='2843810'>use</span> <span m='2844140'>this</span> <span m='2844710'>to</span>
  <span m='2844860'>prove</span> <span m='2846030'>the</span> <span m='2846160'>Beame
  Fich</span> <span m='2846840'>lower</span> <span m='2847080'>bounds,</span> <span
  m='2847470'>which</span> <span m='2847890'>I've by</span> <span m='2848070'>now</span>
  <span m='2848340'>erased,</span> <span m='2850110'>which</span> <span m='2850380'>are</span>
  <span m='2850470'>the</span> <span m='2850660'>pure--</span> <span m='2851820'>the
  for</span> <span m='2852030'>all</span> <span m='2852270'>n,</span> <span m='2852480'>there</span>
  <span m='2852600'>exists</span> <span m='2852870'>a</span> <span m='2852930'>w,</span>
  <span m='2853680'>for</span> <span m='2853830'>all</span> <span m='2854010'>w,</span>
  <span m='2854370'>there</span> <span m='2854490'>exists</span> <span m='2854880'>an</span>
  <span m='2854990'>n.</span> <span m='2857910'>Why don't I</span> <span m='2858090'>briefly</span>
  <span m='2859200'>cover</span> <span m='2859470'>that?</span> </p><p><span m='2881700'>Again,</span>
  <span m='2882090'>let's</span> <span m='2882230'>assume</span> <span m='2882770'>that</span>
  <span m='2883010'>a</span> <span m='2883970'>is</span> <span m='2884090'>order</span>
  <span m='2884300'>log</span> <span m='2884585'>n with</span> <span m='2884870'>polynomial</span>
  <span m='2885380'>space.</span> <span m='2887270'>Then,</span> <span m='2887600'>the</span>
  <span m='2887720'>lower</span> <span m='2888020'>bound</span> <span m='2889310'>will</span>
  <span m='2889460'>be</span> <span m='2889610'>largest</span> <span m='2893330'>when</span>
  <span m='2894800'>the</span> <span m='2894950'>two</span> <span m='2895400'>terms</span>
  <span m='2895760'>in</span> <span m='2895850'>the</span> <span m='2895940'>min</span>
  <span m='2896210'>are</span> <span m='2896300'>equal.</span> <span m='2898880'>So</span>
  <span m='2901800'>log</span> <span m='2903190'>base</span> <span m='2903580'>a</span>
  <span m='2903970'>of</span> <span m='2904210'>w</span> <span m='2905320'>equals</span>
  <span m='2905770'>log</span> <span m='2907090'>base b</span> <span m='2907480'>of</span>
  <span m='2907660'>n.</span> </p><p><span m='2912130'>And</span> <span m='2912480'>that's</span>
  <span m='2912900'>these</span> <span m='2913140'>two</span> <span m='2913290'>guys.</span>
  <span m='2915010'>So</span> <span m='2915090'>this</span> <span m='2915330'>is</span>
  <span m='2915480'>log</span> <span m='2916530'>w</span> <span m='2917700'>over</span>
  <span m='2918450'>a</span> <span m='2918720'>is</span> <span m='2918840'>order</span>
  <span m='2919050'>log</span> <span m='2919320'>n.</span> <span m='2919590'>So</span>
  <span m='2919770'>this</span> <span m='2919920'>is</span> <span m='2920010'>going</span>
  <span m='2920130'>to</span> <span m='2920220'>be</span> <span m='2920370'>order</span>
  <span m='2920640'>log</span> <span m='2920940'>log</span> <span m='2921210'>n.</span>
  </p><p><span m='2924660'>And</span> <span m='2924870'>I</span> <span m='2924960'>want</span>
  <span m='2925140'>this</span> <span m='2925320'>to</span> <span m='2925470'>be</span>
  <span m='2925650'>equal</span> <span m='2927060'>to</span> <span m='2927210'>log</span>
  <span m='2927600'>n</span> <span m='2927930'>over</span> <span m='2928440'>log</span>
  <span m='2929470'>w.</span> <span m='2931200'>So</span> <span m='2931470'>we</span>
  <span m='2931620'>can</span> <span m='2932010'>cross</span> <span m='2932310'>multiply,</span>
  <span m='2933205'>get</span> <span m='2933500'>log</span> <span m='2933990'>square</span>
  <span m='2934560'>w</span> <span m='2936270'>equals</span> <span m='2937560'>log</span>
  <span m='2937950'>n,</span> <span m='2939390'>log</span> <span m='2939630'>log</span>
  <span m='2939810'>n.</span> <span m='2943070'>And</span> <span m='2943200'>so</span>
  <span m='2943560'>log</span> <span m='2943920'>w</span> <span m='2945780'>is</span>
  <span m='2945930'>equal</span> <span m='2946200'>to</span> <span m='2947250'>square</span>
  <span m='2947760'>root</span> <span m='2948990'>log</span> <span m='2949440'>n,</span>
  <span m='2950950'>log</span> <span m='2951060'>log</span> <span m='2951180'>n.</span>
  </p><p><span m='2956130'>And</span> <span m='2959280'>let's</span> <span m='2959550'>see.</span>
  <span m='2959820'>You</span> <span m='2959940'>can</span> <span m='2960090'>also</span>
  <span m='2960480'>take</span> <span m='2960810'>logs,</span> <span m='2962030'>and</span>
  <span m='2962160'>from</span> <span m='2962370'>this</span> <span m='2962640'>conclude</span>
  <span m='2963900'>that</span> <span m='2964250'>log</span> <span m='2964620'>log</span>
  <span m='2964860'>w</span> <span m='2967050'>equals</span> <span m='2968670'>log</span>
  <span m='2969120'>log</span> <span m='2969450'>n.</span> <span m='2972640'>I'm</span>
  <span m='2972990'>throwing</span> <span m='2973260'>away</span> <span m='2973410'>constant</span>
  <span m='2973740'>factors.</span> </p><p><span m='2974410'>And</span> <span m='2974510'>when</span>
  <span m='2974520'>I</span> <span m='2974580'>say</span> <span m='2974760'>equal</span>
  <span m='2975060'>here,</span> <span m='2975750'>I</span> <span m='2975810'>mean</span>
  <span m='2975980'>up</span> <span m='2976060'>to</span> <span m='2976170'>constant</span>
  <span m='2976500'>factors</span> <span m='2977290'>for</span> <span m='2977560'>throughout</span>
  <span m='2977940'>this</span> <span m='2978570'>half</span> <span m='2978870'>board.</span>
  <span m='2980550'>So</span> <span m='2980630'>you</span> <span m='2980700'>take</span>
  <span m='2980880'>logs.</span> <span m='2981240'>You</span> <span m='2981330'>get</span>
  <span m='2981480'>2</span> <span m='2981690'>log</span> <span m='2981870'>log</span>
  <span m='2982050'>w</span> <span m='2982470'>on</span> <span m='2982560'>the</span>
  <span m='2982620'>left</span> <span m='2982830'>hand</span> <span m='2982950'>side.</span>
  <span m='2983610'>Over</span> <span m='2983790'>here,</span> <span m='2983940'>you</span>
  <span m='2984030'>get</span> <span m='2984150'>log</span> <span m='2984360'>log</span>
  <span m='2984540'>n,</span> <span m='2984660'>plus</span> <span m='2984870'>log</span>
  <span m='2985050'>log</span> <span m='2985260'>log</span> <span m='2985530'>n.</span>
  </p><p><span m='2986190'>So</span> <span m='2986430'>it's</span> <span m='2986550'>dominated</span>
  <span m='2986970'>by</span> <span m='2987120'>log</span> <span m='2987360'>log</span>
  <span m='2987570'>n.</span> <span m='2988050'>So</span> <span m='2988350'>in</span>
  <span m='2988530'>this</span> <span m='2988650'>scenario,</span> <span m='2989280'>where</span>
  <span m='2990090'>these</span> <span m='2990270'>two</span> <span m='2990390'>things</span>
  <span m='2990690'>are</span> <span m='2990750'>roughly</span> <span m='2991050'>equal,</span>
  <span m='2991530'>you get</span> <span m='2992030'>log</span> <span m='2992240'>log</span>
  <span m='2992430'>w</span> <span m='2992810'>roughly</span> <span m='2993090'>equal</span>
  <span m='2993300'>to</span> <span m='2993390'>log</span> <span m='2993600'>log</span>
  <span m='2993810'>n.</span> <span m='2995580'>And</span> <span m='2995790'>so,</span>
  <span m='2996570'>from</span> <span m='2996930'>this</span> <span m='2997140'>bound,</span>
  <span m='2998150'>or</span> <span m='2998280'>from</span> <span m='2998480'>this</span>
  <span m='2998770'>equality,</span> <span m='2999990'>we</span> <span m='3000140'>should</span>
  <span m='3000350'>get</span> <span m='3000620'>the</span> <span m='3001100'>old</span>
  <span m='3001880'>Beame</span> <span m='3002120'>Fich</span> <span m='3002360'>bounds,</span>
  <span m='3002760'>which</span> <span m='3003110'>let</span> <span m='3003260'>me</span>
  <span m='3004580'>write</span> <span m='3004790'>them</span> <span m='3004940'>again.</span>
  </p><p><span m='3018830'>So</span> <span m='3019100'>they</span> <span m='3019370'>are--</span>
  <span m='3024630'>I</span> <span m='3025090'>mean,</span> <span m='3025200'>we</span>
  <span m='3025280'>want</span> <span m='3025460'>to</span> <span m='3025520'>compute</span>
  <span m='3026420'>what</span> <span m='3026630'>was</span> <span m='3026960'>this</span>
  <span m='3027110'>bound.</span> <span m='3027940'>We have</span> <span m='3028130'>log</span>
  <span m='3028430'>w,</span> <span m='3029180'>divided</span> <span m='3029500'>by</span>
  <span m='3029660'>log</span> <span m='3030890'>a,</span> <span m='3031280'>or</span>
  <span m='3031660'>log</span> <span m='3031990'>w</span> <span m='3032210'>divided</span>
  <span m='3032510'>by</span> <span m='3032660'>log</span> <span m='3032900'>log</span>
  <span m='3033110'>n--</span> <span m='3033980'>so</span> <span m='3034730'>log</span>
  <span m='3035030'>w,</span> <span m='3036260'>divided by</span> <span m='3036350'>log</span>
  <span m='3036560'>log</span> <span m='3036650'>n.</span> <span m='3037400'>But</span>
  <span m='3037520'>log</span> <span m='3037760'>log</span> <span m='3037940'>n</span>
  <span m='3038140'>now</span> <span m='3038410'>is</span> <span m='3038650'>log log</span>
  <span m='3038930'>w.</span> <span m='3039500'>So</span> <span m='3039680'>this</span>
  <span m='3039890'>is</span> <span m='3039980'>going</span> <span m='3040220'>to</span>
  <span m='3040310'>be</span> <span m='3041060'>log</span> <span m='3041300'>w</span>
  <span m='3041840'>over</span> <span m='3042200'>log</span> <span m='3042430'>log</span>
  <span m='3042730'>w,</span> <span m='3044060'>which</span> <span m='3044270'>was</span>
  <span m='3044570'>one</span> <span m='3044840'>of</span> <span m='3045020'>the</span>
  <span m='3046270'>Beam Fich</span> <span m='3046780'>bounds.</span> </p><p><span
  m='3047000'>So</span> <span m='3047180'>for</span> <span m='3047390'>all</span>
  <span m='3049610'>w,</span> <span m='3050370'>there</span> <span m='3050530'>exists</span>
  <span m='3050800'>an</span> <span m='3050960'>n,</span> <span m='3051620'>such</span>
  <span m='3051950'>that</span> <span m='3052790'>omega</span> <span m='3054080'>this</span>
  <span m='3054290'>thing</span> <span m='3054560'>holds.</span> <span m='3056480'>On</span>
  <span m='3056570'>the</span> <span m='3056660'>other</span> <span m='3056870'>hand,</span>
  <span m='3057270'>we</span> <span m='3057290'>have</span> <span m='3057720'>log</span>
  <span m='3058040'>n,</span> <span m='3058220'>divided</span> <span m='3058550'>by</span>
  <span m='3058790'>log</span> <span m='3060140'>w</span> <span m='3067880'>is</span>
  <span m='3068030'>now</span> <span m='3068300'>square</span> <span m='3068690'>root</span>
  <span m='3068840'>of</span> <span m='3068930'>log</span> <span m='3069230'>n,</span>
  <span m='3069380'>log</span> <span m='3069590'>log</span> <span m='3069770'>n.</span>
  <span m='3070360'>So</span> <span m='3070740'>this is</span> <span m='3071120'>log</span>
  <span m='3071780'>n,</span> <span m='3071990'>divided</span> <span m='3072660'>by</span>
  <span m='3072980'>square</span> <span m='3073370'>root</span> <span m='3073670'>of</span>
  <span m='3073820'>log</span> <span m='3074030'>n,</span> <span m='3075400'>log</span>
  <span m='3075650'>log</span> <span m='3076000'>n.</span> </p><p><span m='3077360'>So</span>
  <span m='3077660'>the</span> <span m='3077810'>square</span> <span m='3078180'>root</span>
  <span m='3078930'>log</span> <span m='3079210'>n</span> <span m='3079380'>cancels</span>
  <span m='3079850'>with this.</span> <span m='3080160'>We</span> <span m='3080260'>end</span>
  <span m='3080270'>up</span> <span m='3080390'>with</span> <span m='3080510'>square
  root</span> <span m='3080870'>of</span> <span m='3080960'>log</span> <span m='3081170'>n</span>
  <span m='3081290'>on</span> <span m='3081380'>the</span> <span m='3081500'>top.</span>
  <span m='3082760'>And</span> <span m='3082940'>we</span> <span m='3083060'>keep</span>
  <span m='3083440'>the</span> <span m='3083820'>square</span> <span m='3083920'>root</span>
  <span m='3084190'>of</span> <span m='3084320'>log</span> <span m='3084590'>log</span>
  <span m='3084800'>n</span> <span m='3084950'>on</span> <span m='3085070'>the</span>
  <span m='3085160'>bottom.</span> </p><p><span m='3087710'>And</span> <span m='3087830'>so</span>
  <span m='3088010'>we</span> <span m='3088070'>get</span> <span m='3088220'>the</span>
  <span m='3088340'>other</span> <span m='3088580'>Beam Fich</span> <span m='3088810'>Xiau</span>
  <span m='3089070'>bound,</span> <span m='3092230'>for</span> <span m='3092380'>all</span>
  <span m='3092540'>n,</span> <span m='3092780'>there</span> <span m='3092900'>exists</span>
  <span m='3093170'>a</span> <span m='3093230'>w,</span> <span m='3093860'>such</span>
  <span m='3094220'>that</span> <span m='3094870'>omega</span> <span m='3095920'>this</span>
  <span m='3096170'>holds.</span> <span m='3098040'>And when</span> <span m='3098150'>you</span>
  <span m='3098240'>just</span> <span m='3098390'>need</span> <span m='3098570'>existence,</span>
  <span m='3099170'>then</span> <span m='3099320'>we</span> <span m='3099440'>get</span>
  <span m='3099560'>to</span> <span m='3099650'>choose</span> <span m='3100010'>the</span>
  <span m='3100100'>relationship</span> <span m='3100610'>between</span> <span m='3100880'>n</span>
  <span m='3100970'>and</span> <span m='3101090'>w</span> <span m='3101330'>however</span>
  <span m='3101620'>we</span> <span m='3101780'>want.</span> </p><p><span m='3102410'>So</span>
  <span m='3102530'>you</span> <span m='3102590'>don't</span> <span m='3102680'>have</span>
  <span m='3102800'>to</span> <span m='3102890'>believe</span> <span m='3103190'>me</span>
  <span m='3103310'>that</span> <span m='3103430'>it's</span> <span m='3103550'>largest</span>
  <span m='3103880'>when</span> <span m='3104000'>they're</span> <span m='3104090'>equal.</span>
  <span m='3104600'>It</span> <span m='3105350'>happens</span> <span m='3105740'>to</span>
  <span m='3105860'>be</span> <span m='3105950'>true.</span> <span m='3106220'>But</span>
  <span m='3107780'>the</span> <span m='3107990'>point</span> <span m='3108230'>is,</span>
  <span m='3108380'>there</span> <span m='3108560'>is</span> <span m='3108710'>a</span>
  <span m='3108770'>choice</span> <span m='3109160'>of</span> <span m='3109280'>w</span>
  <span m='3109590'>and n--</span> <span m='3109770'>namely,</span> <span m='3110090'>this</span>
  <span m='3110300'>choice,</span> <span m='3111110'>log w</span> <span m='3111530'>equals</span>
  <span m='3111920'>root log</span> <span m='3112190'>n,</span> <span m='3112340'>log</span>
  <span m='3112590'>log</span> <span m='3112910'>n,</span> <span m='3113230'>where</span>
  <span m='3113330'>you</span> <span m='3113390'>get</span> <span m='3113540'>a</span>
  <span m='3113570'>lower</span> <span m='3113710'>bound</span> <span m='3113930'>of</span>
  <span m='3114110'>this.</span> <span m='3116060'>And</span> <span m='3116240'>there's</span>
  <span m='3116390'>another</span> <span m='3116600'>choice</span> <span m='3116870'>for</span>
  <span m='3116990'>n</span> <span m='3117200'>versus</span> <span m='3117440'>w</span>
  <span m='3117860'>where</span> <span m='3117980'>this</span> <span m='3118160'>happens.</span>
  </p><p><span m='3119750'>So</span> <span m='3119870'>this</span> <span m='3120050'>implies</span>
  <span m='3120530'>the</span> <span m='3121670'>Beame</span> <span m='3122150'>Fich</span>
  <span m='3122590'>Xiau</span> <span m='3123150'>bounds.</span> <span m='3124660'>But</span>
  <span m='3124850'>I</span> <span m='3124940'>kind</span> <span m='3125120'>of</span>
  <span m='3125210'>prefer</span> <span m='3125540'>this</span> <span m='3125750'>form,</span>
  <span m='3126230'>because</span> <span m='3126440'>it's</span> <span m='3126680'>clear</span>
  <span m='3127040'>up</span> <span m='3127190'>to</span> <span m='3127310'>this</span>
  <span m='3127460'>log</span> <span m='3127700'>log</span> <span m='3127910'>n</span>
  <span m='3128030'>factor,</span> <span m='3128960'>we</span> <span m='3129200'>understand</span>
  <span m='3129710'>the</span> <span m='3129800'>complete</span> <span m='3130100'>trade-off</span>
  <span m='3130880'>between</span> <span m='3131600'>w</span> <span m='3131930'>and</span>
  <span m='3132020'>n,</span> <span m='3132710'>assuming</span> <span m='3133070'>polynomial</span>
  <span m='3133550'>space.</span> <span m='3136880'>So</span> <span m='3137030'>we're</span>
  <span m='3137090'>going</span> <span m='3137210'>to</span> <span m='3137270'>prove</span>
  <span m='3137510'>this</span> <span m='3137700'>bound,</span> <span m='3138020'>which</span>
  <span m='3139010'>implies</span> <span m='3139430'>all</span> <span m='3139550'>this</span>
  <span m='3139690'>stuff,</span> <span m='3141650'>using</span> <span m='3142370'>round</span>
  <span m='3142580'>elimination</span> <span m='3143100'>lemma.</span> </p><p><span
  m='3177460'>So</span> <span m='3177770'>we're</span> <span m='3177890'>proving</span>
  <span m='3179480'>this</span> <span m='3179630'>claim</span> <span m='3179930'>here,</span>
  <span m='3183620'>omega</span> <span m='3184040'>min</span> <span m='3184390'>log</span>
  <span m='3184800'>base</span> <span m='3185190'>of</span> <span m='3185460'>a of
  w,</span> <span m='3185960'>log</span> <span m='3186230'>base</span> <span m='3186530'>b</span>
  <span m='3186690'>of</span> <span m='3186980'>n,</span> <span m='3187640'>for</span>
  <span m='3187790'>any</span> <span m='3188030'>colored</span> <span m='3188330'>predecessor</span>
  <span m='3189410'>data</span> <span m='3189650'>structure.</span> <span m='3193190'>So</span>
  <span m='3193310'>let's</span> <span m='3193490'>suppose</span> <span m='3193910'>you</span>
  <span m='3194030'>have</span> <span m='3194420'>a</span> <span m='3195110'>colored</span>
  <span m='3195350'>predecessor</span> <span m='3195860'>data</span> <span m='3196070'>structure.</span>
  <span m='3197420'>And</span> <span m='3197690'>it</span> <span m='3197930'>can</span>
  <span m='3198230'>answer</span> <span m='3198620'>queries</span> <span m='3199070'>in</span>
  <span m='3199280'>t</span> <span m='3200240'>cell</span> <span m='3200540'>probes.</span>
  <span m='3205130'>which</span> <span m='3206180'>in</span> <span m='3206390'>the</span>
  <span m='3206510'>communication</span> <span m='3207110'>complexity</span> <span
  m='3207530'>perspective,</span> <span m='3208040'>that's</span> <span m='3208220'>rounds</span>
  <span m='3208580'>of</span> <span m='3208670'>communication,</span> <span m='3213230'>or</span>
  <span m='3213730'>colored</span> <span m='3216260'>predecessor.</span> </p><p><span
  m='3218810'>Our</span> <span m='3218930'>goal</span> <span m='3221720'>is</span>
  <span m='3221930'>to</span> <span m='3222080'>do</span> <span m='3222560'>t</span>
  <span m='3223310'>round</span> <span m='3223640'>eliminations.</span> <span m='3228530'>Slight</span>
  <span m='3228830'>discrepancy</span> <span m='3229400'>in</span> <span m='3229490'>terminology</span>
  <span m='3230090'>here--</span> <span m='3230770'>round</span> <span m='3231020'>elimination</span>
  <span m='3231560'>lemma</span> <span m='3232190'>is</span> <span m='3232340'>really</span>
  <span m='3232580'>about</span> <span m='3233300'>eliminating</span> <span m='3233840'>one</span>
  <span m='3234020'>message,</span> <span m='3234410'>which</span> <span m='3234560'>is</span>
  <span m='3234650'>half a</span> <span m='3234920'>round.</span> <span m='3235760'>But</span>
  <span m='3235840'>you</span> <span m='3235910'>do</span> <span m='3236030'>it</span>
  <span m='3236090'>twice,</span> <span m='3236680'>you</span> <span m='3236900'>eliminate</span>
  <span m='3237260'>a round.</span> </p><p><span m='3238470'>And</span> <span m='3238610'>so</span>
  <span m='3238760'>we</span> <span m='3238850'>need</span> <span m='3239000'>to</span>
  <span m='3239090'>do</span> <span m='3239660'>two</span> <span m='3239900'>t</span>
  <span m='3240300'>calls</span> <span m='3241100'>to</span> <span m='3241250'>this</span>
  <span m='3241500'>lemma.</span> <span m='3242270'>We</span> <span m='3242390'>will</span>
  <span m='3242480'>eliminate</span> <span m='3242930'>all</span> <span m='3243080'>messages.</span>
  <span m='3244010'>Then</span> <span m='3244190'>there's</span> <span m='3244370'>zero</span>
  <span m='3244700'>communication.</span> </p><p><span m='3246320'>Then</span> <span
  m='3247990'>the</span> <span m='3254270'>best</span> <span m='3254540'>you</span>
  <span m='3254600'>could</span> <span m='3254720'>hope</span> <span m='3254900'>to</span>
  <span m='3254990'>do</span> <span m='3255170'>is</span> <span m='3255350'>by</span>
  <span m='3255500'>flipping</span> <span m='3255830'>a</span> <span m='3255890'>coin.</span>
  <span m='3263630'>Maybe</span> <span m='3263960'>you're</span> <span m='3264080'>worse</span>
  <span m='3264320'>than</span> <span m='3264440'>that.</span> <span m='3264920'>But</span>
  <span m='3265040'>the</span> <span m='3266450'>probability</span> <span m='3266900'>of</span>
  <span m='3266990'>error</span> <span m='3267110'>has</span> <span m='3267260'>to</span>
  <span m='3267380'>be</span> <span m='3267470'>at</span> <span m='3267530'>least</span>
  <span m='3267770'>1/2.</span> </p><p><span m='3269630'>So</span> <span m='3269810'>we'll</span>
  <span m='3269960'>either</span> <span m='3270170'>get</span> <span m='3270290'>a</span>
  <span m='3270350'>contradiction.</span> <span m='3271520'>Or</span> <span m='3271970'>we're</span>
  <span m='3272150'>going</span> <span m='3272240'>to</span> <span m='3272330'>set</span>
  <span m='3272510'>things</span> <span m='3272750'>up</span> <span m='3272840'>so</span>
  <span m='3272960'>the</span> <span m='3273110'>error</span> <span m='3273350'>is,</span>
  <span m='3273470'>at</span> <span m='3273560'>most,</span> <span m='3273860'>1/3.</span>
  <span m='3275060'>And,</span> <span m='3275210'>therefore,</span> <span m='3276680'>this</span>
  <span m='3276860'>will</span> <span m='3276980'>prove</span> <span m='3277280'>that</span>
  <span m='3277430'>t</span> <span m='3277700'>has</span> <span m='3277880'>to</span>
  <span m='3278000'>be</span> <span m='3278150'>large.</span> <span m='3279810'>So</span>
  <span m='3279860'>you</span> <span m='3280010'>couldn't</span> <span m='3280340'>eliminate</span>
  <span m='3280730'>all</span> <span m='3280850'>the</span> <span m='3280990'>messages.</span>
  <span m='3281750'>Anyway,</span> <span m='3282170'>we'll</span> <span m='3283010'>see</span>
  <span m='3283190'>that</span> <span m='3283400'>in</span> <span m='3283490'>a</span>
  <span m='3283520'>moment.</span> </p><p><span m='3286890'>So</span> <span m='3287360'>we</span>
  <span m='3287600'>have</span> <span m='3287750'>a</span> <span m='3287810'>setup</span>
  <span m='3288140'>like</span> <span m='3288290'>this.</span> <span m='3291510'>And</span>
  <span m='3291970'>in</span> <span m='3292430'>our</span> <span m='3292640'>case,</span>
  <span m='3293280'>with</span> <span m='3293750'>this</span> <span m='3294500'>picture,</span>
  <span m='3295490'>there</span> <span m='3295550'>is</span> <span m='3295700'>an</span>
  <span m='3295790'>asymmetry</span> <span m='3296450'>between</span> <span m='3296780'>Alice</span>
  <span m='3297110'>and</span> <span m='3297200'>Bob.</span> <span m='3297740'>I</span>
  <span m='3297770'>mean,</span> <span m='3297920'>yeah,</span> <span m='3298100'>the</span>
  <span m='3298220'>picture</span> <span m='3298440'>is</span> <span m='3298550'>nice</span>
  <span m='3298790'>and</span> <span m='3298910'>clean.</span> </p><p><span m='3299750'>But</span>
  <span m='3300560'>in</span> <span m='3300740'>reality,</span> <span m='3301370'>this</span>
  <span m='3301550'>has</span> <span m='3301790'>to</span> <span m='3301880'>represent</span>
  <span m='3302360'>a</span> <span m='3302420'>colored</span> <span m='3302750'>predecessor</span>
  <span m='3303320'>problem.</span> <span m='3304380'>So</span> <span m='3304480'>in</span>
  <span m='3304580'>reality,</span> <span m='3304850'>Bob</span> <span m='3305300'>is</span>
  <span m='3305420'>a</span> <span m='3305510'>data</span> <span m='3305810'>structure</span>
  <span m='3306770'>and</span> <span m='3306950'>is</span> <span m='3307040'>not</span>
  <span m='3307220'>very</span> <span m='3307430'>smart,</span> <span m='3307910'>just</span>
  <span m='3308600'>does</span> <span m='3308840'>random</span> <span m='3309140'>access.</span>
  <span m='3310040'>Alice,</span> <span m='3312170'>we</span> <span m='3312350'>don't</span>
  <span m='3312480'>know,</span> <span m='3312890'>could</span> <span m='3313040'>be</span>
  <span m='3313130'>very</span> <span m='3313310'>smart.</span> <span m='3314420'>And</span>
  <span m='3315730'>Alice just</span> <span m='3315890'>has</span> <span m='3316070'>a</span>
  <span m='3316130'>single</span> <span m='3316430'>word.</span> </p><p><span m='3318090'>So</span>
  <span m='3318170'>there's</span> <span m='3318380'>an</span> <span m='3318500'>asymmetry</span>
  <span m='3319010'>between</span> <span m='3319280'>Alice</span> <span m='3319520'>and</span>
  <span m='3319610'>Bob.</span> <span m='3320210'>So</span> <span m='3320420'>when</span>
  <span m='3320600'>we</span> <span m='3320780'>eliminate</span> <span m='3321170'>a</span>
  <span m='3321230'>message</span> <span m='3321530'>from</span> <span m='3321710'>Alice</span>
  <span m='3322010'>to</span> <span m='3322130'>Bob,</span> <span m='3322790'>it's</span>
  <span m='3322910'>going</span> <span m='3323030'>to</span> <span m='3323120'>be</span>
  <span m='3323210'>different</span> <span m='3323630'>from</span> <span m='3323870'>eliminating</span>
  <span m='3324380'>a</span> <span m='3324410'>message</span> <span m='3324710'>from</span>
  <span m='3324860'>Bob</span> <span m='3325100'>to</span> <span m='3325190'>Alice.</span>
  <span m='3325870'>This</span> <span m='3326130'>f</span> <span m='3326460'>to</span>
  <span m='3326620'>the</span> <span m='3326720'>k</span> <span m='3327080'>thing</span>
  <span m='3328520'>here</span> <span m='3329030'>is</span> <span m='3329210'>going</span>
  <span m='3329360'>to</span> <span m='3329420'>have</span> <span m='3329600'>to</span>
  <span m='3329720'>be</span> <span m='3329840'>different</span> <span m='3331040'>when</span>
  <span m='3331190'>we're</span> <span m='3331460'>doing</span> <span m='3331820'>an</span>
  <span m='3331970'>Alice</span> <span m='3332270'>to</span> <span m='3332390'>Bob</span>
  <span m='3332570'>message,</span> <span m='3333020'>versus</span> <span m='3333320'>doing</span>
  <span m='3333500'>a</span> <span m='3333560'>Bob to</span> <span m='3333820'>Alice</span>
  <span m='3334160'>message.</span> </p><p><span m='3335320'>And</span> <span m='3336050'>that's</span>
  <span m='3336290'>where</span> <span m='3336440'>we're</span> <span m='3336560'>going</span>
  <span m='3336680'>to</span> <span m='3336770'>get</span> <span m='3336920'>a</span>
  <span m='3337050'>min.</span> <span m='3339440'>When</span> <span m='3339560'>we</span>
  <span m='3339680'>go</span> <span m='3339830'>from</span> <span m='3340010'>Alice</span>
  <span m='3340220'>to</span> <span m='3340340'>Bob,</span> <span m='3341210'>we're</span>
  <span m='3341270'>going</span> <span m='3341390'>to</span> <span m='3341480'>be,</span>
  <span m='3341840'>essentially,</span> <span m='3342200'>contributing</span> <span
  m='3342710'>to</span> <span m='3342800'>this</span> <span m='3342980'>term.</span>
  <span m='3343220'>When</span> <span m='3343310'>we</span> <span m='3343370'>go</span>
  <span m='3343490'>Bob</span> <span m='3343730'>to</span> <span m='3343820'>Alice,</span>
  <span m='3344120'>we're</span> <span m='3344210'>going</span> <span m='3344290'>to</span>
  <span m='3344390'>be</span> <span m='3344540'>contributing</span> <span m='3344990'>to</span>
  <span m='3345080'>this</span> <span m='3345260'>term,</span> <span m='3345920'>I</span>
  <span m='3345980'>think,</span> <span m='3346600'>or</span> <span m='3346800'>the</span>
  <span m='3347000'>reverse.</span> <span m='3347980'>We'll</span> <span m='3348110'>find</span>
  <span m='3348320'>out</span> <span m='3348440'>in</span> <span m='3348500'>a</span>
  <span m='3348620'>second.</span> </p><p><span m='3352230'>So</span> <span m='3353120'>let's</span>
  <span m='3353450'>do</span> <span m='3353810'>first</span> <span m='3354200'>Alice</span>
  <span m='3354530'>to</span> <span m='3354650'>Bob,</span> <span m='3368750'>because</span>
  <span m='3368960'>that's</span> <span m='3369170'>the</span> <span m='3369230'>first</span>
  <span m='3369530'>type</span> <span m='3369740'>of</span> <span m='3369800'>message</span>
  <span m='3370190'>we</span> <span m='3370310'>need</span> <span m='3370460'>to</span>
  <span m='3370550'>eliminate.</span> <span m='3372870'>So</span> <span m='3374090'>let's</span>
  <span m='3374390'>suppose--</span> <span m='3375620'>now,</span> <span m='3375890'>as</span>
  <span m='3376100'>we</span> <span m='3376250'>eliminate</span> <span m='3376760'>things,</span>
  <span m='3377960'>w</span> <span m='3378500'>and</span> <span m='3378680'>n</span>
  <span m='3379130'>are</span> <span m='3379250'>going</span> <span m='3379460'>to</span>
  <span m='3379580'>decrease.</span> <span m='3381120'>So</span> <span m='3381620'>I'm</span>
  <span m='3381710'>going</span> <span m='3381890'>to</span> <span m='3382070'>suppose</span>
  <span m='3383780'>at</span> <span m='3383930'>this</span> <span m='3384110'>point,</span>
  <span m='3385110'>Alice's</span> <span m='3385640'>input</span> <span m='3388130'>has</span>
  <span m='3388730'>w</span> <span m='3389240'>prime</span> <span m='3390080'>bits</span>
  <span m='3390380'>left.</span> </p><p><span m='3391460'>Initially,</span> <span
  m='3391940'>w</span> <span m='3392240'>prime</span> <span m='3392490'>is</span>
  <span m='3392630'>w.</span> <span m='3393000'>But</span> <span m='3393200'>I</span>
  <span m='3393290'>want</span> <span m='3393410'>to</span> <span m='3393890'>do the</span>
  <span m='3393980'>generic</span> <span m='3394370'>case</span> <span m='3394760'>so
  I</span> <span m='3394820'>don't</span> <span m='3394970'>have</span> <span m='3395060'>to</span>
  <span m='3395150'>repeat</span> <span m='3396080'>anything.</span> <span m='3398970'>Here's</span>
  <span m='3399080'>the</span> <span m='3399170'>concept.</span> </p><p><span m='3400650'>Remember,</span>
  <span m='3401660'>we're</span> <span m='3401860'>proving</span> <span m='3402110'>a</span>
  <span m='3402140'>lower</span> <span m='3402380'>bound.</span> <span m='3402690'>We</span>
  <span m='3402740'>get</span> <span m='3402860'>to</span> <span m='3402980'>set</span>
  <span m='3403190'>up</span> <span m='3403430'>the</span> <span m='3403550'>set</span>
  <span m='3403760'>of</span> <span m='3403850'>elements</span> <span m='3404240'>however</span>
  <span m='3404720'>we</span> <span m='3404870'>want.</span> <span m='3406020'>We're</span>
  <span m='3406080'>going</span> <span m='3406310'>to</span> <span m='3406680'>define</span>
  <span m='3406960'>a</span> <span m='3407030'>distribution</span> <span m='3407750'>on</span>
  <span m='3407900'>the</span> <span m='3407990'>set</span> <span m='3408170'>of</span>
  <span m='3408260'>elements.</span> <span m='3411620'>And</span> <span m='3411890'>we're</span>
  <span m='3412040'>going</span> <span m='3412280'>to</span> <span m='3412430'>do</span>
  <span m='3412580'>that</span> <span m='3412940'>by</span> <span m='3416690'>breaking</span>
  <span m='3417290'>this</span> <span m='3417650'>input,</span> <span m='3419120'>w</span>
  <span m='3419480'>prime</span> <span m='3420410'>bits,</span> <span m='3421850'>into</span>
  <span m='3422750'>a</span> <span m='3422870'>lot</span> <span m='3423170'>of</span>
  <span m='3423260'>pieces.</span> </p><p><span m='3435340'>Alice's</span> <span m='3436000'>input,</span>
  <span m='3436300'>you</span> <span m='3436480'>think</span> <span m='3436690'>of</span>
  <span m='3436810'>as</span> <span m='3437030'>x.</span> <span m='3440330'>Don't</span>
  <span m='3440480'>necessarily</span> <span m='3440800'>want</span> <span m='3440920'>to</span>
  <span m='3440980'>call</span> <span m='3441190'>it</span> <span m='3441280'>x.</span>
  <span m='3441890'>Well,</span> <span m='3441970'>sure,</span> <span m='3442240'>we</span>
  <span m='3442360'>can</span> <span m='3442450'>call it</span> <span m='3442770'>x.</span>
  <span m='3443630'>There it</span> <span m='3444080'>Is</span> </p><p><span m='3446470'>What</span>
  <span m='3446650'>I'd</span> <span m='3446740'>like</span> <span m='3446920'>to</span>
  <span m='3447040'>do</span> <span m='3447700'>is</span> <span m='3447880'>break</span>
  <span m='3448150'>that</span> <span m='3448330'>input</span> <span m='3448720'>into</span>
  <span m='3448990'>chunks,</span> <span m='3450050'>x1</span> <span m='3450540'>up</span>
  <span m='3450640'>to</span> <span m='3450730'>xk.</span> <span m='3451120'>This</span>
  <span m='3451300'>is</span> <span m='3451390'>basically</span> <span m='3451990'>what</span>
  <span m='3452260'>round</span> <span m='3452470'>elimination</span> <span m='3453070'>tells</span>
  <span m='3453400'>me</span> <span m='3453550'>I</span> <span m='3453670'>should</span>
  <span m='3453820'>do.</span> <span m='3454120'>If</span> <span m='3454450'>I</span>
  <span m='3454570'>want to</span> <span m='3454780'>view</span> <span m='3455020'>my</span>
  <span m='3455200'>problem</span> <span m='3455530'>as</span> <span m='3455640'>an</span>
  <span m='3455710'>f</span> <span m='3455850'>to</span> <span m='3456040'>the</span>
  <span m='3456160'>k</span> <span m='3456340'>problem,</span> <span m='3457390'>somehow</span>
  <span m='3457780'>my</span> <span m='3457990'>input</span> <span m='3458950'>is</span>
  <span m='3459070'>not</span> <span m='3459280'>just</span> <span m='3459430'>one</span>
  <span m='3459640'>thing.</span> <span m='3459950'>It's</span> <span m='3459970'>k</span>
  <span m='3460150'>things.</span> </p><p><span m='3460690'>Well,</span> <span m='3461470'>in</span>
  <span m='3461620'>reality,</span> <span m='3462280'>the</span> <span m='3462370'>input</span>
  <span m='3462670'>is</span> <span m='3462850'>a</span> <span m='3462910'>single</span>
  <span m='3463210'>word.</span> <span m='3464180'>So</span> <span m='3464370'>I'm</span>
  <span m='3464500'>going to have</span> <span m='3464680'>to</span> <span m='3464770'>split</span>
  <span m='3465070'>it</span> <span m='3465160'>into</span> <span m='3465430'>sub</span>
  <span m='3465670'>words,</span> <span m='3466090'>in</span> <span m='3466210'>the</span>
  <span m='3466270'>usual</span> <span m='3466570'>way.</span> <span m='3468270'>Van
  Emde Boas</span> <span m='3469060'>would</span> <span m='3469180'>split</span> <span
  m='3469390'>it</span> <span m='3469450'>in</span> <span m='3469540'>half.</span>
  <span m='3470890'>We're</span> <span m='3471040'>going</span> <span m='3471160'>to</span>
  <span m='3471220'>split</span> <span m='3471490'>it</span> <span m='3471550'>into</span>
  <span m='3471790'>more</span> <span m='3471970'>pieces,</span> <span m='3472420'>because</span>
  <span m='3472900'>we</span> <span m='3473020'>need</span> <span m='3473140'>to</span>
  <span m='3473230'>guarantee</span> <span m='3474400'>that</span> <span m='3474610'>this</span>
  <span m='3474790'>error is</span> <span m='3475150'>small.</span> </p><p><span m='3475600'>We</span>
  <span m='3475720'>need</span> <span m='3475870'>k</span> <span m='3476140'>to</span>
  <span m='3476230'>be</span> <span m='3476350'>large</span> <span m='3477100'>for</span>
  <span m='3477190'>this</span> <span m='3477340'>error</span> <span m='3477580'>to</span>
  <span m='3477700'>be</span> <span m='3477790'>small.</span> <span m='3479740'>I</span>
  <span m='3479890'>claim</span> <span m='3480520'>this</span> <span m='3480820'>is</span>
  <span m='3480940'>the</span> <span m='3481060'>good</span> <span m='3481210'>choice</span>
  <span m='3481540'>of</span> <span m='3481630'>k.</span> <span m='3483250'>And</span>
  <span m='3483400'>so</span> <span m='3483520'>now,</span> <span m='3484030'>this</span>
  <span m='3484300'>is</span> <span m='3485060'>x1,</span> <span m='3485540'>this</span>
  <span m='3485810'>is</span> <span m='3486110'>x</span> <span m='3486500'>2x,</span>
  <span m='3487193'>this</span> <span m='3487536'>is</span> <span m='3487880'>xk.</span>
  <span m='3488890'>The</span> <span m='3488980'>low</span> <span m='3489220'>order</span>
  <span m='3489460'>bits</span> <span m='3489700'>are</span> <span m='3489790'>xk.</span>
  <span m='3489970'>The</span> <span m='3490320'>high</span> <span m='3490520'>order</span>
  <span m='3490740'>bits</span> <span m='3490940'>aer</span> <span m='3491020'>x1.</span>
  <span m='3491680'>Or</span> <span m='3491800'>the</span> <span m='3491890'>reverse,
  it</span> <span m='3492280'>doesn't</span> <span m='3492490'>actually</span> <span
  m='3492790'>matter.</span> </p><p><span m='3497470'>So</span> <span m='3497800'>why</span>
  <span m='3498100'>is</span> <span m='3498220'>this</span> <span m='3498370'>a</span>
  <span m='3498400'>good</span> <span m='3498550'>choice</span> <span m='3498880'>of</span>
  <span m='3498970'>k?</span> <span m='3499750'>Because</span> <span m='3500980'>if</span>
  <span m='3501190'>we</span> <span m='3501310'>then</span> <span m='3501610'>look</span>
  <span m='3502000'>at</span> <span m='3503050'>the</span> <span m='3503230'>error</span>
  <span m='3503560'>increase</span> <span m='3504250'>we</span> <span m='3504370'>get</span>
  <span m='3504640'>from</span> <span m='3504880'>here,</span> <span m='3506620'>error</span>
  <span m='3507170'>increase</span> <span m='3507700'>is</span> <span m='3507820'>square</span>
  <span m='3508210'>root</span> <span m='3508840'>of</span> <span m='3509000'>a</span>
  <span m='3509290'>divided</span> <span m='3509680'>by</span> <span m='3509830'>k.</span>
  <span m='3512630'>So</span> <span m='3512870'>error</span> <span m='3514140'>increase,</span>
  <span m='3516810'>which is</span> <span m='3517150'>order</span> <span m='3517900'>a</span>
  <span m='3518320'>over</span> <span m='3518620'>k,</span> <span m='3520260'>is</span>
  <span m='3520420'>going</span> <span m='3520600'>to</span> <span m='3520660'>be</span>
  <span m='3520870'>k</span> <span m='3521140'>is</span> <span m='3521260'>now</span>
  <span m='3521440'>this.</span> </p><p><span m='3522490'>So</span> <span m='3522640'>the</span>
  <span m='3522760'>a's</span> <span m='3523090'>cancel--</span> <span m='3525460'>sorry,</span>
  <span m='3525670'>square</span> <span m='3526840'>root</span> <span m='3527200'>of</span>
  <span m='3527350'>a over</span> <span m='3527590'>k.</span> <span m='3529610'>A
  over k was</span> <span m='3529780'>the</span> <span m='3529900'>wrong</span> <span
  m='3530200'>analysis.</span> <span m='3530800'>The</span> <span m='3531190'>square</span>
  <span m='3531290'>root</span> <span m='3531490'>of</span> <span m='3531610'>a over</span>
  <span m='3531860'>k is</span> <span m='3532220'>the</span> <span m='3532320'>correct</span>
  <span m='3532510'>bound.</span> <span m='3533470'>Still,</span> <span m='3533770'>the</span>
  <span m='3533890'>a's</span> <span m='3534070'>cancel,</span> <span m='3534970'>because
  the</span> <span m='3535090'>k</span> <span m='3535330'>has</span> <span m='3535510'>an</span>
  <span m='3535600'>a</span> <span m='3535750'>factor.</span> </p><p><span m='3537100'>And</span>
  <span m='3537130'>so</span> <span m='3537310'>we</span> <span m='3537430'>get</span>
  <span m='3538000'>order</span> <span m='3538870'>square</span> <span m='3539200'>root</span>
  <span m='3539860'>of</span> <span m='3540160'>1</span> <span m='3540370'>over</span>
  <span m='3540550'>t</span> <span m='3540700'>squared,</span> <span m='3542350'>also</span>
  <span m='3542650'>known</span> <span m='3542920'>as</span> <span m='3543220'>1</span>
  <span m='3543370'>over</span> <span m='3543460'>t.</span> <span m='3546560'>This</span>
  <span m='3546790'>is</span> <span m='3546910'>good.</span> <span m='3547800'>There's</span>
  <span m='3547960'>a</span> <span m='3548020'>constant</span> <span m='3548440'>here.</span>
  <span m='3549410'>And</span> <span m='3549520'>if</span> <span m='3549610'>I</span>
  <span m='3549700'>tune</span> <span m='3550550'>this</span> <span m='3550750'>constant</span>
  <span m='3551230'>correct,</span> <span m='3551980'>I</span> <span m='3552100'>can</span>
  <span m='3552220'>make</span> <span m='3552370'>this</span> <span m='3552550'>constant</span>
  <span m='3553030'>less</span> <span m='3553360'>than</span> <span m='3553660'>1/3.</span>
  </p><p><span m='3555440'>So</span> <span m='3555580'>if</span> <span m='3555700'>I</span>
  <span m='3555790'>start</span> <span m='3556090'>with</span> <span m='3556210'>a</span>
  <span m='3556270'>protocol,</span> <span m='3556750'>let's</span> <span m='3556930'>say,</span>
  <span m='3557050'>that's</span> <span m='3557230'>completely</span> <span m='3557800'>correct--</span>
  <span m='3558770'>you</span> <span m='3558870'>don't</span> <span m='3558970'>have</span>
  <span m='3559090'>to.</span> <span m='3559210'>You</span> <span m='3559300'>could</span>
  <span m='3559420'>start</span> <span m='3559600'>with</span> <span m='3559720'>one</span>
  <span m='3559900'>that's</span> <span m='3560590'>correct</span> <span m='3560830'>with</span>
  <span m='3561010'>at</span> <span m='3561130'>least</span> <span m='3561340'>probability</span>
  <span m='3561820'>3/4</span> <span m='3562420'>or</span> <span m='3562510'>something.</span>
  <span m='3563490'>But</span> <span m='3563590'>let's</span> <span m='3563650'>just</span>
  <span m='3563710'>say,</span> <span m='3564160'>for</span> <span m='3564340'>simplicity,</span>
  <span m='3565240'>the</span> <span m='3565330'>initial</span> <span m='3565630'>data</span>
  <span m='3565810'>structure</span> <span m='3566110'>is</span> <span m='3566170'>completely</span>
  <span m='3566560'>correct.</span> <span m='3567630'>If</span> <span m='3567790'>every</span>
  <span m='3568150'>time</span> <span m='3568660'>I</span> <span m='3568780'>do</span>
  <span m='3569350'>an</span> <span m='3569500'>elimination</span> <span m='3571390'>of</span>
  <span m='3571510'>a</span> <span m='3571570'>message,</span> <span m='3572090'>I</span>
  <span m='3572190'>guess</span> <span m='3572230'>I</span> <span m='3572320'>should</span>
  <span m='3572500'>set</span> <span m='3572680'>it</span> <span m='3572740'>to</span>
  <span m='3572890'>be</span> <span m='3573490'>1/6</span> <span m='3574870'>time's</span>
  <span m='3575140'>1</span> <span m='3575290'>over</span> <span m='3575490'>t,</span>
  <span m='3576190'>and</span> <span m='3576340'>I</span> <span m='3576430'>do</span>
  <span m='3576610'>this</span> <span m='3576880'>2</span> <span m='3577120'>times</span>
  <span m='3577450'>t</span> <span m='3577680'>times,</span> <span m='3579340'>in</span>
  <span m='3579460'>the</span> <span m='3579610'>end</span> <span m='3579850'>the</span>
  <span m='3580000'>error</span> <span m='3580240'>will</span> <span m='3580360'>be</span>
  <span m='3581050'>only</span> <span m='3581350'>1/3.</span> <span m='3582260'>So
  I'll</span> <span m='3582450'>be</span> <span m='3582580'>correct</span> <span m='3582940'>with</span>
  <span m='3583060'>2/3</span> <span m='3583510'>probability.</span> </p><p><span
  m='3585310'>So</span> <span m='3586240'>never</span> <span m='3586570'>mind</span>
  <span m='3586780'>the</span> <span m='3586860'>constants.</span> <span m='3587520'>I</span>
  <span m='3587590'>can</span> <span m='3587740'>set</span> <span m='3587950'>this</span>
  <span m='3588100'>constant</span> <span m='3588460'>right</span> <span m='3589210'>so</span>
  <span m='3589360'>this</span> <span m='3589600'>is</span> <span m='3589900'>some</span>
  <span m='3590170'>epsilon</span> <span m='3590680'>times</span> <span m='3590890'>1</span>
  <span m='3591040'>over</span> <span m='3591100'>t.</span> <span m='3591430'>So</span>
  <span m='3591550'>after</span> <span m='3591760'>I</span> <span m='3591820'>do</span>
  <span m='3591940'>this</span> <span m='3592090'>2</span> <span m='3592220'>t</span>
  <span m='3592400'>times,</span> <span m='3593530'>I</span> <span m='3593650'>end</span>
  <span m='3593830'>up</span> <span m='3593980'>with</span> <span m='3594160'>an</span>
  <span m='3594250'>error</span> <span m='3594550'>that's</span> <span m='3594730'>only</span>
  <span m='3595000'>epsilon,</span> <span m='3595780'>or</span> <span m='3595970'>2</span>
  <span m='3596170'>epsilon,</span> <span m='3596620'>or</span> <span m='3596710'>whatever.</span>
  <span m='3598160'>So</span> <span m='3598480'>that</span> <span m='3598690'>would</span>
  <span m='3598810'>be</span> <span m='3598900'>a</span> <span m='3598960'>contradiction.</span>
  </p><p><span m='3600070'>So</span> <span m='3600250'>that's</span> <span m='3600430'>why</span>
  <span m='3600550'>this</span> <span m='3600700'>is</span> <span m='3600820'>a</span>
  <span m='3600880'>good</span> <span m='3601030'>choice.</span> <span m='3601380'>I'm</span>
  <span m='3601450'>basically</span> <span m='3601780'>balancing</span> <span m='3602350'>the</span>
  <span m='3602440'>error</span> <span m='3602770'>I</span> <span m='3602890'>get</span>
  <span m='3603100'>from</span> <span m='3603280'>every</span> <span m='3603520'>message</span>
  <span m='3603880'>elimination.</span> <span m='3604450'>I</span> <span m='3604540'>want</span>
  <span m='3604690'>them</span> <span m='3604840'>all</span> <span m='3605080'>to</span>
  <span m='3605230'>be</span> <span m='3605350'>order</span> <span m='3605530'>1</span>
  <span m='3605660'>over</span> <span m='3605810'>t</span> <span m='3606730'>so</span>
  <span m='3606850'>it's</span> <span m='3606940'>nice</span> <span m='3607150'>and</span>
  <span m='3607240'>balanced.</span> <span m='3607990'>That</span> <span m='3608170'>will</span>
  <span m='3608260'>give</span> <span m='3608410'>me</span> <span m='3608500'>the</span>
  <span m='3608620'>best</span> <span m='3608830'>lower</span> <span m='3609070'>bound,</span>
  <span m='3609340'>it</span> <span m='3609400'>turns</span> <span m='3609670'>out.</span>
  </p><p><span m='3612220'>But</span> <span m='3612370'>what</span> <span m='3612520'>does</span>
  <span m='3612700'>this</span> <span m='3612910'>mean?</span> <span m='3613570'>I</span>
  <span m='3613630'>mean,</span> <span m='3614080'>somehow</span> <span m='3616120'>I</span>
  <span m='3616690'>have</span> <span m='3616900'>to</span> <span m='3616960'>have</span>
  <span m='3617110'>an</span> <span m='3617200'>f</span> <span m='3617500'>to the</span>
  <span m='3617620'>k</span> <span m='3617890'>problem,</span> <span m='3619030'>meaning,</span>
  <span m='3619510'>really</span> <span m='3619930'>I</span> <span m='3620020'>should</span>
  <span m='3620200'>only</span> <span m='3620470'>care</span> <span m='3620710'>about</span>
  <span m='3620950'>1xi</span> <span m='3622690'>here,</span> <span m='3623320'>that</span>
  <span m='3623500'>all</span> <span m='3623830'>the</span> <span m='3623950'>interesting</span>
  <span m='3624370'>stuff</span> <span m='3625210'>is</span> <span m='3625360'>these</span>
  <span m='3625660'>bits.</span> <span m='3626530'>But</span> <span m='3626710'>Alice</span>
  <span m='3627040'>doesn't</span> <span m='3627340'>know</span> <span m='3628060'>which</span>
  <span m='3628330'>is</span> <span m='3628510'>i.</span> <span m='3628960'>Only</span>
  <span m='3629290'>Bob</span> <span m='3629620'>knows</span> <span m='3629890'>which</span>
  <span m='3630070'>is</span> <span m='3630190'>i.</span> </p><p><span m='3630880'>What</span>
  <span m='3631000'>does</span> <span m='3631090'>that</span> <span m='3631270'>mean?</span>
  <span m='3631840'>Bob</span> <span m='3632170'>knows</span> <span m='3632650'>the</span>
  <span m='3632770'>set</span> <span m='3632980'>of</span> <span m='3633070'>elements</span>
  <span m='3633730'>in</span> <span m='3633880'>the</span> <span m='3633970'>data</span>
  <span m='3634210'>structure.</span> <span m='3636050'>So,</span> <span m='3636640'>basically,</span>
  <span m='3637180'>the</span> <span m='3637270'>set</span> <span m='3637480'>of</span>
  <span m='3637600'>elements--</span> <span m='3639220'>maybe</span> <span m='3639460'>they</span>
  <span m='3639640'>all</span> <span m='3639850'>differ</span> <span m='3640600'>in</span>
  <span m='3640810'>these</span> <span m='3641110'>bits.</span> </p><p><span m='3642040'>Or</span>
  <span m='3642340'>maybe</span> <span m='3642550'>they</span> <span m='3642640'>all</span>
  <span m='3642760'>differ</span> <span m='3642990'>in</span> <span m='3643060'>these</span>
  <span m='3643210'>bits,</span> <span m='3643480'>or</span> <span m='3643570'>these</span>
  <span m='3643750'>bits,</span> <span m='3643960'>or</span> <span m='3644050'>these</span>
  <span m='3644230'>bits,</span> <span m='3644440'>but</span> <span m='3644590'>only</span>
  <span m='3644890'>one</span> <span m='3645070'>of</span> <span m='3645190'>these.</span>
  <span m='3646520'>So</span> <span m='3646570'>that's</span> <span m='3646780'>a</span>
  <span m='3646840'>distribution</span> <span m='3647410'>of</span> <span m='3647530'>inputs.</span>
  <span m='3649430'>There's</span> <span m='3649780'>one</span> <span m='3650260'>class</span>
  <span m='3650620'>of</span> <span m='3650740'>inputs</span> <span m='3651070'>where</span>
  <span m='3651220'>they</span> <span m='3651370'>all</span> <span m='3651580'>differ</span>
  <span m='3651940'>in</span> <span m='3652090'>the</span> <span m='3652280'>x1</span>
  <span m='3652560'>part.</span> <span m='3653140'>But</span> <span m='3653290'>then</span>
  <span m='3653410'>they're</span> <span m='3653530'>identical</span> <span m='3654070'>for</span>
  <span m='3654190'>the</span> <span m='3654280'>rest.</span> </p><p><span m='3657490'>For</span>
  <span m='3658150'>each</span> <span m='3658360'>xi,</span> <span m='3659290'>there's</span>
  <span m='3659470'>a</span> <span m='3659530'>set</span> <span m='3659710'>of</span>
  <span m='3659800'>inputs</span> <span m='3660130'>where</span> <span m='3660250'>they</span>
  <span m='3660370'>all</span> <span m='3660520'>differ</span> <span m='3660820'>in</span>
  <span m='3660880'>the</span> <span m='3660980'>xi's,</span> <span m='3662110'>and</span>
  <span m='3662290'>nowhere</span> <span m='3662620'>else,</span> <span m='3662860'>let's</span>
  <span m='3662980'>say.</span> <span m='3664300'>But</span> <span m='3664450'>Alice</span>
  <span m='3664780'>doesn't</span> <span m='3665020'>know</span> <span m='3665290'>which</span>
  <span m='3666100'>setting</span> <span m='3666880'>she</span> <span m='3667150'>is</span>
  <span m='3667300'>in.</span> <span m='3668590'>Alice</span> <span m='3668890'>just</span>
  <span m='3669070'>knows</span> <span m='3669290'>x.</span> </p><p><span m='3670570'>And</span>
  <span m='3670690'>so</span> <span m='3671200'>Alice</span> <span m='3671530'>is</span>
  <span m='3671650'>kind</span> <span m='3671890'>of</span> <span m='3672010'>in</span>
  <span m='3672160'>trouble,</span> <span m='3672520'>because</span> <span m='3672880'>you</span>
  <span m='3673000'>can</span> <span m='3673150'>only</span> <span m='3673330'>send</span>
  <span m='3673600'>a</span> <span m='3673660'>few</span> <span m='3673990'>bits.</span>
  <span m='3674320'>You</span> <span m='3674410'>can</span> <span m='3674500'>only</span>
  <span m='3674620'>send</span> <span m='3674830'>a</span> <span m='3674980'>bits</span>
  <span m='3675280'>out</span> <span m='3675400'>of</span> <span m='3675490'>this</span>
  <span m='3675640'>thing.</span> <span m='3676670'>So</span> <span m='3676750'>you</span>
  <span m='3676840'>can't</span> <span m='3677500'>communicate</span> <span m='3677980'>very</span>
  <span m='3678160'>much.</span> </p><p><span m='3680230'>Let's</span> <span m='3680590'>go</span>
  <span m='3691150'>over</span> <span m='3691400'>here.</span> <span m='3692975'>I</span>
  <span m='3693400'>need the</span> <span m='3693570'>bound.</span> <span m='3694690'>I</span>
  <span m='3694750'>don't need</span> <span m='3694910'>the</span> <span m='3695000'>corollary.</span>
  <span m='3699450'>Let</span> <span m='3699560'>me</span> <span m='3699650'>draw</span>
  <span m='3699830'>a</span> <span m='3699860'>picture</span> <span m='3700160'>for</span>
  <span m='3700370'>Alice,</span> <span m='3703230'>or</span> <span m='3703400'>for</span>
  <span m='3703760'>what</span> <span m='3703970'>the</span> <span m='3704240'>data</span>
  <span m='3704570'>looks</span> <span m='3704780'>like.</span> </p><p><span m='3709360'>So</span>
  <span m='3709410'>there's</span> <span m='3709560'>some</span> <span m='3709980'>initial</span>
  <span m='3710610'>segment,</span> <span m='3711680'>which</span> <span m='3711970'>is</span>
  <span m='3712060'>shared</span> <span m='3712410'>by</span> <span m='3712560'>all</span>
  <span m='3712800'>elements.</span> <span m='3714250'>Then</span> <span m='3715290'>they</span>
  <span m='3715440'>all</span> <span m='3715680'>differ</span> <span m='3716010'>in</span>
  <span m='3716100'>this</span> <span m='3716250'>middle</span> <span m='3716520'>chunk.</span>
  <span m='3718140'>And</span> <span m='3718320'>then</span> <span m='3718560'>they</span>
  <span m='3718710'>all</span> <span m='3718860'>have--</span> <span m='3719730'>I</span>
  <span m='3719790'>don't</span> <span m='3719880'>really</span> <span m='3720090'>care</span>
  <span m='3720330'>what</span> <span m='3720450'>they</span> <span m='3720570'>have</span>
  <span m='3720780'>after</span> <span m='3721020'>that.</span> </p><p><span m='3723180'>So</span>
  <span m='3723330'>these</span> <span m='3723600'>are</span> <span m='3723720'>the</span>
  <span m='3723870'>elements</span> <span m='3724230'>in</span> <span m='3724320'>the</span>
  <span m='3724410'>data</span> <span m='3724560'>structure.</span> <span m='3727720'>And</span>
  <span m='3728640'>this</span> <span m='3728910'>is</span> <span m='3729090'>our</span>
  <span m='3729330'>usual</span> <span m='3729720'>picture</span> <span m='3730080'>of</span>
  <span m='3730200'>a</span> <span m='3730260'>binary</span> <span m='3730650'>tree.</span>
  <span m='3730860'>Except,</span> <span m='3731130'>I</span> <span m='3731170'>didn't</span>
  <span m='3731370'>draw it</span> <span m='3731580'>binary.</span> <span m='3732210'>I</span>
  <span m='3732360'>drew</span> <span m='3732570'>it</span> <span m='3732660'>with</span>
  <span m='3732900'>some</span> <span m='3733110'>branching</span> <span m='3733530'>factor</span>
  <span m='3734360'>so</span> <span m='3734630'>that</span> <span m='3734850'>the</span>
  <span m='3735210'>height</span> <span m='3735600'>of</span> <span m='3735720'>this</span>
  <span m='3735900'>tree</span> <span m='3737490'>is</span> <span m='3737730'>theta</span>
  <span m='3738590'>at</span> <span m='3739050'>squared.</span> </p><p><span m='3740820'>So</span>
  <span m='3741000'>I</span> <span m='3741120'>set</span> <span m='3741330'>the</span>
  <span m='3741480'>base</span> <span m='3742020'>of</span> <span m='3744000'>my</span>
  <span m='3744150'>representation</span> <span m='3744960'>so</span> <span m='3745110'>that</span>
  <span m='3745290'>you</span> <span m='3745410'>branch</span> <span m='3746700'>whatever,</span>
  <span m='3747030'>w</span> <span m='3747330'>divided</span> <span m='3747690'>by</span>
  <span m='3747840'>at</span> <span m='3748100'>squared</span> <span m='3748770'>here.</span>
  <span m='3748950'>That's</span> <span m='3749130'>my</span> <span m='3749280'>branching</span>
  <span m='3749640'>factor.</span> <span m='3752720'>So</span> <span m='3753980'>cool,</span>
  <span m='3754400'>that's</span> <span m='3754730'>my</span> <span m='3754940'>picture.</span>
  <span m='3755810'>And</span> <span m='3756080'>this</span> <span m='3757430'>is</span>
  <span m='3759110'>depth</span> <span m='3759470'>i.</span> </p><p><span m='3763400'>So</span>
  <span m='3763580'>Bob</span> <span m='3763940'>knows</span> <span m='3764210'>this</span>
  <span m='3764390'>picture.</span> <span m='3764870'>Bob</span> <span m='3765170'>knows</span>
  <span m='3765470'>what</span> <span m='3765590'>all</span> <span m='3765710'>the</span>
  <span m='3765830'>elements</span> <span m='3766190'>are</span> <span m='3766370'>so</span>
  <span m='3766600'>it</span> <span m='3766670'>can</span> <span m='3766820'>build</span>
  <span m='3767060'>this</span> <span m='3767210'>picture</span> <span m='3767560'>or</span>
  <span m='3767600'>whatever.</span> <span m='3769220'>Bob</span> <span m='3769550'>knows</span>
  <span m='3770840'>which</span> <span m='3771140'>is</span> <span m='3771320'>the</span>
  <span m='3771410'>relevant</span> <span m='3771740'>depth</span> <span m='3772010'>that</span>
  <span m='3772130'>they</span> <span m='3772250'>differ.</span> <span m='3773270'>But</span>
  <span m='3773570'>in</span> <span m='3773720'>the</span> <span m='3773810'>lower</span>
  <span m='3774020'>bound,</span> <span m='3774320'>we're</span> <span m='3774410'>going</span>
  <span m='3774530'>to</span> <span m='3774590'>say</span> <span m='3774870'>a</span>
  <span m='3775070'>is</span> <span m='3775190'>chosen</span> <span m='3775580'>uniformly</span>
  <span m='3776090'>at</span> <span m='3776150'>random.</span> </p><p><span m='3777180'>So</span>
  <span m='3777350'>Alice</span> <span m='3777680'>has</span> <span m='3777890'>no</span>
  <span m='3778100'>idea</span> <span m='3779450'>which</span> <span m='3779780'>bits</span>
  <span m='3780020'>to</span> <span m='3780140'>send.</span> <span m='3781100'>And</span>
  <span m='3781190'>so</span> <span m='3781400'>probably,</span> <span m='3782490'>Alice</span>
  <span m='3782720'>is</span> <span m='3782780'>going</span> <span m='3782900'>to</span>
  <span m='3782960'>say,</span> <span m='3783200'>oh,</span> <span m='3784580'>here,</span>
  <span m='3785360'>I</span> <span m='3785480'>know</span> <span m='3785630'>these</span>
  <span m='3785840'>bits.</span> <span m='3786170'>But</span> <span m='3786320'>Bob</span>
  <span m='3786560'>already</span> <span m='3786740'>knew</span> <span m='3786860'>those</span>
  <span m='3787040'>bits. So</span> <span m='3787330'>Bob</span> <span m='3787610'>learned</span>
  <span m='3787820'>nothing.</span> <span m='3788720'>And</span> <span m='3788840'>so</span>
  <span m='3789140'>that's</span> <span m='3789440'>why</span> <span m='3789650'>you</span>
  <span m='3789800'>can</span> <span m='3789950'>eliminate</span> <span m='3790280'>the</span>
  <span m='3790370'>round.</span> <span m='3791060'>That's</span> <span m='3791210'>the</span>
  <span m='3791300'>intuition,</span> <span m='3791780'>anyway.</span> </p><p><span
  m='3792740'>The</span> <span m='3792860'>proof</span> <span m='3793130'>is,</span>
  <span m='3793340'>well,</span> <span m='3793640'>you</span> <span m='3793700'>just</span>
  <span m='3793850'>apply</span> <span m='3794120'>round</span> <span m='3794330'>elimination.</span>
  <span m='3796150'>You</span> <span m='3796310'>see</span> <span m='3796520'>that</span>
  <span m='3796890'>the</span> <span m='3797030'>problem</span> <span m='3797600'>now</span>
  <span m='3797930'>becomes</span> <span m='3799100'>to</span> <span m='3799220'>compute</span>
  <span m='3800120'>predecessor</span> <span m='3800780'>on</span> <span m='3800960'>this</span>
  <span m='3801170'>node.</span> <span m='3801890'>Just</span> <span m='3802070'>like</span>
  <span m='3802220'>in</span> <span m='3802310'>fusion</span> <span m='3802670'>tries,</span>
  <span m='3803510'>at</span> <span m='3803660'>every</span> <span m='3804290'>step</span>
  <span m='3804620'>of</span> <span m='3804680'>the</span> <span m='3804800'>way,</span>
  <span m='3805100'>the</span> <span m='3805220'>hard</span> <span m='3805370'>part</span>
  <span m='3805550'>was</span> <span m='3805730'>to</span> <span m='3805850'>compute</span>
  <span m='3806210'>predecessor</span> <span m='3807140'>at</span> <span m='3807320'>the</span>
  <span m='3807410'>node.</span> </p><p><span m='3808710'>Here,</span> <span m='3810710'>if</span>
  <span m='3810830'>Bob</span> <span m='3811070'>is</span> <span m='3811190'>allowed</span>
  <span m='3811490'>to</span> <span m='3811610'>do</span> <span m='3811730'>computation,</span>
  <span m='3813140'>then,</span> <span m='3813290'>really,</span> <span m='3814250'>Alice</span>
  <span m='3814610'>just</span> <span m='3814760'>needs</span> <span m='3814970'>to</span>
  <span m='3815060'>say,</span> <span m='3815870'>what</span> <span m='3816740'>are</span>
  <span m='3816830'>the</span> <span m='3816920'>things</span> <span m='3817190'>here?</span>
  <span m='3817460'>Or together,</span> <span m='3817940'>Alice</span> <span m='3818180'>and</span>
  <span m='3818270'>Bob</span> <span m='3818480'>somehow</span> <span m='3818870'>have</span>
  <span m='3819050'>to</span> <span m='3819110'>figure</span> <span m='3819350'>out,</span>
  <span m='3819830'>what</span> <span m='3820040'>is</span> <span m='3820190'>the</span>
  <span m='3820280'>predecessor</span> <span m='3820880'>at</span> <span m='3821120'>this</span>
  <span m='3821270'>node</span> <span m='3821660'>of</span> <span m='3821980'>xi?</span>
  <span m='3823460'>Which</span> <span m='3823670'>way</span> <span m='3824060'>the</span>
  <span m='3824210'>query</span> <span m='3824570'>goes,</span> <span m='3824870'>which</span>
  <span m='3825020'>could</span> <span m='3825200'>be</span> <span m='3825320'>in</span>
  <span m='3825440'>between</span> <span m='3825860'>one</span> <span m='3825980'>of</span>
  <span m='3826040'>these,</span> <span m='3826280'>that</span> <span m='3826520'>is</span>
  <span m='3826700'>xi.</span> </p><p><span m='3828290'>The</span> <span m='3828380'>rest</span>
  <span m='3828680'>of</span> <span m='3830000'>the</span> <span m='3830090'>xj's</span>
  <span m='3830600'>don't</span> <span m='3830840'>matter.</span> <span m='3831650'>Only</span>
  <span m='3831980'>xi</span> <span m='3832340'>matters.</span> <span m='3833420'>And</span>
  <span m='3833510'>so</span> <span m='3833810'>the</span> <span m='3833930'>problem</span>
  <span m='3834230'>reduces</span> <span m='3834680'>to</span> <span m='3834770'>computing</span>
  <span m='3835100'>predecessor</span> <span m='3835670'>here.</span> <span m='3836450'>And</span>
  <span m='3836570'>that</span> <span m='3836810'>matches</span> <span m='3837350'>the</span>
  <span m='3837470'>definition</span> <span m='3838100'>of</span> <span m='3838340'>f</span>
  <span m='3838490'>to</span> <span m='3838640'>the k.</span> </p><p><span m='3839280'>So</span>
  <span m='3839390'>we</span> <span m='3839540'>have</span> <span m='3839630'>successfully</span>
  <span m='3840350'>set</span> <span m='3840560'>up</span> <span m='3840800'>an</span>
  <span m='3840890'>f</span> <span m='3841100'>to</span> <span m='3841190'>the</span>
  <span m='3841310'>k</span> <span m='3841490'>problem.</span> <span m='3842195'>The</span>
  <span m='3842480'>only</span> <span m='3842780'>thing</span> <span m='3842990'>you</span>
  <span m='3843080'>need</span> <span m='3843260'>to</span> <span m='3843380'>do</span>
  <span m='3843950'>to</span> <span m='3844040'>solve</span> <span m='3844310'>the</span>
  <span m='3844430'>overall</span> <span m='3844790'>predecessor</span> <span m='3845330'>problem</span>
  <span m='3846050'>is</span> <span m='3846170'>to</span> <span m='3846260'>find</span>
  <span m='3846530'>your</span> <span m='3846620'>predecessor</span> <span m='3847160'>in</span>
  <span m='3847280'>the</span> <span m='3847400'>node,</span> <span m='3848060'>because</span>
  <span m='3848240'>there's</span> <span m='3848360'>only</span> <span m='3848720'>one</span>
  <span m='3849080'>element</span> <span m='3849530'>within</span> <span m='3849830'>each</span>
  <span m='3850010'>subtree</span> <span m='3851240'>that's</span> <span m='3851480'>enough</span>
  <span m='3851840'>to</span> <span m='3851900'>figure</span> <span m='3852170'>out</span>
  <span m='3852290'>your</span> <span m='3852440'>overall</span> <span m='3852830'>predecessor.</span>
  </p><p><span m='3861900'>OK,</span> <span m='3863560'>depth</span> <span m='3863890'>i,</span>
  <span m='3864220'>at</span> <span m='3864530'>squared,</span> <span m='3867940'>I
  guess</span> <span m='3868180'>you</span> <span m='3868270'>can</span> <span m='3868390'>think</span>
  <span m='3868570'>of</span> <span m='3868660'>this</span> <span m='3868870'>as</span>
  <span m='3868990'>y.</span> <span m='3871180'>That's</span> <span m='3871570'>the</span>
  <span m='3871690'>part</span> <span m='3873100'>that</span> <span m='3873190'>Bob</span>
  <span m='3873490'>knows.</span> <span m='3873970'>These</span> <span m='3874240'>are,</span>
  <span m='3874330'>in</span> <span m='3874420'>some</span> <span m='3874630'>sense,</span>
  <span m='3875110'>xi</span> <span m='3876450'>up</span> <span m='3876610'>to</span>
  <span m='3876700'>xk</span> <span m='3877200'>minus</span> <span m='3877540'>1.</span>
  </p><p><span m='3879610'>And this</span> <span m='3879790'>is</span> <span m='3879940'>why</span>
  <span m='3880210'>we</span> <span m='3880390'>had</span> <span m='3880570'>to</span>
  <span m='3880690'>say</span> <span m='3880930'>over</span> <span m='3881140'>here</span>
  <span m='3881800'>that</span> <span m='3881950'>Bob</span> <span m='3882370'>already</span>
  <span m='3882880'>knew</span> <span m='3883870'>xi</span> <span m='3884470'>up</span>
  <span m='3884650'>to</span> <span m='3884740'>xi</span> <span m='3885070'>minus</span>
  <span m='3885370'>1,</span> <span m='3886795'>because</span> <span m='3888040'>Bob</span>
  <span m='3888400'>already</span> <span m='3888670'>knows</span> <span m='3889120'>that</span>
  <span m='3889540'>the</span> <span m='3889660'>shared</span> <span m='3890140'>prefix</span>
  <span m='3890650'>among</span> <span m='3890950'>all</span> <span m='3891130'>the</span>
  <span m='3891250'>items--</span> <span m='3892410'>sorry,</span> <span m='3893470'>not</span>
  <span m='3893800'>minus</span> <span m='3893920'>1,</span> <span m='3894120'>i</span>
  <span m='3894320'>minus</span> <span m='3894610'>i.</span> <span m='3898630'>And</span>
  <span m='3898960'>so</span> <span m='3899350'>all</span> <span m='3899560'>the</span>
  <span m='3899680'>content</span> <span m='3900220'>is</span> <span m='3900400'>here</span>
  <span m='3900670'>in</span> <span m='3900880'>this</span> <span m='3901030'>node,</span>
  <span m='3901810'>which</span> <span m='3901930'>is</span> <span m='3902020'>y.</span>
  <span m='3902990'>And</span> <span m='3903100'>so</span> <span m='3903370'>it</span>
  <span m='3904030'>reduces</span> <span m='3904510'>to</span> <span m='3904690'>a</span>
  <span m='3904780'>regular</span> <span m='3905230'>predecessor</span> <span m='3905770'>problem,</span>
  <span m='3906200'>which</span> <span m='3906280'>is</span> <span m='3906370'>what</span>
  <span m='3906520'>f</span> <span m='3906750'>will</span> <span m='3906890'>always</span>
  <span m='3907180'>denote,</span> <span m='3907540'>colored</span> <span m='3907810'>predecessor</span>
  <span m='3908830'>of</span> <span m='3909050'>xi,</span> <span m='3909430'>y.</span>
  </p><p><span m='3911840'>Cool.</span> <span m='3914710'>OK,</span> <span m='3914950'>what</span>
  <span m='3915220'>happens</span> <span m='3915700'>here</span> <span m='3917320'>in</span>
  <span m='3917470'>terms</span> <span m='3917770'>of</span> <span m='3917910'>n</span>
  <span m='3918070'>and</span> <span m='3918230'>w?</span> <span m='3918600'>We</span>
  <span m='3918730'>have</span> <span m='3918850'>a</span> <span m='3918880'>smaller</span>
  <span m='3919300'>problem</span> <span m='3919750'>here.</span> <span m='3920110'>We</span>
  <span m='3920200'>threw</span> <span m='3920440'>away</span> <span m='3920710'>all</span>
  <span m='3920830'>this</span> <span m='3920960'>stuff.</span> <span m='3923490'>What</span>
  <span m='3923830'>got</span> <span m='3924070'>reduced</span> <span m='3925240'>is</span>
  <span m='3925390'>our</span> <span m='3925540'>word</span> <span m='3925840'>size</span>
  <span m='3927180'>for</span> <span m='3927420'>here.</span> </p><p><span m='3928180'>We</span>
  <span m='3928270'>started</span> <span m='3928660'>with</span> <span m='3928810'>something</span>
  <span m='3929200'>of</span> <span m='3929280'>size</span> <span m='3930280'>w</span>
  <span m='3930640'>prime.</span> <span m='3932300'>And</span> <span m='3932320'>now,</span>
  <span m='3932560'>we</span> <span m='3932710'>end</span> <span m='3932860'>up</span>
  <span m='3932980'>with</span> <span m='3933070'>something</span> <span m='3933460'>of</span>
  <span m='3933550'>this</span> <span m='3933730'>size,</span> <span m='3934280'>which</span>
  <span m='3934390'>was</span> <span m='3935180'>W</span> <span m='3935410'>prime</span>
  <span m='3935740'>divided</span> <span m='3936130'>by</span> <span m='3936350'>at</span>
  <span m='3936700'>squared</span> <span m='3939130'>up</span> <span m='3939280'>to</span>
  <span m='3939460'>theta.</span> <span m='3941770'>So</span> <span m='3942670'>this</span>
  <span m='3943060'>reduction</span> <span m='3945010'>reduces--</span> <span m='3947260'>or
  this</span> <span m='3947590'>round</span> <span m='3947860'>elimination</span>
  <span m='3948970'>reduces</span> <span m='3949480'>w</span> <span m='3949810'>prime</span>
  <span m='3950830'>to</span> <span m='3951310'>w</span> <span m='3951760'>prime,</span>
  <span m='3952270'>divided</span> <span m='3952660'>by</span> <span m='3953030'>at</span>
  <span m='3953260'>squared,</span> <span m='3954390'>theta</span> <span m='3954790'>that.</span>
  <span m='3961180'>I</span> <span m='3961560'>think that's</span> <span m='3961960'>all</span>
  <span m='3962100'>I</span> <span m='3962410'>need to</span> <span m='3962500'>say</span>
  <span m='3962680'>at</span> <span m='3962770'>this</span> <span m='3962920'>point.</span>
  </p><p><span m='3965680'>The</span> <span m='3965830'>claim</span> <span m='3966130'>is</span>
  <span m='3966370'>that</span> <span m='3966730'>this</span> <span m='3967030'>picture</span>
  <span m='3968110'>is</span> <span m='3968260'>kind</span> <span m='3968650'>of</span>
  <span m='3968770'>like</span> <span m='3969010'>Van Emde Boas</span> <span m='3970780'>in</span>
  <span m='3970930'>the</span> <span m='3971020'>following</span> <span m='3971380'>sense.</span>
  <span m='3971870'>Van Emde Boas</span> <span m='3973450'>is,</span> <span m='3973600'>essentially,</span>
  <span m='3974080'>binary</span> <span m='3974500'>searching</span> <span m='3975040'>on</span>
  <span m='3975490'>which</span> <span m='3975730'>level</span> <span m='3976120'>matters.</span>
  <span m='3977350'>If</span> <span m='3977740'>it</span> <span m='3977830'>goes</span>
  <span m='3978040'>too</span> <span m='3978220'>low,</span> <span m='3978600'>things</span>
  <span m='3978820'>are</span> <span m='3978910'>empty.</span> <span m='3979450'>If</span>
  <span m='3979700'>it</span> <span m='3979990'>goes</span> <span m='3980200'>too</span>
  <span m='3980350'>high,</span> <span m='3980650'>there's</span> <span m='3980800'>too</span>
  <span m='3980920'>many</span> <span m='3981130'>items.</span> </p><p><span m='3981650'>So</span>
  <span m='3981800'>it's</span> <span m='3981880'>binary</span> <span m='3982210'>searching</span>
  <span m='3982570'>for</span> <span m='3982660'>that</span> <span m='3982840'>critical</span>
  <span m='3983200'>point,</span> <span m='3983470'>where</span> <span m='3983590'>you</span>
  <span m='3983710'>basically</span> <span m='3985930'>have</span> <span m='3986080'>a</span>
  <span m='3986110'>node</span> <span m='3986380'>and</span> <span m='3986470'>nothing</span>
  <span m='3986740'>else.</span> <span m='3988360'>And</span> <span m='3988450'>that's</span>
  <span m='3988630'>why</span> <span m='3988740'>it</span> <span m='3988800'>took</span>
  <span m='3989000'>log</span> <span m='3989340'>w.</span> <span m='3990550'>So</span>
  <span m='3990700'>here,</span> <span m='3991370'>one</span> <span m='3991720'>level</span>
  <span m='3992050'>matters.</span> </p><p><span m='3993340'>And</span> <span m='3993820'>the</span>
  <span m='3993970'>goal</span> <span m='3994360'>is</span> <span m='3994480'>to</span>
  <span m='3994600'>figure</span> <span m='3994870'>out</span> <span m='3994990'>which</span>
  <span m='3995200'>one.</span> <span m='3996190'>And</span> <span m='3996730'>it's</span>
  <span m='3996880'>not</span> <span m='3997060'>exactly</span> <span m='3997420'>binary</span>
  <span m='3997750'>search</span> <span m='3998020'>here.</span> <span m='3998230'>We're</span>
  <span m='3998350'>losing</span> <span m='3998650'>a</span> <span m='3998710'>larger</span>
  <span m='3999070'>factor,</span> <span m='3999430'>at</span> <span m='3999730'>squared,</span>
  <span m='4000540'>at</span> <span m='4000660'>each</span> <span m='4000780'>step.</span>
  <span m='4001090'>So</span> <span m='4001110'>we're</span> <span m='4001200'>not</span>
  <span m='4001320'>reducing</span> <span m='4001650'>w to</span> <span m='4002095'>w
  over</span> <span m='4002540'>2,</span> <span m='4003300'>like</span> <span m='4003480'>we</span>
  <span m='4003570'>did</span> <span m='4003720'>with</span> <span m='4003950'>Van
  Emde Boas.</span> <span m='4004830'>But</span> <span m='4005180'>this</span> <span
  m='4005410'>is</span> <span m='4005520'>why</span> <span m='4005670'>we're</span>
  <span m='4005790'>losing</span> <span m='4006060'>a</span> <span m='4006120'>little</span>
  <span m='4006300'>bit.</span> <span m='4006500'>We</span> <span m='4006660'>reduce</span>
  <span m='4007020'>by</span> <span m='4007290'>a</span> <span m='4007320'>factor</span>
  <span m='4007710'>of</span> <span m='4007800'>at</span> <span m='4008100'>squared.</span>
  </p><p><span m='4009430'>So</span> <span m='4009510'>it's</span> <span m='4009630'>kind</span>
  <span m='4010020'>of</span> <span m='4010110'>like</span> <span m='4010320'>the</span>
  <span m='4010500'>Van Emde Boas</span> <span m='4011130'>upper</span> <span m='4011370'>bound.</span>
  <span m='4011680'>But</span> <span m='4011820'>here,</span> <span m='4012120'>we're</span>
  <span m='4012240'>setting</span> <span m='4012600'>up</span> <span m='4013290'>a</span>
  <span m='4013350'>lower</span> <span m='4013620'>bound</span> <span m='4013860'>picture</span>
  <span m='4014190'>so</span> <span m='4014400'>that--</span> <span m='4015240'>this</span>
  <span m='4015690'>is</span> <span m='4015780'>still</span> <span m='4015990'>an</span>
  <span m='4016080'>arbitrary</span> <span m='4016530'>predecessor</span> <span m='4017040'>problem.</span>
  <span m='4017520'>But</span> <span m='4017670'>figuring</span> <span m='4018030'>out</span>
  <span m='4018150'>which</span> <span m='4018360'>level</span> <span m='4018630'>matters,</span>
  <span m='4019560'>that's</span> <span m='4019860'>tricky.</span> <span m='4020550'>And</span>
  <span m='4020700'>you</span> <span m='4020760'>really</span> <span m='4021000'>can't</span>
  <span m='4021240'>do</span> <span m='4021360'>much</span> <span m='4021570'>better</span>
  <span m='4021810'>than</span> <span m='4022710'>Van Emde Boas</span> <span m='4022880'>to</span>
  <span m='4023350'>style a</span> <span m='4023850'>binary</span> <span m='4024180'>search.</span>
  <span m='4025080'>OK,</span> <span m='4025260'>maybe</span> <span m='4025530'>you</span>
  <span m='4025590'>can</span> <span m='4025710'>do</span> <span m='4025800'>at</span>
  <span m='4026130'>squared</span> <span m='4027060'>wave</span> <span m='4027360'>binary</span>
  <span m='4027990'>search,</span> <span m='4028740'>instead</span> <span m='4028950'>of</span>
  <span m='4029010'>binary</span> <span m='4029310'>search.</span> </p><p><span m='4032040'>So</span>
  <span m='4032190'>that</span> <span m='4032340'>was</span> <span m='4032620'>eliminating
  a</span> <span m='4033040'>message</span> <span m='4033360'>from</span> <span m='4033510'>Alice</span>
  <span m='4033780'>to</span> <span m='4033870'>Bob.</span> <span m='4034340'>Eliminating</span>
  <span m='4034760'>a</span> <span m='4034860'>message</span> <span m='4035190'>from</span>
  <span m='4035370'>Bob</span> <span m='4035580'>to</span> <span m='4035670'>Alice</span>
  <span m='4036090'>is</span> <span m='4036180'>going</span> <span m='4036280'>to</span>
  <span m='4036380'>look</span> <span m='4036540'>like</span> <span m='4036720'>fusion</span>
  <span m='4037050'>trees.</span> <span m='4038370'>That's</span> <span m='4038580'>the</span>
  <span m='4038670'>cool</span> <span m='4038880'>thing.</span> <span m='4041520'>So</span>
  <span m='4041970'>let's</span> <span m='4042180'>do</span> <span m='4042300'>that.</span>
  <span m='4055240'>Next</span> <span m='4055540'>page.</span> </p><p><span m='4075490'>OK,</span>
  <span m='4077100'>let's</span> <span m='4077340'>suppose--</span> <span m='4079110'>so</span>
  <span m='4080220'>this</span> <span m='4080430'>is</span> <span m='4080520'>going</span>
  <span m='4080670'>to</span> <span m='4080730'>get</span> <span m='4080880'>slightly</span>
  <span m='4081240'>confusing</span> <span m='4081690'>notationally,</span> <span
  m='4082260'>because</span> <span m='4082530'>you</span> <span m='4082590'>have</span>
  <span m='4082680'>to</span> <span m='4082770'>reverse</span> <span m='4083190'>a
  and</span> <span m='4083520'>b.</span> <span m='4084690'>The</span> <span m='4084840'>picture</span>
  <span m='4085170'>I</span> <span m='4085260'>set</span> <span m='4085500'>up</span>
  <span m='4086340'>over</span> <span m='4086580'>here,</span> <span m='4087480'>and</span>
  <span m='4087750'>for</span> <span m='4087930'>the</span> <span m='4088020'>round</span>
  <span m='4088260'>elimination</span> <span m='4088830'>lamma</span> <span m='4089150'>f</span>
  <span m='4089450'>to</span> <span m='4089610'>the</span> <span m='4089730'>k,</span>
  <span m='4091020'>and</span> <span m='4092180'>round</span> <span m='4092410'>elimination</span>
  <span m='4092910'>lamma,</span> <span m='4093210'>are</span> <span m='4093390'>all</span>
  <span m='4093540'>phrased</span> <span m='4094050'>in</span> <span m='4094140'>terms</span>
  <span m='4094410'>of</span> <span m='4094740'>eliminating</span> <span m='4095130'>the</span>
  <span m='4095250'>Alice</span> <span m='4095550'>to</span> <span m='4095670'>Bob</span>
  <span m='4095880'>message.</span> <span m='4096720'>You've</span> <span m='4096840'>got</span>
  <span m='4096990'>to</span> <span m='4097080'>invert</span> <span m='4097380'>everything.</span>
  </p><p><span m='4097800'>So</span> <span m='4097950'>we're</span> <span m='4098040'>going</span>
  <span m='4098160'>to</span> <span m='4098250'>get</span> <span m='4098660'>square</span>
  <span m='4098760'>root</span> <span m='4099090'>of</span> <span m='4099149'>b</span>
  <span m='4099330'>over</span> <span m='4099630'>k</span> <span m='4099920'>error</span>
  <span m='4100950'>if</span> <span m='4101069'>I</span> <span m='4101130'>don't</span>
  <span m='4101520'>relabel</span> <span m='4102090'>things.</span> <span m='4103020'>So</span>
  <span m='4103109'>you</span> <span m='4103200'>can</span> <span m='4103350'>restate</span>
  <span m='4103710'>this,</span> <span m='4104069'>if</span> <span m='4104399'>Bob</span>
  <span m='4104760'>speaks</span> <span m='4105090'>first,</span> <span m='4105479'>and</span>
  <span m='4105569'>then</span> <span m='4105720'>Alice</span> <span m='4105990'>speaks</span>
  <span m='4106229'>next,</span> <span m='4107060'>I</span> <span m='4107189'>get</span>
  <span m='4107340'>square</span> <span m='4107680'>root</span> <span m='4107790'>of</span>
  <span m='4107880'>b</span> <span m='4108060'>over</span> <span m='4108240'>k</span>
  <span m='4108490'>error.</span> <span m='4110399'>The</span> <span m='4110490'>F</span>
  <span m='4110700'>to</span> <span m='4110819'>the</span> <span m='4110910'>k</span>
  <span m='4111180'>problem</span> <span m='4111750'>is</span> <span m='4111899'>now</span>
  <span m='4112080'>that</span> <span m='4112260'>Bob</span> <span m='4112710'>has</span>
  <span m='4112979'>k</span> <span m='4113220'>inputs.</span> </p><p><span m='4114330'>Maybe</span>
  <span m='4114510'>call</span> <span m='4114689'>them</span> <span m='4114810'>y1</span>
  <span m='4115350'>to</span> <span m='4115500'>yk.</span> <span m='4117569'>Alice</span>
  <span m='4118050'>has</span> <span m='4118290'>an</span> <span m='4118380'>input</span>
  <span m='4118710'>x</span> <span m='4119279'>and</span> <span m='4119580'>the</span>
  <span m='4119729'>integer</span> <span m='4120149'>i.</span> <span m='4120550'>So</span>
  <span m='4121380'>now</span> <span m='4121830'>Alice,</span> <span m='4122460'>the</span>
  <span m='4122580'>querier,</span> <span m='4123270'>knows</span> <span m='4123540'>what</span>
  <span m='4123689'>i</span> <span m='4123910'>is.</span> <span m='4124189'>But</span>
  <span m='4124319'>Bob</span> <span m='4124590'>doesn't.</span> <span m='4125250'>The</span>
  <span m='4125340'>data</span> <span m='4125520'>structure</span> <span m='4125850'>doesn't</span>
  <span m='4126120'>know</span> <span m='4126270'>it.</span> <span m='4127200'>So</span>
  <span m='4127319'>it</span> <span m='4127399'>just</span> <span m='4127590'>reversed</span>
  <span m='4127920'>everything.</span> </p><p><span m='4128850'>So</span> <span m='4129060'>let</span>
  <span m='4129149'>me</span> <span m='4129840'>state</span> <span m='4130229'>it</span>
  <span m='4131040'>over</span> <span m='4131220'>here.</span> <span m='4132180'>Bob</span>
  <span m='4133470'>has</span> <span m='4133859'>input.</span> <span m='4135330'>Now,</span>
  <span m='4135510'>in</span> <span m='4135600'>general,</span> <span m='4137189'>what</span>
  <span m='4137370'>Bob</span> <span m='4137609'>knows</span> <span m='4137910'>is</span>
  <span m='4138029'>a</span> <span m='4138090'>bunch</span> <span m='4138300'>of</span>
  <span m='4138390'>integers,</span> <span m='4138750'>n</span> <span m='4138930'>integers.</span>
  <span m='4139380'>In</span> <span m='4139470'>general,</span> <span m='4139920'>n</span>
  <span m='4140100'>prime</span> <span m='4140430'>integers,</span> <span m='4140910'>because</span>
  <span m='4141130'>n</span> <span m='4141270'>is</span> <span m='4141390'>also</span>
  <span m='4141600'>going</span> <span m='4141779'>to</span> <span m='4141870'>increase.</span>
  </p><p><span m='4144390'>And</span> <span m='4145450'>let's</span> <span m='4145649'>say</span>
  <span m='4145920'>each</span> <span m='4146160'>of</span> <span m='4146220'>them</span>
  <span m='4147270'>is</span> <span m='4147450'>w</span> <span m='4147840'>prime</span>
  <span m='4148319'>bits.</span> <span m='4149970'>That's</span> <span m='4150149'>what</span>
  <span m='4150270'>Bob</span> <span m='4150569'>knows.</span> <span m='4151859'>That's</span>
  <span m='4152189'>y.</span> </p><p><span m='4156029'>So</span> <span m='4156479'>what</span>
  <span m='4156689'>do</span> <span m='4156750'>we</span> <span m='4156899'>have</span>
  <span m='4157080'>to</span> <span m='4157200'>do</span> <span m='4157380'>to</span>
  <span m='4157500'>phrase</span> <span m='4157830'>an</span> <span m='4157910'>f</span>
  <span m='4158109'>to</span> <span m='4158250'>the k</span> <span m='4158490'>problem?</span>
  <span m='4159420'>Well,</span> <span m='4159540'>just</span> <span m='4159720'>like</span>
  <span m='4159870'>this,</span> <span m='4160109'>we've</span> <span m='4160260'>got</span>
  <span m='4160380'>to</span> <span m='4160470'>break</span> <span m='4160770'>that</span>
  <span m='4160950'>input</span> <span m='4161760'>into</span> <span m='4163380'>bt</span>
  <span m='4163840'>squared</span> <span m='4164729'>equal-sized</span> <span m='4165330'>chunks.</span>
  <span m='4166630'>So</span> <span m='4166950'>let's just</span> <span m='4167069'>think</span>
  <span m='4167279'>about</span> <span m='4167520'>what</span> <span m='4167670'>that</span>
  <span m='4167850'>means.</span> </p><p><span m='4184970'>So</span> <span m='4185790'>it's</span>
  <span m='4185910'>going</span> <span m='4186020'>to</span> <span m='4186090'>be</span>
  <span m='4186210'>y1</span> <span m='4188010'>up to</span> <span m='4188310'>yk.</span>
  <span m='4190499'>k</span> <span m='4191670'>is</span> <span m='4191979'>theta</span>
  <span m='4192189'>bt</span> <span m='4192510'>squared.</span> <span m='4193479'>Again,</span>
  <span m='4193590'>we</span> <span m='4193710'>want</span> <span m='4193930'>bt</span>
  <span m='4194250'>squared,</span> <span m='4194580'>because</span> <span m='4194850'>then</span>
  <span m='4195000'>you</span> <span m='4195090'>plug</span> <span m='4195330'>it</span>
  <span m='4195420'>into</span> <span m='4195630'>this</span> <span m='4195940'>root</span>
  <span m='4196200'>b</span> <span m='4196440'>over</span> <span m='4196650'>k</span>
  <span m='4196890'>formula.</span> <span m='4197910'>And</span> <span m='4198120'>you</span>
  <span m='4198240'>get</span> <span m='4199680'>that</span> <span m='4200060'>the</span>
  <span m='4200330'>error</span> <span m='4200640'>increase</span> <span m='4203430'>is</span>
  <span m='4204180'>order</span> <span m='4204570'>1 over</span> <span m='4204930'>t,</span>
  <span m='4206610'>which</span> <span m='4206790'>is</span> <span m='4206880'>what</span>
  <span m='4207030'>we</span> <span m='4207150'>need</span> <span m='4207360'>to</span>
  <span m='4207510'>do</span> <span m='4207660'>t</span> <span m='4208010'>round</span>
  <span m='4208260'>eliminations.</span> </p><p><span m='4211180'>So</span> <span
  m='4212800'>before,</span> <span m='4213290'>our</span> <span m='4213420'>input
  was</span> <span m='4213570'>a</span> <span m='4213630'>single</span> <span m='4213930'>word.</span>
  <span m='4214180'>Now,</span> <span m='4214440'>our</span> <span m='4214530'>input</span>
  <span m='4214860'>is</span> <span m='4214950'>a</span> <span m='4215040'>whole</span>
  <span m='4215370'>bunch</span> <span m='4215730'>of</span> <span m='4215820'>integers.</span>
  <span m='4216880'>So</span> <span m='4216980'>it's</span> <span m='4217080'>natural</span>
  <span m='4217350'>to</span> <span m='4217590'>split</span> <span m='4218010'>it</span>
  <span m='4218130'>up</span> <span m='4218790'>into</span> <span m='4219030'>different</span>
  <span m='4219420'>integers.</span> <span m='4224620'>Here's</span> <span m='4224760'>how</span>
  <span m='4224910'>I'm</span> <span m='4225000'>going</span> <span m='4225240'>to</span>
  <span m='4225360'>do</span> <span m='4225540'>that.</span> </p><p><span m='4230000'>I'll
  just</span> <span m='4230260'>draw</span> <span m='4230470'>the</span> <span m='4230550'>picture</span>
  <span m='4231480'>over</span> <span m='4231930'>here.</span> <span m='4232630'>So</span>
  <span m='4232680'>this</span> <span m='4232890'>was</span> <span m='4233130'>the</span>
  <span m='4234030'>Alice</span> <span m='4234330'>to</span> <span m='4234450'>Bob</span>
  <span m='4236280'>elimination.</span> <span m='4238020'>Now,</span> <span m='4238080'>we'll</span>
  <span m='4238310'>do</span> <span m='4238500'>the</span> <span m='4238620'>Bob</span>
  <span m='4239040'>to</span> <span m='4239970'>Alice</span> <span m='4241290'>picture.</span>
  </p><p><span m='4244980'>So</span> <span m='4245370'>what</span> <span m='4245580'>I'd</span>
  <span m='4245670'>like</span> <span m='4245820'>to</span> <span m='4245880'>do</span>
  <span m='4246000'>is</span> <span m='4246060'>split</span> <span m='4246540'>up</span>
  <span m='4246720'>all</span> <span m='4246840'>the</span> <span m='4246990'>inputs.</span>
  <span m='4247650'>What's</span> <span m='4247890'>the</span> <span m='4247980'>natural</span>
  <span m='4248250'>way</span> <span m='4248340'>to</span> <span m='4248430'>do</span>
  <span m='4248550'>that?</span> <span m='4248760'>Well,</span> <span m='4248950'>have</span>
  <span m='4250170'>a</span> <span m='4250260'>tree</span> <span m='4250560'>at</span>
  <span m='4250650'>the</span> <span m='4250770'>top.</span> <span m='4253520'>Let's</span>
  <span m='4253680'>just</span> <span m='4253830'>make</span> <span m='4254010'>it</span>
  <span m='4254070'>a</span> <span m='4254130'>binary</span> <span m='4254520'>tree.</span>
  </p><p><span m='4254860'>So</span> <span m='4255360'>I'm</span> <span m='4255450'>drawing</span>
  <span m='4255810'>the</span> <span m='4255900'>usual</span> <span m='4256440'>picture</span>
  <span m='4256830'>I</span> <span m='4256920'>draw</span> <span m='4257670'>when</span>
  <span m='4257760'>I</span> <span m='4257820'>draw</span> <span m='4258000'>a</span>
  <span m='4258030'>bunch</span> <span m='4258270'>of</span> <span m='4258360'>elements.</span>
  <span m='4260960'>And</span> <span m='4262830'>then</span> <span m='4262970'>there's</span>
  <span m='4263100'>some</span> <span m='4263280'>elements</span> <span m='4263640'>left</span>
  <span m='4263880'>over</span> <span m='4264780'>in</span> <span m='4264900'>each</span>
  <span m='4265080'>of</span> <span m='4265140'>these</span> <span m='4265290'>subtrees.</span>
  <span m='4271710'>Each</span> <span m='4271920'>of</span> <span m='4272040'>these</span>
  <span m='4272430'>is</span> <span m='4272580'>a</span> <span m='4272640'>predecessor</span>
  <span m='4273180'>problem.</span> </p><p><span m='4274630'>I'm</span> <span m='4275700'>constraining</span>
  <span m='4276450'>the</span> <span m='4276540'>inputs</span> <span m='4277950'>to</span>
  <span m='4278970'>sort</span> <span m='4279180'>of</span> <span m='4279330'>differ</span>
  <span m='4279705'>a</span> <span m='4280080'>lot</span> <span m='4280490'>in</span>
  <span m='4280620'>the</span> <span m='4280710'>beginning,</span> <span m='4281220'>in</span>
  <span m='4281340'>the</span> <span m='4281400'>early</span> <span m='4281700'>bits,</span>
  <span m='4281970'>the</span> <span m='4282090'>most</span> <span m='4282300'>significant</span>
  <span m='4282780'>bits.</span> <span m='4283060'>This</span> <span m='4283110'>is</span>
  <span m='4283200'>the</span> <span m='4283320'>most</span> <span m='4283500'>significant,</span>
  <span m='4283980'>next</span> <span m='4284220'>most</span> <span m='4284400'>significant,</span>
  <span m='4284760'>and</span> <span m='4284860'>so</span> <span m='4285030'>on,</span>
  <span m='4285180'>bits.</span> <span m='4286110'>I</span> <span m='4286170'>want</span>
  <span m='4286410'>the</span> <span m='4286500'>number</span> <span m='4286740'>of</span>
  <span m='4286860'>leaves</span> <span m='4287250'>here</span> <span m='4288390'>to</span>
  <span m='4288540'>be</span> <span m='4288810'>theta</span> <span m='4289440'>bt</span>
  <span m='4290090'>squared--</span> <span m='4291930'>or</span> <span m='4292050'>not</span>
  <span m='4292200'>leaves,</span> <span m='4292560'>but</span> <span m='4292710'>number</span>
  <span m='4292920'>of</span> <span m='4292980'>intermediate</span> <span m='4293460'>nodes</span>
  <span m='4293790'>here.</span> <span m='4296940'>And,</span> <span m='4297030'>therefore,</span>
  <span m='4297300'>there</span> <span m='4297420'>are</span> <span m='4297480'>theta</span>
  <span m='4297840'>bt</span> <span m='4298260'>squared</span> <span m='4299130'>subtrees.</span>
  </p><p><span m='4301410'>And</span> <span m='4301590'>I</span> <span m='4301680'>want</span>
  <span m='4301830'>to</span> <span m='4301920'>set</span> <span m='4302130'>up</span>
  <span m='4302310'>the n</span> <span m='4302640'>items</span> <span m='4303060'>to</span>
  <span m='4303180'>be</span> <span m='4303480'>uniformly</span> <span m='4303960'>distributed.</span>
  <span m='4304490'>So</span> <span m='4304530'>each</span> <span m='4304770'>of</span>
  <span m='4304830'>these</span> <span m='4305040'>has</span> <span m='4305810'>n</span>
  <span m='4306150'>divided</span> <span m='4306600'>by</span> <span m='4306920'>bt</span>
  <span m='4307300'>squared</span> <span m='4308510'>items.</span> <span m='4310920'>So</span>
  <span m='4311070'>we</span> <span m='4311160'>used</span> <span m='4311560'>a</span>
  <span m='4311880'>few</span> <span m='4312390'>bits</span> <span m='4312720'>up</span>
  <span m='4312870'>top</span> <span m='4313200'>here.</span> </p><p><span m='4314220'>How</span>
  <span m='4314370'>many</span> <span m='4314580'>bits</span> <span m='4314850'>was</span>
  <span m='4315000'>this,</span> <span m='4315320'>just</span> <span m='4315540'>log</span>
  <span m='4315900'>of</span> <span m='4317250'>bt</span> <span m='4317640'>squared?</span>
  <span m='4318880'>So</span> <span m='4319020'>if</span> <span m='4319140'>you</span>
  <span m='4319260'>look</span> <span m='4319440'>at</span> <span m='4319530'>one</span>
  <span m='4319650'>of</span> <span m='4319740'>these</span> <span m='4319860'>subproblems,</span>
  <span m='4320430'>we</span> <span m='4320520'>have</span> <span m='4320670'>reduced</span>
  <span m='4320970'>w</span> <span m='4321430'>slightly,</span> <span m='4322470'>but</span>
  <span m='4322620'>only</span> <span m='4322860'>by</span> <span m='4323010'>this</span>
  <span m='4323250'>additive</span> <span m='4323730'>amount.</span> <span m='4325230'>It</span>
  <span m='4325710'>basically</span> <span m='4326040'>won't</span> <span m='4326220'>matter.</span>
  </p><p><span m='4327250'>The</span> <span m='4327350'>big</span> <span m='4327450'>thing</span>
  <span m='4327630'>we</span> <span m='4327750'>changed</span> <span m='4328130'>is</span>
  <span m='4328230'>we</span> <span m='4328410'>used</span> <span m='4328620'>to</span>
  <span m='4328710'>have</span> <span m='4328890'>n</span> <span m='4329130'>items</span>
  <span m='4329470'>to</span> <span m='4329580'>search</span> <span m='4329850'>among,</span>
  <span m='4330260'>or this</span> <span m='4330420'>is n</span> <span m='4330780'>prime,</span>
  <span m='4331140'>I</span> <span m='4331200'>guess.</span> </p><p><span m='4331950'>Now,</span>
  <span m='4332250'>we</span> <span m='4332400'>have</span> <span m='4333270'>and</span>
  <span m='4333600'>divided</span> <span m='4333990'>by</span> <span m='4334360'>bt</span>
  <span m='4334680'>squared</span> <span m='4334980'>items.</span> <span m='4335480'>So</span>
  <span m='4335670'>we</span> <span m='4335820'>reduced</span> <span m='4336270'>n</span>
  <span m='4336480'>substantially.</span> <span m='4337990'>And</span> <span m='4338090'>this</span>
  <span m='4338160'>is</span> <span m='4338280'>what</span> <span m='4338400'>fusion</span>
  <span m='4338760'>trees</span> <span m='4339000'>do,</span> <span m='4339270'>right?</span>
  <span m='4339830'>They</span> <span m='4340020'>look</span> <span m='4340230'>at</span>
  <span m='4340320'>the</span> <span m='4340440'>root</span> <span m='4340830'>first,</span>
  <span m='4341730'>and</span> <span m='4341820'>say,</span> <span m='4342040'>OK,</span>
  <span m='4342310'>look,</span> <span m='4342550'>I</span> <span m='4342570'>can</span>
  <span m='4342750'>distinguish</span> <span m='4343740'>w</span> <span m='4344040'>to</span>
  <span m='4344160'>the</span> <span m='4344310'>epsilon,</span> <span m='4344700'>different</span>
  <span m='4344940'>things</span> <span m='4345210'>in</span> <span m='4345300'>constant</span>
  <span m='4345660'>time.</span> </p><p><span m='4346710'>Here,</span> <span m='4347000'>it's</span>
  <span m='4347120'>on</span> <span m='4347250'>w</span> <span m='4347460'>to</span>
  <span m='4347570'>the</span> <span m='4347670'>epsilon.</span> <span m='4348090'>But</span>
  <span m='4348210'>it's</span> <span m='4348330'>b to</span> <span m='4348780'>bt</span>
  <span m='4349140'>squared.</span> <span m='4349530'>And</span> <span m='4349720'>we
  haven't</span> <span m='4349830'>figured</span> <span m='4350100'>out</span> <span
  m='4350190'>what</span> <span m='4350310'>bt</span> <span m='4350710'>are</span>
  <span m='4350910'>yet.</span> <span m='4351930'>I</span> <span m='4351990'>mean,</span>
  <span m='4352200'>b</span> <span m='4352410'>is</span> <span m='4352530'>w.</span>
  <span m='4353170'>So</span> <span m='4353670'>that's</span> <span m='4354210'>close</span>
  <span m='4354660'>to</span> <span m='4355070'>a</span> <span m='4355360'>w</span>
  <span m='4355650'>factor,</span> <span m='4357540'>w</span> <span m='4357910'>folds</span>
  <span m='4358530'>search.</span> </p><p><span m='4359700'>And</span> <span m='4359850'>then</span>
  <span m='4360060'>you</span> <span m='4360330'>determine,</span> <span m='4360870'>am</span>
  <span m='4361020'>I</span> <span m='4361110'>in</span> <span m='4361200'>this</span>
  <span m='4361320'>subtree,</span> <span m='4361660'>or</span> <span m='4361750'>this</span>
  <span m='4361910'>subtree?</span> <span m='4362290'>This</span> <span m='4362550'>is</span>
  <span m='4362760'>exactly</span> <span m='4363210'>what</span> <span m='4363300'>fusion</span>
  <span m='4363630'>trees</span> <span m='4363870'>do.</span> <span m='4365460'>But</span>
  <span m='4365640'>we're</span> <span m='4365790'>setting</span> <span m='4366150'>up</span>
  <span m='4366300'>a</span> <span m='4366330'>lower</span> <span m='4366600'>bound</span>
  <span m='4366780'>instance</span> <span m='4367110'>where</span> <span m='4367260'>that</span>
  <span m='4367470'>is</span> <span m='4367590'>the</span> <span m='4367680'>right</span>
  <span m='4367890'>thing</span> <span m='4368100'>to</span> <span m='4368220'>do,</span>
  <span m='4368910'>where</span> <span m='4369150'>you</span> <span m='4369480'>have</span>
  <span m='4369870'>to</span> <span m='4369990'>know</span> <span m='4370830'>what</span>
  <span m='4371040'>the</span> <span m='4371130'>early</span> <span m='4371430'>bits</span>
  <span m='4371700'>are</span> <span m='4372510'>before</span> <span m='4372990'>you</span>
  <span m='4373140'>can</span> <span m='4373290'>figure</span> <span m='4373620'>out</span>
  <span m='4374130'>which</span> <span m='4374310'>subtree</span> <span m='4375060'>you're</span>
  <span m='4375240'>in.</span> </p><p><span m='4377640'>Now,</span> <span m='4378570'>reverse</span>
  <span m='4378960'>roles.</span> <span m='4380550'>Alice</span> <span m='4381600'>knows</span>
  <span m='4382560'>what</span> <span m='4382770'>these</span> <span m='4382950'>bits</span>
  <span m='4383190'>are.</span> <span m='4384690'>The</span> <span m='4384990'>data</span>
  <span m='4385290'>structure</span> <span m='4385590'>of</span> <span m='4385680'>relevance--</span>
  <span m='4386040'>let's</span> <span m='4386160'>suppose</span> <span m='4386460'>you</span>
  <span m='4386580'>fit</span> <span m='4386790'>here,</span> <span m='4387100'>because</span>
  <span m='4387180'>you</span> <span m='4387390'>are</span> <span m='4387540'>0111</span>
  <span m='4388350'>in</span> <span m='4388440'>the</span> <span m='4388500'>beginning.</span>
  </p><p><span m='4390540'>This</span> <span m='4390780'>is</span> <span m='4391170'>our</span>
  <span m='4391590'>yi</span> <span m='4393120'>problem.</span> <span m='4394770'>Alice</span>
  <span m='4395130'>knows</span> <span m='4395430'>what</span> <span m='4395580'>i</span>
  <span m='4395850'>is.</span> <span m='4396060'>Alice</span> <span m='4396390'>knows</span>
  <span m='4396720'>what</span> <span m='4396840'>those</span> <span m='4396990'>leading</span>
  <span m='4397290'>bits</span> <span m='4397530'>are.</span> <span m='4398250'>Bob</span>
  <span m='4398640'>doesn't.</span> </p><p><span m='4400230'>And</span> <span m='4400380'>Bob
  is</span> <span m='4400680'>speaking</span> <span m='4401100'>first.</span> <span
  m='4402090'>So</span> <span m='4402240'>Bob</span> <span m='4402480'>could</span>
  <span m='4402600'>try</span> <span m='4402900'>to</span> <span m='4402990'>summarize</span>
  <span m='4403530'>this</span> <span m='4403680'>entire</span> <span m='4404070'>data</span>
  <span m='4404280'>structure.</span> <span m='4404710'>But</span> <span m='4404730'>there's</span>
  <span m='4404850'>basically</span> <span m='4405240'>no</span> <span m='4405450'>hope.</span>
  </p><p><span m='4406500'>Bob</span> <span m='4406830'>needs</span> <span m='4407130'>to</span>
  <span m='4407220'>know,</span> <span m='4407460'>what</span> <span m='4407670'>are</span>
  <span m='4407760'>those</span> <span m='4408060'>early</span> <span m='4408540'>bits?</span>
  <span m='4409180'>So</span> <span m='4409260'>the</span> <span m='4409350'>first</span>
  <span m='4409620'>message</span> <span m='4409920'>from</span> <span m='4410040'>Bob</span>
  <span m='4410300'>is</span> <span m='4410370'>going</span> <span m='4410510'>to</span>
  <span m='4410580'>be</span> <span m='4410700'>useless.</span> <span m='4411540'>Alice</span>
  <span m='4411850'>can</span> <span m='4411990'>then</span> <span m='4412140'>send</span>
  <span m='4412350'>the</span> <span m='4412440'>bits.</span> <span m='4412710'>And</span>
  <span m='4412830'>then</span> <span m='4412950'>you</span> <span m='4413100'>can</span>
  <span m='4413280'>restrict</span> <span m='4413730'>your</span> <span m='4413820'>problem</span>
  <span m='4414120'>to</span> <span m='4414300'>a</span> <span m='4414540'>regular</span>
  <span m='4414900'>predecessor</span> <span m='4415380'>problem</span> <span m='4415680'>in</span>
  <span m='4415800'>here.</span> </p><p><span m='4416480'>And so</span> <span m='4416570'>you've</span>
  <span m='4416670'>eliminated</span> <span m='4417180'>this</span> <span m='4417450'>sort</span>
  <span m='4417660'>of</span> <span m='4417720'>root</span> <span m='4417960'>node.</span>
  <span m='4418860'>Your</span> <span m='4418980'>entire</span> <span m='4419310'>problem</span>
  <span m='4419640'>is</span> <span m='4419730'>a</span> <span m='4419790'>predecessor</span>
  <span m='4420270'>problem</span> <span m='4420540'>in</span> <span m='4420630'>here.</span>
  <span m='4420940'>So,</span> <span m='4421020'>again,</span> <span m='4421900'>we</span>
  <span m='4421950'>have</span> <span m='4422280'>an</span> <span m='4422430'>f</span>
  <span m='4422640'>to</span> <span m='4422760'>the</span> <span m='4422880'>k</span>
  <span m='4423600'>style</span> <span m='4423990'>problem.</span> <span m='4424560'>We</span>
  <span m='4424680'>reduce</span> <span m='4425040'>to</span> <span m='4425160'>a</span>
  <span m='4425220'>predecessor</span> <span m='4425760'>problem</span> <span m='4426210'>on</span>
  <span m='4426420'>a</span> <span m='4426480'>smaller--</span> <span m='4427680'>in</span>
  <span m='4427740'>this</span> <span m='4427860'>case,</span> <span m='4429150'>y</span>
  <span m='4429480'>and</span> <span m='4429630'>x</span> <span m='4429810'>are</span>
  <span m='4429900'>reversed.</span> <span m='4430520'>But</span> <span m='4431550'>we</span>
  <span m='4431700'>end</span> <span m='4431850'>up</span> <span m='4431970'>with</span>
  <span m='4432120'>a</span> <span m='4432180'>smaller</span> <span m='4432570'>problem,</span>
  <span m='4432840'>mainly</span> <span m='4433170'>in</span> <span m='4433230'>the</span>
  <span m='4433320'>fact</span> <span m='4433650'>that</span> <span m='4433960'>n
  got</span> <span m='4434460'>smaller.</span> </p><p><span m='4435740'>So let</span>
  <span m='4435840'>me</span> <span m='4435990'>go</span> <span m='4436110'>back</span>
  <span m='4437160'>to</span> <span m='4437280'>this</span> <span m='4437520'>board.</span>
  <span m='4440010'>What</span> <span m='4440190'>happens</span> <span m='4441360'>is</span>
  <span m='4441600'>that</span> <span m='4441810'>we</span> <span m='4441990'>reduce</span>
  <span m='4444240'>n</span> <span m='4444420'>prime</span> <span m='4445490'>to n</span>
  <span m='4445850'>prime,</span> <span m='4446640'>divided</span> <span m='4447120'>by</span>
  <span m='4450020'>bt</span> <span m='4450420'>squared.</span> <span m='4454060'>There's</span>
  <span m='4454350'>theta.</span> </p><p><span m='4457020'>We</span> <span m='4457230'>also</span>
  <span m='4457500'>reduce</span> <span m='4457800'>w</span> <span m='4458160'>prime.</span>
  <span m='4460200'>w</span> <span m='4460530'>prime</span> <span m='4460920'>becomes</span>
  <span m='4461490'>w</span> <span m='4461850'>prime,</span> <span m='4462300'>minus</span>
  <span m='4463470'>log</span> <span m='4463880'>bt</span> <span m='4464260'>squared.</span>
  <span m='4467050'>OK,</span> <span m='4467340'>but</span> <span m='4467520'>in</span>
  <span m='4467640'>particular,</span> <span m='4468240'>this</span> <span m='4468450'>is</span>
  <span m='4468570'>going</span> <span m='4468810'>to</span> <span m='4468960'>be</span>
  <span m='4469230'>at</span> <span m='4469380'>least</span> <span m='4470520'>w</span>
  <span m='4470880'>prime</span> <span m='4471300'>over</span> <span m='4471630'>2</span>
  <span m='4473040'>most</span> <span m='4473400'>of</span> <span m='4473460'>the</span>
  <span m='4473580'>time,</span> <span m='4473910'>till</span> <span m='4474030'>the</span>
  <span m='4474150'>very</span> <span m='4474450'>end.</span> <span m='4475020'>And</span>
  <span m='4475320'>over</span> <span m='4475560'>here,</span> <span m='4475810'>we're</span>
  <span m='4475920'>reducing</span> <span m='4476370'>w</span> <span m='4476730'>prime</span>
  <span m='4477390'>by</span> <span m='4477690'>a</span> <span m='4477750'>big</span>
  <span m='4477960'>factor,</span> <span m='4478950'>something</span> <span m='4479370'>bigger</span>
  <span m='4479610'>than</span> <span m='4479760'>a</span> <span m='4479820'>constant.</span>
  </p><p><span m='4480540'>So</span> <span m='4480690'>we</span> <span m='4480780'>don't</span>
  <span m='4480930'>really</span> <span m='4481110'>care</span> <span m='4481350'>about</span>
  <span m='4481560'>losing</span> <span m='4481800'>a</span> <span m='4481860'>factor</span>
  <span m='4482130'>of</span> <span m='4482220'>2,</span> <span m='4482760'>because</span>
  <span m='4482910'>we</span> <span m='4483000'>alternate</span> <span m='4483390'>between</span>
  <span m='4483750'>these.</span> <span m='4484520'>And</span> <span m='4484620'>so</span>
  <span m='4484860'>a</span> <span m='4484890'>factor</span> <span m='4485220'>of</span>
  <span m='4485310'>2</span> <span m='4485740'>just</span> <span m='4485970'>falls</span>
  <span m='4486270'>into</span> <span m='4486480'>the</span> <span m='4486570'>theta.</span>
  <span m='4487990'>So</span> <span m='4488070'>it's</span> <span m='4488190'>going</span>
  <span m='4488310'>to</span> <span m='4488400'>be</span> <span m='4488820'>at</span>
  <span m='4488910'>least</span> <span m='4489360'>that,</span> <span m='4489810'>as</span>
  <span m='4489990'>long</span> <span m='4490380'>as</span> <span m='4491550'>w</span>
  <span m='4491970'>prime</span> <span m='4492770'>is,</span> <span m='4493140'>I</span>
  <span m='4493455'>don't know,</span> <span m='4493770'>at</span> <span m='4493830'>least</span>
  <span m='4494670'>log--</span> <span m='4500570'>log</span> <span m='4500880'>w</span>
  <span m='4501320'>would</span> <span m='4501440'>be</span> <span m='4501560'>enough.</span>
  </p><p><span m='4507610'>Yeah,</span> <span m='4507890'>this is</span> <span m='4508250'>log</span>
  <span m='4508520'>w.</span> <span m='4509390'>t</span> <span m='4509645'>squared</span>
  <span m='4509900'>is</span> <span m='4510020'>going</span> <span m='4510170'>to</span>
  <span m='4510260'>be,</span> <span m='4511220'>at</span> <span m='4511310'>most,</span>
  <span m='4511580'>log</span> <span m='4511790'>w.</span> <span m='4512660'>So</span>
  <span m='4513996'>this is</span> <span m='4514990'>going</span> <span m='4515150'>to</span>
  <span m='4515240'>be</span> <span m='4515390'>log</span> <span m='4515650'>w,</span>
  <span m='4516470'>plus</span> <span m='4516860'>log</span> <span m='4517130'>log</span>
  <span m='4517460'>w.</span> <span m='4518045'>Log</span> <span m='4518300'>log</span>
  <span m='4518480'>w goes</span> <span m='4518970'>away.</span> <span m='4520460'>What</span>
  <span m='4520640'>is</span> <span m='4520840'>t?</span> </p><p><span m='4521435'>The</span>
  <span m='4521690'>whole</span> <span m='4521840'>point</span> <span m='4522050'>is</span>
  <span m='4522140'>to</span> <span m='4522230'>prove</span> <span m='4522440'>a</span>
  <span m='4522470'>lower</span> <span m='4522680'>bound</span> <span m='4522890'>on</span>
  <span m='4523010'>t.</span> <span m='4523550'>But</span> <span m='4523670'>we</span>
  <span m='4523820'>know from</span> <span m='4524150'>an</span> <span m='4524210'>upper</span>
  <span m='4524420'>bound</span> <span m='4524600'>perspective,</span> <span m='4525110'>t</span>
  <span m='4525290'>is,</span> <span m='4525370'>at</span> <span m='4525470'>most,</span>
  <span m='4525680'>log</span> <span m='4525920'>w,</span> <span m='4526700'>because</span>
  <span m='4527030'>Van Emde Boas</span> <span m='4527630'>exists.</span> <span m='4528655'>So</span>
  <span m='4529060'>we're</span> <span m='4529190'>never</span> <span m='4529400'>going</span>
  <span m='4529510'>to</span> <span m='4529610'>prove</span> <span m='4529820'>a</span>
  <span m='4529850'>lower</span> <span m='4530090'>bound</span> <span m='4530870'>bigger</span>
  <span m='4531170'>than</span> <span m='4531320'>log</span> <span m='4531540'>w.</span>
  </p><p><span m='4531910'>So</span> <span m='4532160'>whatever</span> <span m='4532530'>t</span>
  <span m='4532710'>is</span> <span m='4532790'>going</span> <span m='4532920'>to</span>
  <span m='4533000'>be</span> <span m='4533660'>is,</span> <span m='4533780'>at</span>
  <span m='4533870'>most,</span> <span m='4534080'>log</span> <span m='4534290'>w.</span>
  <span m='4534680'>So</span> <span m='4534890'>this</span> <span m='4535250'>is</span>
  <span m='4535430'>just</span> <span m='4535640'>log</span> <span m='4535850'>w.</span>
  <span m='4537470'>So</span> <span m='4537980'>you're</span> <span m='4538100'>fine.</span>
  </p><p><span m='4539880'>But</span> <span m='4540350'>at</span> <span m='4540470'>some</span>
  <span m='4540680'>point,</span> <span m='4541880'>we</span> <span m='4542000'>have</span>
  <span m='4542090'>to</span> <span m='4542210'>stop.</span> <span m='4542720'>We</span>
  <span m='4542840'>start</span> <span m='4543050'>with</span> <span m='4543140'>some</span>
  <span m='4543320'>w</span> <span m='4543680'>and</span> <span m='4543770'>n.</span>
  <span m='4545000'>n</span> <span m='4545330'>prime</span> <span m='4545720'>is</span>
  <span m='4545840'>racing</span> <span m='4546290'>down</span> <span m='4546560'>at</span>
  <span m='4546650'>this</span> <span m='4546830'>rate.</span> <span m='4547630'>w</span>
  <span m='4548000'>prime</span> <span m='4548420'>is</span> <span m='4548570'>racing</span>
  <span m='4548960'>down</span> <span m='4549320'>at</span> <span m='4549410'>this</span>
  <span m='4549620'>rate.</span> </p><p><span m='4551050'>When</span> <span m='4551580'>w</span>
  <span m='4551900'>prime</span> <span m='4552230'>gets</span> <span m='4552500'>down</span>
  <span m='4552800'>to</span> <span m='4553940'>log</span> <span m='4554570'>w,</span>
  <span m='4555660'>then</span> <span m='4555740'>we're</span> <span m='4555890'>in</span>
  <span m='4555950'>trouble.</span> <span m='4556820'>If</span> <span m='4556980'>n</span>
  <span m='4557210'>prime</span> <span m='4557570'>gets</span> <span m='4557780'>down</span>
  <span m='4558050'>to</span> <span m='4559610'>2,</span> <span m='4559970'>1,</span>
  <span m='4560330'>0,</span> <span m='4560690'>one</span> <span m='4560840'>of</span>
  <span m='4560900'>those</span> <span m='4561740'>constants,</span> <span m='4562740'>when</span>
  <span m='4563090'>n prime</span> <span m='4563300'>gets</span> <span m='4563480'>down
  to a</span> <span m='4563690'>constant,</span> <span m='4564630'>we're</span> <span
  m='4564830'>in</span> <span m='4564920'>trouble.</span> <span m='4565250'>You</span>
  <span m='4565340'>can</span> <span m='4565460'>no</span> <span m='4565640'>longer</span>
  <span m='4565940'>evenly</span> <span m='4566330'>divide</span> <span m='4566690'>things.</span>
  </p><p><span m='4568120'>So</span> <span m='4568310'>when</span> <span m='4568490'>does</span>
  <span m='4568640'>that</span> <span m='4568820'>happen?</span> <span m='4569980'>This</span>
  <span m='4570120'>is</span> <span m='4570170'>where</span> <span m='4570350'>we're</span>
  <span m='4570410'>going</span> <span m='4570530'>to</span> <span m='4570620'>get</span>
  <span m='4570710'>a</span> <span m='4570740'>lower</span> <span m='4570980'>bound.</span>
  <span m='4573290'>So</span> <span m='4573590'>I</span> <span m='4573650'>guess</span>
  <span m='4573830'>we</span> <span m='4573920'>can</span> <span m='4574010'>go</span>
  <span m='4574130'>back</span> <span m='4574370'>over</span> <span m='4574550'>here.</span>
  </p><p><span m='4580060'>So</span> <span m='4580190'>if</span> <span m='4580280'>you</span>
  <span m='4580340'>do</span> <span m='4580790'>a</span> <span m='4581090'>round</span>
  <span m='4581390'>elimination,</span> <span m='4583130'>you</span> <span m='4583580'>decrease</span>
  <span m='4584150'>w</span> <span m='4584450'>prime</span> <span m='4584750'>by</span>
  <span m='4584840'>this</span> <span m='4585020'>factor.</span> <span m='4586130'>And</span>
  <span m='4586280'>you</span> <span m='4586430'>decrease</span> <span m='4587000'>n</span>
  <span m='4587210'>prime</span> <span m='4587570'>by</span> <span m='4587690'>this</span>
  <span m='4587870'>factor,</span> <span m='4588530'>both</span> <span m='4588860'>of</span>
  <span m='4588950'>these</span> <span m='4589850'>in</span> <span m='4589970'>sequence.</span>
  <span m='4590820'>Then</span> <span m='4590930'>you</span> <span m='4591050'>repeat</span>
  <span m='4591410'>it.</span> </p><p><span m='4594020'>So</span> <span m='4594890'>we</span>
  <span m='4595040'>have</span> <span m='4595220'>to</span> <span m='4595340'>stop</span>
  <span m='4597240'>when</span> <span m='4599390'>w</span> <span m='4599810'>prime</span>
  <span m='4601340'>hits</span> <span m='4601810'>log</span> <span m='4602300'>w,</span>
  <span m='4603620'>or</span> <span m='4604940'>when</span> <span m='4605180'>n</span>
  <span m='4605420'>prime</span> <span m='4606830'>hits</span> <span m='4608000'>2,</span>
  <span m='4608330'>let's</span> <span m='4608690'>say.</span> <span m='4610430'>This</span>
  <span m='4610700'>is</span> <span m='4610970'>not</span> <span m='4611180'>really</span>
  <span m='4611360'>going</span> <span m='4611480'>to</span> <span m='4611540'>make</span>
  <span m='4611660'>a</span> <span m='4611720'>difference.</span> <span m='4612050'>You</span>
  <span m='4612110'>can</span> <span m='4612230'>also</span> <span m='4612410'>think</span>
  <span m='4612670'>that</span> <span m='4612820'>as</span> <span m='4612940'>2.</span>
  <span m='4616700'>So,</span> <span m='4616760'>in</span> <span m='4617030'>fact,</span>
  <span m='4617390'>I'll</span> <span m='4617490'>just</span> <span m='4617660'>do</span>
  <span m='4617810'>that,</span> <span m='4620040'>just</span> <span m='4620250'>to</span>
  <span m='4621210'>clean</span> <span m='4621450'>the</span> <span m='4621600'>arithmetic</span>
  <span m='4622080'>a</span> <span m='4622140'>little</span> <span m='4622320'>bit.</span>
  </p><p><span m='4627390'>Now,</span> <span m='4627930'>if</span> <span m='4628080'>we</span>
  <span m='4628200'>succeed</span> <span m='4628680'>in</span> <span m='4628770'>eliminating</span>
  <span m='4629370'>all</span> <span m='4629610'>the</span> <span m='4629700'>messages,</span>
  <span m='4630660'>we</span> <span m='4630780'>get</span> <span m='4630900'>a</span>
  <span m='4630960'>contradiction,</span> <span m='4631830'>because</span> <span m='4632070'>we</span>
  <span m='4632130'>set</span> <span m='4632340'>up</span> <span m='4632490'>our</span>
  <span m='4632610'>errors</span> <span m='4633000'>to</span> <span m='4633090'>add</span>
  <span m='4633300'>up</span> <span m='4633480'>to</span> <span m='4633780'>only</span>
  <span m='4634020'>1/3.</span> <span m='4635760'>And</span> <span m='4636240'>we</span>
  <span m='4636450'>know</span> <span m='4636790'>the</span> <span m='4636940'>error</span>
  <span m='4637080'>has</span> <span m='4637410'>to</span> <span m='4637530'>be</span>
  <span m='4637710'>at</span> <span m='4637770'>least</span> <span m='4637980'>1/2,</span>
  <span m='4638430'>if</span> <span m='4638500'>you</span> <span m='4638640'>eliminate</span>
  <span m='4639030'>all</span> <span m='4639150'>the</span> <span m='4639240'>messages,</span>
  <span m='4639690'>which</span> <span m='4639870'>means</span> <span m='4640620'>we</span>
  <span m='4640740'>didn't</span> <span m='4641070'>eliminate</span> <span m='4641490'>all</span>
  <span m='4641580'>the</span> <span m='4641640'>messages.</span> </p><p><span m='4642900'>Now,</span>
  <span m='4644520'>we</span> <span m='4644730'>will</span> <span m='4644850'>not</span>
  <span m='4645090'>eliminate</span> <span m='4645840'>all</span> <span m='4645960'>the</span>
  <span m='4646050'>messages</span> <span m='4646440'>if</span> <span m='4646620'>t</span>
  <span m='4646800'>is</span> <span m='4646920'>large.</span> <span m='4648720'>So</span>
  <span m='4649440'>when</span> <span m='4649710'>would</span> <span m='4649830'>we</span>
  <span m='4649980'>eliminate</span> <span m='4650370'>all</span> <span m='4650460'>the</span>
  <span m='4650550'>messages?</span> <span m='4651420'>Let's</span> <span m='4651570'>compute</span>
  <span m='4651960'>that.</span> </p><p><span m='4652460'>And</span> <span m='4652560'>then</span>
  <span m='4652740'>t</span> <span m='4653430'>has</span> <span m='4653670'>to</span>
  <span m='4653790'>be</span> <span m='4654120'>at</span> <span m='4654240'>least</span>
  <span m='4654540'>that</span> <span m='4654780'>big.</span> <span m='4657210'>t</span>
  <span m='4658800'>has</span> <span m='4659010'>to</span> <span m='4659130'>be</span>
  <span m='4659280'>greater</span> <span m='4659760'>than</span> <span m='4660000'>the</span>
  <span m='4660090'>point</span> <span m='4660360'>at</span> <span m='4660450'>which</span>
  <span m='4660660'>we</span> <span m='4660780'>would</span> <span m='4660870'>eliminate</span>
  <span m='4661260'>all</span> <span m='4661350'>the</span> <span m='4661410'>messages.</span>
  <span m='4661860'>Otherwise,</span> <span m='4662280'>we would</span> <span m='4662340'>get</span>
  <span m='4662490'>a</span> <span m='4662550'>contradiction.</span> <span m='4664390'>So</span>
  <span m='4665460'>this</span> <span m='4665670'>is</span> <span m='4665790'>where</span>
  <span m='4665970'>we</span> <span m='4666060'>get</span> <span m='4666320'>a</span>
  <span m='4666390'>min,</span> <span m='4667250'>which is</span> <span m='4667380'>kind</span>
  <span m='4667560'>of</span> <span m='4667650'>cool,</span> <span m='4668280'>because</span>
  <span m='4668430'>we</span> <span m='4668490'>have</span> <span m='4668610'>to</span>
  <span m='4668700'>stop</span> <span m='4669000'>when</span> <span m='4669150'>w</span>
  <span m='4669480'>prime</span> <span m='4669810'>gets</span> <span m='4670020'>too</span>
  <span m='4670140'>small,</span> <span m='4670800'>or</span> <span m='4671490'>when</span>
  <span m='4671640'>n</span> <span m='4671850'>prime</span> <span m='4672120'>gets</span>
  <span m='4672300'>too</span> <span m='4672420'>small,</span> <span m='4672720'>whichever</span>
  <span m='4673200'>happens</span> <span m='4673620'>first.</span> </p><p><span m='4674820'>And</span>
  <span m='4674910'>so</span> <span m='4675030'>it's</span> <span m='4675150'>going</span>
  <span m='4675270'>to</span> <span m='4675360'>be</span> <span m='4675510'>a</span>
  <span m='4675570'>min</span> <span m='4677430'>of</span> <span m='4677700'>the</span>
  <span m='4677820'>thing</span> <span m='4678670'>relating</span> <span m='4679170'>to</span>
  <span m='4679260'>w,</span> <span m='4680760'>which</span> <span m='4680970'>is</span>
  <span m='4681090'>going</span> <span m='4681240'>to</span> <span m='4681300'>be</span>
  <span m='4681570'>log</span> <span m='4682710'>base</span> <span m='4683250'>at</span>
  <span m='4683770'>squared</span> <span m='4684980'>of</span> <span m='4685290'>w,</span>
  <span m='4686280'>because</span> <span m='4686460'>we're</span> <span m='4686670'>reducing</span>
  <span m='4687180'>w</span> <span m='4687480'>by</span> <span m='4687600'>a</span>
  <span m='4687630'>factor</span> <span m='4687930'>of</span> <span m='4688020'>at</span>
  <span m='4688260'>squared</span> <span m='4688580'>in</span> <span m='4688820'>each</span>
  <span m='4689220'>step.</span> <span m='4689500'>So</span> <span m='4689610'>that's</span>
  <span m='4689820'>when</span> <span m='4689970'>it's</span> <span m='4690060'>going</span>
  <span m='4690180'>to</span> <span m='4690240'>bottom</span> <span m='4690540'>out.</span>
  <span m='4691440'>And</span> <span m='4691950'>then</span> <span m='4692160'>there's</span>
  <span m='4692340'>the</span> <span m='4692460'>thing</span> <span m='4692640'>for</span>
  <span m='4692790'>n,</span> <span m='4693120'>which</span> <span m='4693300'>is</span>
  <span m='4693450'>log</span> <span m='4694000'>base</span> <span m='4694370'>bt</span>
  <span m='4694800'>squared</span> <span m='4696380'>of n.</span> </p><p><span m='4697740'>That's</span>
  <span m='4697950'>when</span> <span m='4698290'>n will</span> <span m='4698430'>bottom</span>
  <span m='4698760'>out,</span> <span m='4698970'>because</span> <span m='4699150'>we're</span>
  <span m='4699270'>reducing</span> <span m='4699720'>by</span> <span m='4699870'>a</span>
  <span m='4699900'>factor</span> <span m='4700230'>of bt</span> <span m='4700580'>square</span>
  <span m='4700810'>at</span> <span m='4700880'>each</span> <span m='4701040'>step.</span>
  <span m='4704010'>So</span> <span m='4705390'>that's</span> <span m='4705630'>the</span>
  <span m='4705750'>bound</span> <span m='4706030'>we</span> <span m='4706170'>get.</span>
  <span m='4708790'>Now,</span> <span m='4709850'>it</span> <span m='4709930'>doesn't</span>
  <span m='4710230'>look</span> <span m='4710410'>quite</span> <span m='4711010'>like</span>
  <span m='4711250'>the</span> <span m='4711370'>bound</span> <span m='4711640'>that</span>
  <span m='4711730'>we</span> <span m='4711940'>want,</span> <span m='4712960'>which
  is</span> <span m='4713230'>this</span> <span m='4713560'>very</span> <span m='4713770'>simple</span>
  <span m='4714130'>log,</span> <span m='4714430'>base of</span> <span m='4714940'>w,</span>
  <span m='4715360'>log</span> <span m='4715600'>base</span> <span m='4715820'>b</span>
  <span m='4716000'>of n.</span> <span m='4716740'>But</span> <span m='4716890'>I</span>
  <span m='4716980'>claim</span> <span m='4717340'>that</span> <span m='4717490'>it's</span>
  <span m='4717640'>basically</span> <span m='4718060'>the</span> <span m='4718180'>same</span>
  <span m='4718480'>thing.</span> </p><p><span m='4730350'>Why?</span> <span m='4731880'>I
  got to cheat</span> <span m='4732180'>here,</span> <span m='4733050'>speed</span>
  <span m='4733320'>things</span> <span m='4733500'>up</span> <span m='4733680'>a</span>
  <span m='4733710'>little</span> <span m='4733980'>bit.</span> <span m='4734490'>I</span>
  <span m='4734580'>claim</span> <span m='4734880'>that</span> <span m='4735030'>at</span>
  <span m='4735420'>squared</span> <span m='4736890'>is</span> <span m='4737250'>order</span>
  <span m='4738120'>a</span> <span m='4738600'>cubed.</span> <span m='4741090'>Why?</span>
  <span m='4742890'>Because</span> <span m='4744270'>a</span> <span m='4745050'>is</span>
  <span m='4745230'>at</span> <span m='4745320'>least</span> <span m='4745590'>log</span>
  <span m='4745870'>n.</span> <span m='4746480'>Remember,</span> <span m='4746690'>a</span>
  <span m='4746920'>is</span> <span m='4747120'>log</span> <span m='4747470'>of</span>
  <span m='4747570'>space.</span> </p><p><span m='4750430'>You</span> <span m='4750785'>have
  to</span> <span m='4751140'>store</span> <span m='4751410'>the</span> <span m='4751530'>data.</span>
  <span m='4751800'>So</span> <span m='4752070'>you</span> <span m='4752130'>need</span>
  <span m='4752280'>at</span> <span m='4752340'>least</span> <span m='4752550'>n words</span>
  <span m='4752940'>of</span> <span m='4753000'>space.</span> <span m='4754440'>a
  is</span> <span m='4754780'>log</span> <span m='4755120'>of</span> <span m='4755220'>that.</span>
  <span m='4755540'>So it's</span> <span m='4755710'>got</span> <span m='4755870'>to</span>
  <span m='4755940'>be</span> <span m='4756000'>at</span> <span m='4756060'>least</span>
  <span m='4756270'>log</span> <span m='4756520'>n.</span> </p><p><span m='4757200'>And,</span>
  <span m='4757290'>furthermore,</span> <span m='4757740'>t</span> <span m='4759360'>is</span>
  <span m='4759510'>at</span> <span m='4759570'>most</span> <span m='4759820'>log</span>
  <span m='4760070'>n.</span> <span m='4763050'>Why?</span> <span m='4763410'>Because</span>
  <span m='4763770'>there</span> <span m='4763890'>is</span> <span m='4764010'>a</span>
  <span m='4764070'>predecessor</span> <span m='4764370'>or</span> <span m='4764670'>data</span>
  <span m='4764880'>structure</span> <span m='4765270'>that</span> <span m='4765390'>runs</span>
  <span m='4765630'>in</span> <span m='4765750'>log</span> <span m='4765960'>n</span>
  <span m='4766080'>time</span> <span m='4766410'>operation,</span> <span m='4766890'>namely</span>
  <span m='4767640'>balance</span> <span m='4767970'>binary</span> <span m='4768270'>search</span>
  <span m='4768540'>trees.</span> <span m='4769500'>There's</span> <span m='4769650'>a</span>
  <span m='4769710'>theta</span> <span m='4770020'>here,</span> <span m='4770400'>order,</span>
  <span m='4771440'>big</span> <span m='4771850'>O.</span> <span m='4772390'>But</span>
  <span m='4772610'>at</span> <span m='4772910'>squared</span> <span m='4773250'>is,</span>
  <span m='4773350'>at</span> <span m='4773430'>most,</span> <span m='4774090'>a</span>
  <span m='4774590'>cubed.</span> </p><p><span m='4777360'>On</span> <span m='4777480'>the</span>
  <span m='4777570'>other</span> <span m='4777750'>hand,</span> <span m='4780100'>this</span>
  <span m='4780210'>thing,</span> <span m='4781140'>bt</span> <span m='4781500'>square,</span>
  <span m='4782760'>is</span> <span m='4782940'>order</span> <span m='4783210'>b</span>
  <span m='4783680'>cubed.</span> <span m='4785190'>Why?</span> <span m='4785950'>Because</span>
  <span m='4787050'>t</span> <span m='4791570'>is</span> <span m='4791780'>order</span>
  <span m='4793100'>log</span> <span m='4793790'>w.</span> <span m='4794210'>b</span>
  <span m='4795430'>is</span> <span m='4795680'>w.</span> <span m='4796460'>That's
  the</span> <span m='4796700'>definition</span> <span m='4797240'>of</span> <span
  m='4797300'>b.</span> </p><p><span m='4798260'>T</span> <span m='4798530'>is</span>
  <span m='4798620'>order</span> <span m='4798830'>log</span> <span m='4799060'>w,</span>
  <span m='4799340'>because</span> <span m='4799640'>Van Emde Boas</span> <span m='4800210'>exists.</span>
  <span m='4801230'>And</span> <span m='4801320'>so</span> <span m='4801440'>this</span>
  <span m='4801620'>is</span> <span m='4801740'>actually,</span> <span m='4802100'>at</span>
  <span m='4802160'>most,</span> <span m='4803000'>w</span> <span m='4803840'>times</span>
  <span m='4804310'>log</span> <span m='4804550'>squared</span> <span m='4804820'>w.</span>
  <span m='4805230'>But,</span> <span m='4805400'>in</span> <span m='4805490'>particular,</span>
  <span m='4805760'>it's</span> <span m='4805860'>at</span> <span m='4805940'>most</span>
  <span m='4806120'>w</span> <span m='4806510'>cubed,</span> <span m='4807980'>because</span>
  <span m='4809030'>we</span> <span m='4809120'>don't</span> <span m='4809300'>care</span>
  <span m='4809450'>about</span> <span m='4809600'>that</span> <span m='4809720'>constant</span>
  <span m='4810110'>because</span> <span m='4810290'>it's</span> <span m='4810410'>in</span>
  <span m='4810530'>a</span> <span m='4810560'>log.</span> <span m='4811400'>So</span>
  <span m='4811550'>it</span> <span m='4811610'>just</span> <span m='4811760'>comes</span>
  <span m='4812000'>out.</span> </p><p><span m='4812210'>It's a</span> <span m='4812300'>factor</span>
  <span m='4812660'>of</span> <span m='4812720'>1/3</span> <span m='4813080'>or</span>
  <span m='4813140'>whatever.</span> <span m='4813960'>And</span> <span m='4814040'>so</span>
  <span m='4814190'>this</span> <span m='4814640'>is</span> <span m='4815540'>the</span>
  <span m='4815630'>same</span> <span m='4815960'>thing</span> <span m='4817010'>as</span>
  <span m='4818020'>log</span> <span m='4818990'>base</span> <span m='4819340'>a</span>
  <span m='4819610'>of</span> <span m='4819880'>w,</span> <span m='4821030'>log</span>
  <span m='4821540'>base</span> <span m='4821930'>b</span> <span m='4822270'>of</span>
  <span m='4822690'>n,</span> <span m='4823080'>minned.</span> <span m='4824480'>And</span>
  <span m='4824600'>that's</span> <span m='4824870'>the</span> <span m='4824990'>nice,</span>
  <span m='4825460'>symmetric</span> <span m='4825860'>bound</span> <span m='4826190'>that</span>
  <span m='4826310'>you</span> <span m='4826400'>get</span> <span m='4827030'>our
  of</span> <span m='4827150'>round</span> <span m='4827420'>elimination,</span> <span
  m='4828230'>pretty</span> <span m='4828440'>cool.</span> </p><p><span m='4830360'>Now,</span>
  <span m='4830570'>if</span> <span m='4830660'>you</span> <span m='4830780'>look</span>
  <span m='4830960'>in</span> <span m='4831080'>the</span> <span m='4831170'>notes,</span>
  <span m='4831430'>I'll</span> <span m='4831690'>just</span> <span m='4831860'>mentioned</span>
  <span m='4832160'>this</span> <span m='4832280'>briefly,</span> <span m='4832960'>there's</span>
  <span m='4833180'>a</span> <span m='4833240'>couple</span> <span m='4833450'>of</span>
  <span m='4833510'>more</span> <span m='4833660'>pages</span> <span m='4834770'>that</span>
  <span m='4835280'>give</span> <span m='4835460'>you</span> <span m='4835550'>a</span>
  <span m='4835580'>little</span> <span m='4836120'>bit</span> <span m='4836270'>of</span>
  <span m='4836330'>flavor</span> <span m='4836780'>of</span> <span m='4836900'>what</span>
  <span m='4837620'>the</span> <span m='4837710'>round</span> <span m='4837920'>elimination</span>
  <span m='4838520'>and</span> <span m='4838650'>that</span> <span m='4839570'>vague</span>
  <span m='4840080'>proof</span> <span m='4840350'>sketch,</span> <span m='4840620'>which</span>
  <span m='4840800'>gave</span> <span m='4840980'>the</span> <span m='4841070'>wrong</span>
  <span m='4841310'>answer</span> <span m='4841580'>by</span> <span m='4841730'>a</span>
  <span m='4841760'>square</span> <span m='4842030'>root,</span> <span m='4843020'>really</span>
  <span m='4843440'>means.</span> <span m='4844980'>We</span> <span m='4845420'>said,</span>
  <span m='4845750'>oh,</span> <span m='4847060'>Alice</span> <span m='4847370'>can</span>
  <span m='4847550'>only</span> <span m='4847880'>communicate,</span> <span m='4848870'>in</span>
  <span m='4848990'>some</span> <span m='4849290'>sense,</span> <span m='4850980'>a
  over</span> <span m='4851180'>k</span> <span m='4851630'>bits</span> <span m='4852170'>about</span>
  <span m='4853250'>xi.</span> </p><p><span m='4854510'>And</span> <span m='4854660'>you</span>
  <span m='4854780'>can</span> <span m='4854900'>formalize</span> <span m='4855440'>that</span>
  <span m='4855590'>by</span> <span m='4855680'>talking</span> <span m='4855980'>about</span>
  <span m='4856130'>distributions</span> <span m='4856970'>of</span> <span m='4857090'>inputs,</span>
  <span m='4858140'>and</span> <span m='4858870'>talking</span> <span m='4859220'>about</span>
  <span m='4859520'>the</span> <span m='4859790'>expected</span> <span m='4860750'>amount</span>
  <span m='4861050'>of</span> <span m='4861290'>entropy</span> <span m='4864230'>of</span>
  <span m='4867680'>xi</span> <span m='4868340'>communicated</span> <span m='4869060'>by</span>
  <span m='4869210'>that</span> <span m='4869420'>first</span> <span m='4869690'>message.</span>
  <span m='4871280'>And so</span> <span m='4871620'>it's</span> <span m='4871950'>very</span>
  <span m='4872150'>simple</span> <span m='4872450'>definitions</span> <span m='4872870'>of</span>
  <span m='4872990'>entropy,</span> <span m='4873530'>and</span> <span m='4873650'>shared</span>
  <span m='4873870'>information,</span> <span m='4874460'>but</span> <span m='4875240'>just</span>
  <span m='4875480'>in</span> <span m='4875570'>terms</span> <span m='4875780'>of</span>
  <span m='4875840'>probabilistic</span> <span m='4876500'>quantities.</span> <span
  m='4877130'>And it</span> <span m='4877220'>at</span> <span m='4877280'>least</span>
  <span m='4877460'>gives</span> <span m='4877640'>you</span> <span m='4878190'>a</span>
  <span m='4878280'>sense</span> <span m='4878810'>of</span> <span m='4878900'>how</span>
  <span m='4879110'>you</span> <span m='4879290'>might</span> <span m='4879500'>prove</span>
  <span m='4879770'>something</span> <span m='4880160'>like</span> <span m='4880400'>this.</span>
  </p><p><span m='4880670'>Whereas</span> <span m='4881240'>talking</span> <span m='4881480'>about</span>
  <span m='4881660'>information</span> <span m='4882260'>about</span> <span m='4882560'>something</span>
  <span m='4882920'>is</span> <span m='4883010'>kind</span> <span m='4883220'>of</span>
  <span m='4883280'>vague,</span> <span m='4884210'>talking</span> <span m='4884450'>about</span>
  <span m='4884690'>entropy,</span> <span m='4885300'>which</span> <span m='4885590'>is</span>
  <span m='4885710'>about</span> <span m='4885980'>sum</span> <span m='4886490'>of</span>
  <span m='4886610'>probabilities</span> <span m='4887240'>times</span> <span m='4887420'>log
  of</span> <span m='4887720'>probabilities</span> <span m='4888890'>is</span> <span
  m='4889040'>a</span> <span m='4889130'>clean,</span> <span m='4889490'>probabilistic</span>
  <span m='4890090'>notion.</span> <span m='4890420'>So</span> <span m='4890560'>it</span>
  <span m='4890630'>becomes</span> <span m='4891080'>a</span> <span m='4891140'>purely</span>
  <span m='4892220'>probabilistic</span> <span m='4893360'>statements</span> <span
  m='4895190'>about</span> <span m='4895430'>error</span> <span m='4895760'>probabilities.</span>
  <span m='4896510'>And</span> <span m='4896630'>that's</span> <span m='4896780'>how</span>
  <span m='4896900'>you</span> <span m='4897360'>argue</span> <span m='4897620'>this.</span>
  </p><p><span m='4898040'>But</span> <span m='4898790'>even</span> <span m='4899120'>these</span>
  <span m='4899330'>notes</span> <span m='4899600'>do</span> <span m='4899720'>not</span>
  <span m='4899900'>give</span> <span m='4900050'>a</span> <span m='4900140'>proof.</span>
  <span m='4900440'>They</span> <span m='4900530'>just</span> <span m='4900710'>give</span>
  <span m='4901280'>a</span> <span m='4901340'>hint</span> <span m='4901610'>of</span>
  <span m='4901700'>how</span> <span m='4901850'>you</span> <span m='4901970'>formalize</span>
  <span m='4902480'>what</span> <span m='4902600'>this</span> <span m='4902780'>means,</span>
  <span m='4903200'>or</span> <span m='4903590'>what</span> <span m='4903740'>the</span>
  <span m='4903860'>proof</span> <span m='4904070'>sketch</span> <span m='4904340'>means.</span>
  <span m='4905420'>And</span> <span m='4906730'>it's</span> <span m='4906860'>several</span>
  <span m='4907160'>pages</span> <span m='4907490'>to</span> <span m='4907550'>actually</span>
  <span m='4907940'>prove</span> <span m='4908180'>it,</span> <span m='4908340'>so</span>
  <span m='4908990'>a</span> <span m='4909080'>bit</span> <span m='4909260'>beyond</span>
  <span m='4909530'>this</span> <span m='4909680'>class.</span> </p><p><span m='4910550'>But</span>
  <span m='4910670'>once</span> <span m='4910850'>you</span> <span m='4910970'>have</span>
  <span m='4911240'>it--</span> <span m='4911420'>because</span> <span m='4911700'>it's</span>
  <span m='4911900'>very</span> <span m='4912470'>clean,</span> <span m='4913070'>I'd</span>
  <span m='4913220'>say</span> <span m='4913490'>kind</span> <span m='4913670'>of</span>
  <span m='4913760'>beautiful</span> <span m='4914180'>lower</span> <span m='4914450'>bound,</span>
  <span m='4915380'>not</span> <span m='4915620'>quite</span> <span m='4916010'>the</span>
  <span m='4916100'>right</span> <span m='4916250'>answer,</span> <span m='4916580'>but</span>
  <span m='4916700'>up</span> <span m='4916790'>to</span> <span m='4916880'>log</span>
  <span m='4917120'>log</span> <span m='4917270'>factors,</span> <span m='4918110'>the</span>
  <span m='4918200'>right</span> <span m='4918350'>answer</span> <span m='4918740'>for</span>
  <span m='4918920'>predecessor.</span> <span m='4920610'>So</span> <span m='4920930'>that's</span>
  <span m='4921170'>the</span> <span m='4921290'>end</span> <span m='4921470'>of</span>
  <span m='4921530'>predecessor</span> <span m='4922430'>in</span> <span m='4922550'>this</span>
  <span m='4922700'>class.</span> </p>
type: course
uid: 14f25333bd634c2ae841e5e17ce09c04

---
None
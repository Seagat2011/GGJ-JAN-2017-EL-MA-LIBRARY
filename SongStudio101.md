
KickStudio 2017 - requisite projects

  1. APlayer.js / android-UniversalMusicPlayer-master- UI
  2. Tone.js - Oscillator APIs (eg Tone.js-master/examples/stepSequencer.html)
  3. sonic-pi-master/etc/samples - Sound Masters

NOTE-DURATION

  whole,1,half,2nd,quarter,4th,eighth,8th,sixteenth,16th,32nd,64th,128th
  
MAJOR/MINOR KEY-NOTATION

  [M,m,dim,aug,sus]

UI

  [hr-2:min-2:sec-15] signtaure=[4,4] 4th=60-bpm Key=CM
  00.00.000000000000000
                     (1) Marker ..
                      v
  Left  --------------|---------------------------------
                      |
  Right --------------|---------------------------------
                      |
  
  [ 1 ] Intro, [ 2 ] Interlude, [ 3 ] Solo, [ 4 ] A Cappella, 
  
  < PREV / NEXT > Bookmark
  
  Note: Each waveform inflection-point has a bookmark, timbre, and note-data

COMPATIBLE FILETYPES

  [mp4,midi,mid,pdf]

FEATRURES

  -BASIC Specify Genre,bpm,keySig
  -ADVANCED Info derived from voicefile
  
RECORDING STUDIO SIZE

  -Airtight studio
  -Headphones
  -Small room
  -Medium room
  -Large room
  -Small hall
  -Medium hall
  -Large hall
  -Live arena

GENRES

  -A Cappella
  -Acid
  -Acid Jazz
  -Acid Punk
  -Acoustic
  -Alternative Rock
  -Alternative
  -Ambient
  -Anime
  -Avante Garde
  -Ballad
  -Bass
  -Beat
  -Bebob
  -Big Band
  -Black Metal
  -Bluegrass
  -Blues
  -Booty Bass
  -British Pop
  -Cabaret
  -Calypso
  -Celtic
  -Chamber Music
  -Chanson
  -Chorus
  -Christian Gangsta Rap
  -Christian Rap
  -Christian Rock
  -Classical
  -Classic Rock
  -Club
  -Clubhouse
  -Comedy
  -Contemporary Christian
  -Contemporary Rock
  -Country
  -Crossover
  -Cult
  -Dance
  -Dance Hall
  -Darkwave
  -Death Metal
  -Disco
  -Dream
  -Drum & Bass
  -Drum Solo
  -Duet
  -Documentary Film
  -Easy Listening
  -Electronic
  -Ethnic
  -Euro House
  -Euro Techno
  -Euro Dance
  -Fast Fusion
  -Film Credits
  -Film Sequence
  -Flat
  -Folk
  -Folk Rock
  -Folklore
  -Freestyle
  -Full Bass
  -Full Treble
  -Full Bass and Treble
  -Funk
  -Fusion
  -Game
  -Gangsta
  -Goa
  -Gospel
  -Gothic
  -Gothic Rock
  -Grunge
  -Hard Rock
  -Hardcore
  -Heavy Metal
  -Hip Hop
  -House
  -Humour
  -Indie
  -Industrial
  -Instrumental
  -Instrumental Pop
  -Instrumental Rock
  -Jazz
  -JPop
  -Jazz+Funk
  -Jungle
  -Latin
  -Lo Fi
  -Meditative
  -Merengue
  -Metal
  -Musical
  -National Folk
  -Native American
  -Negerpunk
  -New Age
  -New Wave
  -Noise
  -Oldies
  -Opera
  -Party
  -Polka
  -Polsk Punk
  -Pop
  -Pop Folk
  -Pop Funk
  -Porn Groove
  -Power Ballad
  -Pranks
  -Primus
  -Progressive Rock
  -Psychedelic
  -Psychedelic Rock
  -Punk
  -Punk Rock
  -R&B
  -Rap
  -Rave
  -Reggae
  -Retro
  -Revival
  -Rhythmic Soul
  -Rock
  -Rock & Roll
  -60's Rock
  -70's Rock
  -80's Rock
  -90's Rock
  -Salsa
  -Samba
  -Satire
  -Showtunes
  -Ska
  -Slow Jam
  -Slow Rock
  -Sonata
  -Soul
  -Sound Clip
  -Soundtrack
  -Southern Rock
  -Space
  -Speech
  -Swing
  -Symphonic Rock
  -Symphony
  -Synthpop
  -Tango
  -Techno
  -Techno Industrial
  -Terror
  -Thrash Metal
  -Top 40
  -Trailer
  -Tv Show
  -Tv Drama
  -Tv Commercial
  -Techno

PREAMP RANGE

  [-Infinity db,+Infinity db]

VOLUME

Adjust the Master or channel volume
  
EQUALIZER (Slider-assignments)

  5hz 10hz 20hz 40hz 60hz 80hz 100hz 150hz 200hz 250hz 300hz 400hz 600hz 1khz 2khz 3khz 4khz 6khz 8khz 12khz 14khz 16khz 18khz 20khz

TIMBRES

  Timbres are RegExp-generated but because recognizable, primal sounds & complex frequencies have the greatest emotional affect, most sounds will fall into well-known, defined instruments

SOUND ANALYSIS STEPS

  -intake voice track[s]
  -discern metre
  -discern genre (ref. genre song templates)
  -detect track spectral components for timbre design
  
MOMENTUM CONSIDERATIONS (freq vs program characteristic)

            p0    p1    p2    p3

  f0  -------|-----|-----|-----|------------>
  
  f1  -------|-----|-----|-----|------------> ..Time..
  
  f2  -------|-----|-----|-----|------------>
  
  f3  -------|-----|-----|-----|------------>

  Stage 1 - f0:p0:t0,f1:p1:t0,f2:p2:t0,f3:p3:t0,
  .
  .
  Stage N - Accounting for stage momentum, program settings can be updated or swapped, to create the illusion of timbre

DESIGN NOTES

  -Accept file of any length
  -Index audio samples at freesound.org for [spectral components,psychological impact]
  -Use a waveshaper tool to auto-build requisite frequencies upon demand
  -Music has handed-ness (chirality)
  -Voice tracks should be layered (separate) for accurate frequency analysis
  -Employ a piano-roll neuralnet per timbre / frequency
  -Metronome (earphones), blinking red dot recording light
  -A NNet allows software to learn once without rep: frequency anlysis => timbre => phrasing => movements => song
  -A timbre's low-end program dynamics may require a separate performance character than its higher-end (attack,decay,etc) for its psychological effects
  -Live record or place voice track in DEMO folder, then uploaded, analyzed, and opened as a fully annotated song
  -Finished songs sent to SONGS folder, with a before-hand ability to edit and revise note-data (eg Solo: violin, Mute:Piano7,etc ) 
  -Use Genre's equalizer settings as a hint for spectral components and requisite frequencies to fill 

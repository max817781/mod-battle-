答對音效設定：
1. 全域答對音效：events/mod-battle/audio/correct-sound-effect-128k.mp3
   mod-quiz-data.js 根層 correctAudio 可設定為：audio/correct-sound-effect-128k.mp3

2. q001 專用答對音效：events/mod-battle/audio/quiz_rawr.MP3
   q001 已設定："correctAudio": "audio/quiz_rawr.MP3"

規則：單題 correctAudio 會優先於全域 correctAudio。

Как это делается https://www.twitch.tv/bwallb/videos

﻿Регулярные выражения - какие бывают
1. Математический вид - описание КА eNFA -> NFA -> DFA
2. PCRE 
3. emacs
4. RE 


План работ
1. Определяем интерфейс нашей обработки (Найти, НайтиСледующий) - по переданому регэкспу и строке - возвращаются позицию найдено
2. Интерпретатор регекспа
*3. Определим eNFA и функции работы с ним (генерация DFA по eNFA)
*4. Определим NFA и функции работы с ним
*5. Определим DFA и функции работы с ним


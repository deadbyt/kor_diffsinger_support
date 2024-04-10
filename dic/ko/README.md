# 세부 정보(Details)

- 이 사전은 한국어로 노래를 부르기 위한 사전입니다. 한글과 로마자를 모두 지원합니다.
- 사전은 한국어에서 흔히 볼 수 있는 동적 음소 변환을 지원하지 않으므로 당분간 모든 음절을 발음 그대로 입력해야 합니다.
- 이 사전은 언어에 구애받지 않는 \[DIFF\] 가사 구문 분석기를 사용합니다. 현재 \[DIFF KO\] 가사 구문 분석기가 있지만, \[DIFF KO\] 문서와 사용법은 현재 드물고 명확하지 않으며 지정된 음소 집합도 없는 것으로 보입니다.
- 이전 버전의 사전은 일본어와 중국어를 지원했지만, 이번 버전에는 한국어만 포함되어 있습니다. 몇 가지 이유로 이러한 변경이 이루어졌습니다:
    * OpenUtau에서는 더욱 강력한 언어 지원이 제공됩니다. 즉, 더 많은 가사 구문 분석기가 추가되었고 대부분의 가사 구문 분석기가 사용자 지정 사전을 지원하도록 변경되었습니다.
    * 일본어에서는 한국어 지원이 우선시되는 동안 한국어 음소만으로 「ん」 음절을 만드는 것은 불가능합니다. 이제 일본어는 \[DIFF JA\] 음소화기를 통해 지원되므로 이 문제를 피할 수 있습니다.
    * 병음으로 인해 한국어 사전이 로마자를 지원하지 못함에 따라 중국어가 제거되었습니다. 일본어와 마찬가지로 중국어도 \[DIFF ZH\] 가사 파서로 지원이 옮겨졌습니다.

- This dictionary is for native Korean singing. It supports both Hangul and Romaja.
- Since dictionaries do not support dynamic phoneme transmutations, all syllables will have to be typed exactly as they are pronounced for the time being.
- This dictionary uses the language-agnostic \[DIFF\] phonemizer, as while there is currently a \[DIFF KO\] phonemizer, documentation and usage of said phonemizer is currently sparse and unclear, with seemingly no specified phoneme set.
- While previous versions of this dictionary supported Japanese and Mandarin Chinese, this version only contains Korean. This change was made for a few reasons:
  * More robust linguistic support is available in OpenUtau. Namely that more phonemizers have been added, and most of the phonemizers have been altered to have custom dictionary support.
  * In Japanese, it was impossible to make 「ん」 syllabic using only Korean phonemes while Korean singing takes precedent. Japanese is now supported via the \[DIFF JA\] phonemizer, this way, the issue can be circumvented.
  * Mandarin Chinese was removed, as the presence of Pinyin prevented the Korean dictionary from supporting Romaja. Like Japanese, Mandarin Chinese has also had its support moved to the \[DIFF ZH\] phonemizer.
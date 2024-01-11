# 간소화된 음소 차트(Simplified Phoneme Chart)

## 한국어 음소(Korean Phonemes)

### 모음(Vowels):
| 한글(Hangul) | 음소(Phoneme) |
| :--- | :--- |
| ㅏ | a |
| ㅔ, ㅐ | e |
| ㅣ | i |
| ㅗ | o |
| ㅜ | u |
| ㅓ | eo |
| ㅡ | eu |
| ㅑ | ia |
| ㅖ, ㅒ | ie |
| ㅛ | io |
| ㅠ | iu |
| ㅕ | ieo |
| ㅘ | ua |
| ㅞ, ㅙ, ㅚ | ue |
| ㅟ | ui |
| ㅝ | uo |


### 자음(Consonants):
| 한글(Hangul) | 초기 음소(Initial) | 코다 음소(Coda) |
| :--- | :--- | :--- |
| ㄱ  | g     | kcl |
| ㄲ  | kk    |     |
| ㅋ  | k     |     |
| ㄷ  | d     | tcl |
| ㄸ  | tt    |     |
| ㅌ  | t     |     |
| ㅂ  | b     | pcl |
| ㅃ  | pp    |     |
| ㅍ  | p     |     |
| ㅁ  | m     | m   |
| ㄴ  | n     | n   |
| ㄹ  | rx, l | l   |
| ㅅ  | sc    |     |
| ㅆ  | s     |     |
| ㅈ  | jh    |     |
| ㅉ  | jj    |     |
| ㅊ  | ch    |     |
| ㅎ  | hh    |     |
| ㅇ  |       | ng  |

### 문맥별 음소(Contextual Phonemes):

| 한글(Hangul) | 음소(Phoneme) | 음소 예시(Example) |
| :--- | :--- | :--- |
| 시, 샤, 셰, 쇼, 슈, 셔	| sh | \[sh ia\], \[sh ie\], \[sh ieo\], etc.	|
| 씨, 쌰, 쎼, 쑈, 쓔, 쎠	| sy | \[sy ia\], \[sy ie\], \[sy ieo\], etc.	|
| 야, 예, 요, 유, 여	| y | \[y a\], \[y e\], \[y eo\], etc.      	|
| 와, 웨, 위, 워		| w | \[w a\], \[w e\], \[w eo\], etc.       	|
| ㅢ			| wx | \[wx i\]                         	|
| "끊음"(Glottal Stop)	| q | \[q a\], \[q e\], \[q eo\], etc.		|

### 참고 사항(Notes)

- \[y a\]와 \[ia\]와 같은 조합을 구분하는 이유는 주로 타이밍을 맞추기 위해서입니다. 이 형식은 글라이딩 음소를 지원하는 가사 구문 분석기가 없다고 가정하므로 대부분의 시나리오에서 \[ia\]가 사용됩니다. 그러나 "야"와 같은 문자가 나타날 때는 음표의 길이가 시작되기 전에 \[ia\]의 "i" 부분이 나와야 합니다. 따라서 해당 한글에 \[ia\] 대신 \[y a\]가 사용되는 이유는 \[y\] 음소가 자음으로 인식되고 음표의 지속 시간보다 먼저 발생하기 때문입니다. \[w a\]나 \[ua\]와 같은 음소에도 동일한 원리가 적용됩니다.

- The reason combinations like \[y a\] and \[ia\] are distinguished is primarily for timing purposes. This format assumes there is no Phonemizer with glide support, thus, \[ia\] is used in most scenarios. However, when a character such as 야 appears, the "i" part of \[ia\] needs to occur before the duration of the note begins. Thus why \[y a\] is used for that Hangul instead of \[ia\], as the \[y\] phoneme is recognized as a consonant, and will occur prior to the notes' duration. The same principle applies to phonemes like \[w a\] and \[ua\] as well.

![image](https://github.com/deadbyt/kor_diffsinger_support/assets/93476780/0e45d31b-d626-41a0-88a6-59f86a07db05)


## 영어 음소(English Phonemes)

- 영어 음소는 ARPAbet을 기반으로 하며 해당 형식의 표준을 준수합니다.
- The English phonemes are based on ARPAbet and comply with the standards of that format.

### 모음(Vowels):
| 음소(Phoneme) | 단어 예제(Example Word) | 트랜스크립션(Transcription) | 대략적인 한글 표기법(Closest Korean Equivalent) |
| :--- | :--- | :--- | :--- |
| aa | "job" | \[jh aa b\] | ㅏ |
| ae | "have" | \[hh ae v\] | "ㅏ" 와 "ㅔ" 사이 |
| ah | "cup" | \[k ah p\] | ㅓ |
| ao | "law" | \[l ao\] | ㅗ |
| eh | "leg" | \[l eh g\] | "ㅔ" 또는"ㅐ" |
| er | "burn" | \[b er n\] | "ㅓ" 처럼 + 영어 "r" |
| ih | "this" | \[dh ih s\] | "ㅔ" 와 "ㅣ" 사이 |
| iy | "tree" | \[t r iy\] | ㅣ |
| uh | "could" | \[k uh d\] | "ㅗ" 와 "ㅜ" 사이  |
| uw | "lose" | \[l uw z] | ㅜ |
| ax | "about" | \[ax b aw t\] | 모호한 모음. "ㅓ"와 같이 혀가 입 중앙에 더 가깝게 위치합니다. |
### 디프통(Diphthongs):
| 음소 (Phoneme) | 단어 예제 (Example Word) | 트랜스크립션 (Transcription) | 대략적인 한글 표기법 (Closest Korean Equivalent) |
| :--- | :--- | :--- | :--- |
| aw | "loud" | \[l aw d\] | "ㅏ" + "ㅜ" |
| ay | "like" | \[l ay k\] | "ㅏ" + "ㅣ" |
| ey | "sey" | \[s ey\] | "ㅔ" + "ㅣ" |
| ow | "close" | \[k l ow z\] | "ㅗ" + "ㅜ" |
| oy | "point" | \[p oy n t\] | "ㅗ" + "ㅣ" |


### 자음(Consonants):
| 음소(Phoneme) | 단어 예제(Example Word) | 트랜스크립션(Transcription) | 대략적인 한글 표기법(Closest Korean Equivalent) |
| :--- | :--- | :--- | :--- |
| b | "bar" | \[b aa r\] | ㅂ |
| ch | "chair" | \[ch eh r\] | ㅊ |
| d | "desk" | \[d eh s k\] | ㄷ |
| dx | "butter" | \[b ah dx er\] | '바람'의 'ㄹ'과 비슷합니다. 결코 트릴되지 않습니다. 이 음소는 악센트에 따라 다르며 필수 음소는 아닙니다. |
| dh | "there" | \[dh eh r\] | "ㄷ" 과 같지만 받침이 없어 마찰음이 됩니다. |
| f | "fire" | \[f ay er\] | "ㅜ" 앞에 올 때 "ㅎ" 과 비슷합니다. 두 앞니가 아랫입술에 닿습니다. |
| g | "guest" | \[g eh s t\] | ㄱ |
| hh | "hair" | \[hh eh r\] | ㅎ |
| jh | "just" | \[jh ah s t\] | ㅈ |
| k | "kid" | \[k ih d\] | ㅋ |
| l | "lead" | \[l iy d\] | "발레"에서 "ㄹ"과 같이 |
| m | "miss" | \[m ih s\] | ㅁ |
| n | "net" | \[n eh t\] | ㄴ |
| ng | "bring" | \[b r ih ng\] | ㅇ |
| q | "uh-oh" | \[ah q ow\] | 끊음 |
| p | "poor" | \[p uh r\] | ㅍ |
| r | "race" | \[r ey s\] | (나중에 작성 예정 ;w; ) |
| s | "sale" | \[s ey l\] | ㅆ |
| sh | "share" | \[sh eh r\] | ㅅ |
| t | "town" | \[t aw n\] | ㅆ |
| th | "thumb" | \[th ah m\] | 리스프로 'ㅅ'을 발음하는 것과 같습니다. |
| v | "vase" | \[v ey s\] | 유성 영어 "f". 앞니가 아랫입술에 닿습니다. |
| w | "wear" | \[w eh r\] | "와", "웨", "위", "워" 의 첫소리와 같이 |
| y | "you" | \[y uw\] | "야", "예", "요", "유", "여" 의 첫소리와 같이 |
| z | "zoo" | \[z uw\] | 유성 "ㅆ" |
| zh | "genre" | \[zh aa n r ah\] | 유성 "ㅅ" |

### 참고 사항(Notes)

- \[i\] & \[iy\], \[u\] & \[uw\]는 별개의 소리로 취급됩니다. 반드시 분리해야 하는 것은 아니지만, 분리하는 논리는 두 가지입니다.
  * 첫 번째 이유는 영어와 한국어 데이터셋을 보다 깔끔하게 구분하여, 충분한 데이터가 주어지면 DiffSinger가 언어별 음소에 대한 특정 조음을 깔끔하게 구분할 수 있도록 하기 위해서입니다. 예를 들어 영어에서는 \[k\]가 문맥에 따라 흡음과 비흡음으로 발음되는 반면, 한국어에서는 \[k\]만 흡음으로 발음되고 \[kk\]는 비흡음으로 발음됩니다. 영어와 한국어의 모음 세트가 완전히 다르기 때문에 영어 모음 앞의 \[k\]는 문맥에 따라 흡기되는 반면, 한국어 모음 앞의 \[k\]는 항상 흡기된다는 것을 DiffSinger가 알 수 있습니다.
  * 두 번째 이유는 영어에서 \[iy\]와 \[uw\]의 발음 때문입니다. 영어에서 화자들은 이 모음을 이중모음처럼 발음하여 종종 "/ɪi/"와 "/ʊu/"처럼 들리는 경우가 많습니다. 간단한 /i/ 및 /u/도 영어에서 똑같이 유효하므로 이러한 소리를 발음하는 데 필수적이거나 필수적인 것은 아닙니다. 그러나 이는 일반적인 행동이며 한국어 발음의 악센트에 부정적인 영향을 미칠 수 있습니다. 또한 일부 한국어->영어 사용자들은 한국어 \[u\]와 \[eu\]를 무분별하게 영어 \[uw\]로 사용하는 경향이 있습니다. \[uw\]를 고유 음소로 만들면 DiffSinger가 이러한 특성을 고려하는 데 도움이 될 것입니다.
- \[i\] & \[iy\] 및 \[u\] & \[uw\]의 발음이 일관되고 자음 조음에 문제가 발생하지 않는다고 확신하는 경우 레이블을 지정하는 동안 안전하게 병합할 수 있습니다. 이를 고려하기 위해 dsdict-en.yaml 파일 하단에 다음 코드 줄을 추가하여 \[DIFFS EN\] Phonemizer에서 ARPAbet을 준수하도록 할 수 있습니다.
  ```
  replacements:
  {from: iy, to: i}
  {from: uw, to: u}
  ```

- \[i\] & \[iy\] and \[u\] & \[uw\] are treated as separate sounds. It is not absolutely essential to separate them, but the logic behind doing so is twofold.
  * The first reason is so that the English and Korean datasets are more neatly divided, that way, given enough data, DiffSinger should neatly be able to discern specific articulation for language-specific phonemes. For example, in English, \[k\] is pronounced as both aspirated and unaspirated depending on the context, whereas in Korean, only \[k\] is aspirated, whereas \[kk\] is unaspirated. Allowing English and Korean to have completely different sets of vowels allows DiffSinger to know that \[k\] preceding an English vowel is contextually aspirated, whereas \[k\] preceding a Korean vowel is always aspirated.
  * The second reason is due to the articulation of \[iy\] and \[uw\] in English. Many times in English, speakers diphthongize these vowels, to where they often sound more like /ɪi/ and /ʊu/. This is not a requirement, or essential to pronouncing these sounds, as simple /i/ and /u/ are equally valid for English. However, it is a common behavior, and may affect the accent for Korean pronunciation negatively. In addition, some Korean->English speakers sometimes tend to use both the Korean \[u\] and \[eu\] as English \[uw\] indiscriminately, so making \[uw\] its own phoneme should help account for such traits.
- If you are confident that the pronunciation of \[i\] & \[iy\] and \[u\] & \[uw\] will be consistent and not cause problems with consonant articulation, then you can safely merge them while labeling. To account for this, you can add the following lines to the bottom of the dsdict-en.yaml file to help it conform to ARPAbet in the \[DIFFS EN\] Phonemizer.
  ```
  replacements:
  {from: iy, to: i}
  {from: uw, to: u}
  ```

## 기타 음소(Misc. Phonemes)

| 음소(Phoneme) | 설명(Description) |
| :--- | :--- |
| AP | 호흡(Breath) |
| SP | 침묵(Silence) |
| cl | 일본어의 자음 확장형「っ」(Gemination, like Japanese 「っ) |
| vf | 보컬 프라이(Vocal Fry) |
| axh | 음성 호흡 또는 양식화된 호흡(Voiced or Stylized End-Breath)|
| exh | 끝 호흡(End-Breath)|

# 간소화된 음소 차트(Simplified Phoneme Chart)

## 한국어 음소(Korean Phonemes)

### 모음(Vowels):
| 한글<br>(Hangul) | 음소<br>(Phoneme) | 가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- |
| ㅏ | a | "ah" in "soft" |
| ㅔ, ㅐ | e | "eh" like in "head" |
| ㅣ | i | "ee" as in "see" |
| ㅗ | o | "o" as in "four" |
| ㅜ | u | "ooh" as in "food" |
| ㅓ | eo | "uh" as in "but" |
| ㅡ | eu | Like English "ooh", but the lips are unrounded and not pursed |
| ㅑ | ia | Like English "yah!", like an action hero |
| ㅖ, ㅒ | ie | Like "ye" as in "yes" |
| ㅛ | io | "yo" like in "fjord" |
| ㅠ | iu | Like English "you" |
| ㅕ | ieo | Like "yuh" |
| ㅘ | oa | Like "wa" as in "water" |
| ㅞ, ㅙ, ㅚ | oe | Like "we" as in "wet" |
| ㅟ | ui | Like English "we" |
| ㅝ | uo | Like English "wuh" as in "what" |


### 자음(Consonants):
| 한글(Hangul) | 초기 음소(Initial) | 코다 음소(Coda) | 가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- | :--- |
| ㄱ  | g     | kcl | "g" as in "game". In the coda position, the consonant is unreleased, meaning your mouth preps to pronounce a "g", but never actually releases the sound. |
| ㄲ  | kk    |     | Unaspirated "k" as in "skip" |
| ㅋ  | k     |     | Aspirated "k" as in "kite" |
| ㄷ  | d     | tcl | "d" as in "day". In the coda position, the consonant is unreleased, meaning your mouth preps to pronounce a "d", but never actually releases the sound. |
| ㄸ  | tt    |     | Unaspirated "t" as in "stay" |
| ㅌ  | t     |     | Aspirated "t" as in "talk" |
| ㅂ  | b     | pcl | "b" as in "best". In the coda position, the consonant is unreleased, meaning your mouth preps to pronounce a "b", but never actually releases the sound. |
| ㅃ  | pp    |     | Unaspirated "p" as in "spill" |
| ㅍ  | p     |     | Aspirated "p" as in "pie" |
| ㅁ  | m     | m   | "m" as in "me" |
| ㄴ  | n     | n   | "n" as in "nine" |
| ㄹ  | rx, l | l   | In the initial position, it is pronounced similar to how Americans pronounce "tt" as in "butter", or like a Spanish "r". In the coda position, or when it's doubled-up, it is pronounced like "l" as in "like" |
| ㅅ  | sc    |     | Like English "s" as in "say", but more relaxed. |
| ㅆ  | s     |     | Like English "s" as in "say". More tense than \[sc\] |
| ㅈ  | jh    |     | Like English "j" as in "just" |
| ㅉ  | jj    |     | Like English "j" as in "just", but more tense. Almost like a "ch" |
| ㅊ  | ch    |     | Like English "ch" as in "chance" |
| ㅎ  | hh    |     | Like English "h" as in "hair". Articulation differs slightly depending on the vowel in Korean. |
| ㅇ  |       | ng  | Like English "ng" as in "sing |

### 문맥별 음소(Contextual Phonemes):

| 한글(Hangul) | 음소(Phoneme) | 음소 예시(Example) | 가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- | :--- |
| 시, 샤, 셰, 쇼, 슈, 셔	| sh | \[sh ia\], \[sh i\], \[sh ieo\], etc.	| Like English "sh" as in "share" |
| 씨, 쌰, 쎼, 쑈, 쓔, 쎠	| sy | \[sy ia\], \[sy i\], \[sy ieo\], etc.	| Like English "sh" as in "share", more tense than \[sh\] |
| 야, 예, 요, 유, 여,	얘 | y | \[y a\], \[y e\], \[y eo\], etc. | Like English "y" as in "yell" |
| 와, 웨, 위, 워	, 왜, 외 | w | \[w a\], \[w e\], \[w eo\], etc. | Like English "w" as in "wait" |
| 의	| wx | \[wx i\] | Like English "w" as in "we". However, compared to \[ui\] the lips should not tense up much when pronouncing it, and remained unrounded and unpursed. |
| "끊음"(Glottal Stop)	| q | \[q a\], \[q e\], \[q eo\], etc.| Like the pause in "uh-oh" |

### 참고 사항(Notes)

#### \[y a\] vs. \[ia\], \[w a\] vs. \[ua\], etc.

- \[y a\]와 \[ia\]와 같은 조합을 구분하는 이유는 주로 타이밍을 맞추기 위해서입니다. 이 형식은 글라이딩 음소를 지원하는 가사 구문 분석기가 없다고 가정하므로 대부분의 시나리오에서 \[ia\]가 사용됩니다. 그러나 "야"와 같은 문자가 나타날 때는 음표의 길이가 시작되기 전에 \[ia\]의 "i" 부분이 나와야 합니다. 따라서 해당 한글에 \[ia\] 대신 \[y a\]가 사용되는 이유는 \[y\] 음소가 자음으로 인식되고 음표의 지속 시간보다 먼저 발생하기 때문입니다. \[w a\]나 \[ua\]와 같은 음소에도 동일한 원리가 적용됩니다.

- The reason combinations like \[y a\] and \[ia\] are distinguished is primarily for timing purposes. This format assumes there is no Phonemizer with glide support, thus, \[ia\] is used in most scenarios. However, when a character such as 야 appears, the "i" part of \[ia\] needs to occur before the duration of the note begins. Thus why \[y a\] is used for that Hangul instead of \[ia\], as the \[y\] phoneme is recognized as a consonant, and will occur prior to the notes' duration. The same principle applies to phonemes like \[w a\] and \[ua\] as well.

![image](https://github.com/deadbyt/kor_diffsinger_support/assets/93476780/0e45d31b-d626-41a0-88a6-59f86a07db05)

#### 음소 트랜스무타(Phoneme Transmutation)

- 한국어에는 특정 소리의 발음이 바뀌는 경우가 있습니다. 예를 들어, '가'는 평상시에는 \[g a\] 처럼 발음되지만, 구의 시작 부분에서는 \[k a\] 로 발음됩니다. AI는 이러한 문맥상의 차이를 고려할 수 있지만, 일본어 및 기타 여러 언어의 일관된 발음과 사용 편의성을 위해 전자의 예는 \[g a\]로, 후자의 예는 \[k a\]로 레이블을 지정하는 것이 좋습니다.

- There are certain occasions in Korean at which the articulation of certain sounds change. For example, "가" is pronounced like \[g a\] normally, but is pronounced \[k a\] at the beginning of a phrase. While AI can account for these contextual differences, it is recommended to label the former example as \[g a\] and the latter example as \[k a\], to ensure consistent pronunciation, and ease of use for Japanese.

#### 디프통(Diphthongs)

- 이는 필수 사항이 아닌 제안 사항입니다. 단, 한국어에서 이중 모음 또는 비음절 모음이 나오는 경우("ABC..."의 "A"와 같이), \[y\] 및 \[w\] 소리는 코다 위치에서 자음으로 다른 용도가 없으므로 적절한 경우 후자의 모음을 \[y\] 또는 \[w\]로 표시하는 것이 좋습니다.<br>예시\:<br>"A" -> \[e y\]

- This is merely a suggestion, and not a requirement. However, when diphthongs or nonsyllabic vowels occur in a Korean dataset (such as the "A" in "ABC..."), it is recommended to mark the latter vowel as \[y\] or \[w\] where appropriate, as the \[y\] and \[w\] sounds have no other use as consonants in coda position.<br>Example\:<br>"A" -> \[e y\]


## 영어 음소(English Phonemes)

- 영어 음소는 ARPAbet을 기반으로 하며 해당 형식의 표준을 준수합니다.
- The English phonemes are based on ARPAbet and comply with the standards of that format.

### 모음(Vowels):
| 음소<br>(Phoneme) | 단어 예제<br>(Example Word) | 트랜스크립션<br>(Transcription) | 대략적인 한글 표기법<br>(Closest Korean Equivalent) |
| :--- | :--- | :--- | :--- |
| aa | "job" | \[jh aa b\] | ㅏ |
| ae | "have" | \[hh ae v\] | "ㅏ" 와 "ㅐ" 사이 |
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
| 음소<br>(Phoneme) | 단어 예제<br>(Example Word) | 트랜스크립션<br>(Transcription) | 대략적인 한글 표기법<br>(Closest Korean Equivalent) |
| :--- | :--- | :--- | :--- |
| aw | "loud" | \[l aw d\] | "ㅏ" + "ㅜ" |
| ay | "like" | \[l ay k\] | "ㅏ" + "ㅣ" |
| ey | "say" | \[s ey\] | "ㅔ" + "ㅣ" |
| ow | "close" | \[k l ow z\] | "ㅗ" + "ㅜ" |
| oy | "point" | \[p oy n t\] | "ㅗ" + "ㅣ" |


### 자음(Consonants):
| 음소<br>(Phoneme) | 단어 예제<br>(Example Word) | 트랜스크립션<br>(Transcription) | 대략적인 한글 표기법<br>(Closest Korean Equivalent) |
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
| r | "race" | \[r ey s\] | 영어 "r". 모음과 비슷하며 혀끝이 입의 어느 부분에도 닿지 않아야 합니다. 혀 끝은 두 개의 앞니 근처에서 구부러지거나 일종의 'C'자 모양으로 목 뒤쪽을 향하게 할 수 있습니다. 노래할 때는 "dark" 또는 "shared" 와 같이 어미 자음으로 약하게 들리는 경우가 많습니다. |
| s | "sale" | \[s ey l\] | ㅆ |
| sh | "share" | \[sh eh r\] | "시", "샤", "셰"에서와 같이 "ㅅ" 등 |
| t | "town" | \[t aw n\] | ㅌ |
| th | "thumb" | \[th ah m\] | "ㅅ"과 비슷하지만 리스프가 굵습니다. |
| v | "vase" | \[v ey s\] | 유성 영어 "f". 앞니가 아랫입술에 닿습니다. |
| w | "wear" | \[w eh r\] | "와", "웨", "위", "워" 의 첫소리와 같이 |
| y | "you" | \[y uw\] | "야", "예", "요", "유", "여" 의 첫소리와 같이 |
| z | "zoo" | \[z uw\] | 유성 "ㅆ" |
| zh | "genre" | \[zh aa n r ah\] | "시", "샤", "셰" 등의 "ㅅ"과 같지만 유성음입니다. |

### 참고 사항(Notes)

  #### <ins>\[i\] & \[iy\], \[u\] & \[uw\]</ins>

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

  #### <ins>R색 모음(R-Colored Vowels)</ins>

  - 영어에는 "R색 모음"이라고도 하는 것이 있습니다. 이러한 모음은 ARPAbet에서 개별 음소로 표시되지 않으며, 일반적으로 AI SVS의 목적상 중복됩니다. 하지만 레이블을 지정할 때 이러한 소리가 발생할 때 레이블을 지정하는 방법을 알아두는 것이 좋습니다. 아래에 몇 가지 예와 일반적으로 어떻게 레이블을 지정해야 하는지 설명했습니다.

    * "ar": "dark", "car" 또는 "start"에서와 같이. \[aa r\]로 표시해야 함.<br>dark -> \[d aa r k\], car -> \[k aa r\], start -> \[s t aa r t\]

    * "ehr": "bears", "scared" 또는 "hair"와 같이. \[eh r\]로 표시해야 함.<br>곰 -> \[b eh r z\], 겁먹다 -> \[s k eh r d\], 머리 -> \[hh eh r\]

    * "ir": "fear", "beard" 또는 "cheers"에서와 같이. \[ih r\]로 표시해야 함.<br>fear -> \[f ih r\], beard -> \[b ih r d\], cheers -> \[ch ih r z\], 

    * "or": "four", "lord", "doors"과 같이. \[ao r\]로 표시해야 함.<br>four -> \[f ao r\], lord -> \[l ao r d\], doors -> \[d ao r z\]

    * "ur": "poor", "cured" 또는 "tours"에서와 같이. \[uh r\]로 표시해야 함. 이 소리가 포함되어야 하는 단어는 발화자에 따라 \[er\] 또는 \[ao r\]로 발음하는 경우가 많습니다. 이러한 경우 정확하게 표기할지 아니면 \[uh r\]로 표기할지 잘 판단해 주세요.<br>poor -> \[p uh r\], cured -> \[k y uh r d\], tours -> \[t uh r z\]

  - 영어 사용자들은 이러한 R 색깔 모음을 \[ih r\] 대신 \[iy r\], \[uh r\] 대신 \[uw r\]과 같이 다른 방식으로 발음하는 경우가 많지만, 이러한 경우에도 일반적으로 각각 \[ih r\]과 \[uh r\]로 표기해야 합니다. 이는 'r'이 매우 약하게 들리거나 아예 없는 비운율 악센트에도 적용됩니다 (예: "dark"가 \[d aa k\]처럼 발음되는 경우에도 \[d aa r k\]로 표시해야 함). 유일한 예외는 "be right"(\[b iy\] \[r ay t\]) 또는 "do wrong"(\[d uw\] \[r ao ng\]) 와 같이 단어가 모음으로 끝나고 "r"로 시작하는 경우로, 이는 R색 모음으로 간주되지 않으므로 예외로 합니다.


  - In English, there are also what are known as "R-colored vowels". These are not represented in ARPAbet, and are usually redundant for the purposes of AI SVS. However, when labeling, it is good to know how to label these sounds when they occur. I have given some examples below, and how they should usually be labelled.

    * "ar": like in "DARK", "CAR", or "START". Should be labelled as \[aa r\]<br>dark -> \[d aa r k\], car -> \[k aa r\], start -> \[s t aa r t\]

    * "ehr": like in "BEARS", "SCARED", or "HAIR". Should be labelled as \[eh r\]<br>bear -> \[b eh r z\], scared -> \[s k eh r d\], hair -> \[hh eh r\]

    * "ir": like in "FEAR", "BEARD", or "CHEERS". Should be labelled as \[ih r\]<br>fear -> \[f ih r\], beard -> \[b ih r d\], cheers -> \[ch ih r z\]

    * "or": like in "FOUR", "LORD", or "DOORS". Should be labelled as \[ao r\]<br>four -> \[f ao r\], lord -> \[l ao r d\], doors -> \[d ao r z\]

    * "ur": like in "POOR", "CURED", or "TOURS". Should be labelled as \[uh r\]. Words which should contain this sound are often instead pronounced with \[er\] or \[ao r\] depending on the speaker. Use your best judgement on whether to label it accurately or as \[uh r\] in such cases.<br>poor -> \[p uh r\], cured -> \[k y uh r d\], tours -> \[t uh r z\]

  - English speakers often pronounce R-colored vowels in different ways, such as \[iy r\] instead of \[ih r\], or \[uw r\] instead of \[uh r\], but even in these cases, they should generally be written as \[ih r\] and \[uh r\] respectively. This also applies to non-rhotic accents, where the "r" sounds very weak or is missing altogether ( e.g., if "DARK" is pronounced like \[d aa k\], you still should label it \[d aa r k\] ). The only exception is when a word ends with a vowel and begins with "r", such as "be right" (\[b iy\] \[r ay t\]) or "do wrong" (\[d uw\] \[r ao ng\]), as these are not considered R-colored vowels.

## 일본어 음소(Japanese Phonemes)

### 모음(Vowels):
| 가명<br>(Kana) | 음소<br>(Phoneme) |  대략적인 한글 표기법<br>(Closest Korean Equivalent) | 가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- | :--- |
| あ | a | ㅏ | Most similar to "ah" in "soft" |
| い | i | ㅣ | "ee" as in "see" |
| う | ux | 입모양 "ㅜ"를를 유지한 채로 "ㅡ" 발음을 내면 유사한 소리가 납니다. | Like English "ooh", but the lips are unrounded and not pursed |
| え | e | ㅔ | "eh" like in "head" |
| お | o | ㅗ | "o" as in "four" |
| ん | nn | ㄱ,ㅋ,o,ㅎ의 앞에서는는 "ㅇ" / ㄴ,ㄷ,ㄹ,ㅅ,ㅈ,ㅊ,ㅌ의 앞에서는 "ㄴ" / ㅁ,ㅂ,ㅍ앞에서는 "ㅁ" 소리가 납니다. | Syllabic "n" |
| (き)ゃ | ia | ㅑ | Like English "yah!", like an action hero |
| (き)ゅ | iux | 입모양 "ㅜ"를를 유지한 채로 "ㅣ" + "ㅡ"를 빠르게 발음하면 유사한 소리가 납니다. | Like English "you", but the lips are unrounded and not pursed |
| (き)ぇ | ie | ㅖ | Like "ye" as in "yes" |
| (き)ょ | io | ㅛ | "yo" like in "fjord" |
#### 선택적 모음 음소(Optional Vowel Phonemes):
| 가명<br>(Kana) | 음소<br>(Phoneme) | 대략적인 한글 표기법<br>(Closest Korean Equivalent)  |가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- | :--- |
| くぁ | ua | "ㅜ" + "ㅏ". | Like "wa" as in "water". |
| くぃ | ui | ㅟ | Like English "we" |
| くぇ | ue | "ㅞ"와 비슷합니다. | Like English "weh" as in "wet" |
| くぉ | wo | "ㅜ" + "ㅗ" | Like English "wo" as in "warm". |


### 자음(Consonants):
| 음소<br>(Phoneme) | 가명<br>(Kana) | 트랜스크립션<br>(Transcription) | 대략적인 한글 표기법<br>(Closest Korean Equivalent) |  가장 가까운 영어 등가물<br>(Closest English Equivalent) |
| :--- | :--- | :--- | :--- | :--- |
| k | かきくけこ | \[k a\] | ㅋ | "k" as in "kite". |
| g | がぎぐげご | \[g a\] | ㄱ | "g" as in "game". |
| s | さすせそ | \[s a\] | ㅆ | "s" as in "say". |
| t | たてと | \[t a\] | ㅌ | "t" as in "talk" |
| d | だでど | \[d a\] | ㄷ | "d" as in "day" |
| dz | ざずぜぞ | \[dz a\] | 영어 "z" | "z" like in "zone" or "dz" like in "beds" |
| hh | はひへほ | \[hh a\] | ㅎ | Like English "h" as in "hair". |
| b | ばびぶべぼ | \[b a\] | ㅂ | "b" as in "best". |
| p | ぱぴぷぺぽ | \[p a\] | ㅍ | "p" as in "pie". |
| m | まみむめも | \[m a\] | ㅁ | "m" as in "me". |
| y | やゆよ | \[y a\] | 야, 유, 요 | "y" as in "yell" |
| rl | らりるれろ | \[rl a\] | ㄹ | It is pronounced similar to how Americans pronounce "tt" as in "butter", or like a Spanish "r". The sound often fluctuates between this and being pronounced like an "l" as in "light" indiscriminantly. |
| sh | し | \[sh i\] | 시 | Like English "sh" as in "share" |
| ch | ち | \[ch i\] | ㅊ | Like English "ch" as in "chance" |
| ts | つ | \[ts ux\] | 영어 "ts" | Like English "ts" as in "lets" |
| dj | じ | \[dj i\] | ㅈ | Similar to English "zh" as in "measure" or English "j" as in "just" |
| fh | ふ | \[fh ux\] | 영어 "f" | Similar to English "f" as in "fan". Front teeth do not touch the bottom lip. |
| w | わ | \[w a\] | 와 | Like English "w" as in "wait". |
| v | ヴ | \[v u\] | 영어 "v" | Like English "v" as in "vase". |
| cl | っ(か) | \[cl k a\] | 받침 ㄱ,ㄷ,ㅂ | Consonant Gemination, similar to how "k" is elongated in "bookkeeper" or "n" in "unknown". |


### 참고 사항(Notes)

  #### <ins>\[dx\] vs \[rx\] vs \[rl\]</ins>

  - \[dx\], \[rx\], \[rl\]은 모두 매우 유사하지만 DB-KOR에서 다른 소리로 간주되는 데에는 몇 가지 이유가 있습니다.
    * \[rl\]의 범위는 종종 /ɾ/에서 /l/ 음소까지 다양합니다. 한국어의 \[rx\]도 비슷하지만 문맥과 주변 음소에 더 많이 의존합니다. \[dx\]은 /ɾ/로만 발음되며 /l/로 발음되지 않습니다. 가벼운 음성 불일치 외에도 같은 음소로 병합된 경우 타이밍 모델에 문제가 발생할 수 있습니다.
	*  또한 한국어에서는 일부 화자들이 \[rx\]를 약하게 떠는 소리로 발음하는 반면, \[rl\]은 음소적으로 그렇게 발음하는 경우가 거의 없으며 \[dx\]는 절대 그렇게 발음하지 않습니다.

  - Each of these sounds are very similar, but there are a couple reasons they are considered different sounds here.
    * \[rl\] often ranges from an /ɾ/ to /l/ indiscriminately. \[rx\] in Korean has a similar behavior, but is more dependent on context and surrounding phonemes. \[dx\] is exclusively pronounced as /ɾ/ and never as /l/. Besides the mild phonetic inconsistency, it may also cause issues with the timing model if they were merged as the same phoneme.
	* Additionally, in Korean, some speakers pronounce \[rx\] with a mild trill, whereas \[rl\] is rarely pronounced that way phonemically, and \[dx\] is never pronounced this way.

	
  #### <ins>\[k\] & \[kk\], \[t\] & \[tt\], \[p\] & \[pp\]</ins>
  - 일본어에서 파열음의 기술적 음소 발음은 한국어의 'ㄲ', 'ㄸ', 'ㅃ'와 가장 유사합니다. 하지만 트위터에서 @malcha_utau가 진행한 설문조사에 따르면 압도적으로 많은 한국어 사용자가 일본어로 말할 때 각각 한국어 \[ㅋ\], \[ㅌ\], \[ㅍ\]으로 발음하는 것으로 나타났습니다. 이 형식은 주로 한국어 화자가 사용하기 위해 고안되었으며 일본어 파열음의 일반적인 유연성을 고려하여 \[ㅋㅋ\], \[ㅌ\], \[ㅍ\] 음소가 일본어에 대응하는 음소를 나타내도록 결정되었습니다. 그러나 화자가 'ㄲ', 'ㄸ', 'ㅃ'의 발음을 선호하는 경우, 이러한 경우를 위한 사전도 준비되어 있으며, [여기](https://github.com/deadbyt/kor_diffsinger_support/tree/main/dic/ja/Alt)에서 확인할 수 있습니다.
  
  - In Japanese, the technical phonemic pronunciation of devoiced plosives is most similar to Korean \[kk\], \[tt\], and \[pp\]. However, a survey hosted by @malcha_utau on Twitter suggests that the overwhelming majority of Korean speakers pronounce them as their Korean \[k\], \[t\], and \[p\] respectively when speaking Japanese. Due to this format being designed primarily for use by Korean speakers, and the general flexibility of Japanese plosives, it was decided that \[k\], \[t\], and \[p\] would represent their Japanese counterparts. However, in the event that a speaker should prefer the pronunciation of \[kk\], \[tt\], and \[pp\], we have a dictionary prepared for such cases as well, which can be found [here](https://github.com/deadbyt/kor_diffsinger_support/tree/main/dic/ja/Alt).

  #### <ins>일본어의 \[ia\], \[iux\], \[ie\], \[io\]에 대한 컨텍스트. (Context for using \[ia\], \[iux\], \[ie\], \[io\] in Japanese)</ins>

  - 구개음화된 자음의 경우 대부분 각각 \[ia\], \[iux\], \[ie\], \[io\]로 표시합니다(きゃ\[k ia\], ぴゅ\[p iux\], りょ\[rl io\] 등 ). 단, 「し」, 「ち」, 「じ」, 「ぢ」가 포함된 가나는 이 규칙을 따르지 않는데, 이 경우 "i"의 음이 약하기 때문입니다. 이런 경우에는 다음과 같이 표기해야 합니다:
    * しゃ -> \[sh a\]
    * ちゅ -> \[ch ux\]
    * じょ -> \[dj o\]
    * ぢぇ -> \[dj e\]
  
  - Most cases of palatilized consonants are marked with \[ia\], \[iux\], \[ie\], and \[io\] respectively ( きゃ\[k ia\], ぴゅ\[p iux\], りょ\[rl io\], etc ). However, Kana containing 「し」, 「ち」, 「じ」, or 「ぢ」 do not follow this rule, as the "i" sound is weak in these cases. When you encounter this, these should be transcribed like so:
    * しゃ -> \[sh a\]
    * ちゅ -> \[ch ux\]
    * じょ -> \[dj o\]
    * ぢぇ -> \[dj e\]

## 기타 음소(Misc. Phonemes)

| 음소(Phoneme) | 설명(Description) |
| :--- | :--- |
| AP | 호흡(Breath) |
| SP | 침묵(Silence) |
| cl | 일본어의 자음 확장형「っ」(Gemination, like Japanese 「っ」) |
| vf | 보컬 프라이(Vocal Fry) |
| axh | 음성 호흡 또는 양식화된 호흡(Voiced or Stylized End-Breath)|
| exh | 끝 호흡(End-Breath)|

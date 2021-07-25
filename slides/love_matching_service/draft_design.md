---
theme: uncover
---

<!--
_color: white
-->

![bg brightness:0.6](lion_pair.jpg)

# LLoMa

Service設計編

---

1. Target
2. Persona
3. User Incentive
4. KSF

---

# Target

希薄な人間関係を希望する人達。
若者と2ch全盛期付近の人間が当てはまるとおもってる。

---

# Persona

1. 岡田太郎(30)
* 趣味: Social Game、動画試聴。
* 職業: SE
* Life Style(仕事除)
  * Social Game主体。
  * 自宅にいることが多い。
* 性格: 批判的。
* 悩み: 彼女がいない。
* SNS: Twitter。

---

### Persona

# Personality

着本的にfake news等に流されにくい、netに強い、やればできる、自分以外が間違っている

と思い込んでいる。

論理的と思い込んでいるが、割と感情的。

自分の意思を抑制するのがうまい。

何かの表紙で爆発する可能性も有。

---

### Persona

# Digital Profile

殆どの場合携帯、Tabletにて情報収集を行う。

明らさまな嘘情報にはひっかからない。

がSourceまでは確認しないままRTしたりする。

literacyは高いと思い込んでいるが、普通より少し高い程度。

嘘情報は普通に拡散するし、信用もする。

---

# Persona

2. 栗山金子(30)
* 趣味: Anime, Game, Dojin
* 職業: 事務員
* Life Style(仕事除)
  * 割とEvent等で外界へ赴く。
* 性格: 批判的。
* 悩み: 彼氏がいない。
* SNS: Twitter。

---

### Persona

# Personality

人間関係は基本的に薄く、そつなく程度。

人間関係が下手なわけではない。消費MPが他人と比べて多く、

かつ節約できることを理解した上で立ち回っている。

趣味、興味のないものに感情をださない。

同士(趣味があう人間)にはかなり感情的になる(早口的な意味で)。

---

### Persona

# Digital Profile

携帯、tablet, PCで検索を行う。

literacyは比較的高い。

嘘情報以前に政治、宗教系の話題にはふれない。

---

# Persona

3. 橋本優(30)
* 趣味: Anime, Game, Dojin
* 職業: Programmer
* Life Style(仕事除)
  * Hardware全般のDIY。
* 性格: 温厚。
* 悩み: 最近推しのVが引退した。
* SNS: Twitter、Mastodon

---

### Persona

# Personality

職場の変な人達に分類される。故に同じ変な人たちとは仲良し。

TwitterではHardware界隈でかなり有名でFollowerが多数いる。

---

### Persona

# Digital Profile

携帯、tablet, PCで検索を行う。

literacyはかなり高い。

論理的思考はもちろん、Souceの裏取りまで行う。

英語も読める。

---

# User Incentive

* 匿名で活動できる。

	使い捨てUserで利用できるServiceも存在する。

* 現実世界に介入してこない。

* くそみたいなMail Magazineを送ってこない。

	送るにしてもDefaultでは送らないようにする。

* 終始軽量な構成。

	守れない場合はこれを閉じるか、別ServiceとしてForkする。

---

# KSF

* 変更反映速度向上

* Bug抑制

	Test導入。

* Shuffle Matchingの満足感

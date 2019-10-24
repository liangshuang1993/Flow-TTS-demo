---
layout: default
---


# Audio samples of "FLOW-TTS: A NON-AUTOREGRESSIVE NETWORK FOR TEXT TO SPEECH BASED ON FLOW"

<!-- ## Authors

Chenfeng Miao*
Shuang Liang*
Minchuan Chen
Jun Ma
Shaojun Wang
Jing Xiao

<font size=2>\**Equal contribution.*</font> -->

## Abstract

In this work, we propose Flow-TTS, a non-autoregressive end-to-end neural TTS model based on generative flow. Unlike other non-autoregressive models, Flow-TTS can achieve high-quality speech generation by using a single feed-forward network. To our knowledge, Flow-TTS is the first TTS model utilizing flow in spectrogram generation network and the first non-autoregssive model which jointly learns the alignment and spectrogram generation through a single network. Experiments on LJSpeech show that the speech quality of Flow-TTS heavily approaches that of human and is even better than that of autoregressive model Tacotron 2 (outperforms Tacotron 2 with a gap of 0.09 in MOS). Meanwhile, the inference speed of Flow-TTS is about 23 times speed-up over Tacotron 2, which is comparable to FastSpeech.

### We compare our method with [Tacotron 2](https://arxiv.org/abs/1712.05884) and [FastSpeech](https://arxiv.org/abs/1905.09263). All of the audio samples use [WaveGlow](https://arxiv.org/abs/1811.00002v1) as vocoder.


I will quote an extract from the reverend gentleman's own journal.


**GT** &emsp **GT(WaveGlow)** &emsp **Flow-TTS** 

<td><audio controls=""><source src="demos/proposed/F2M/p293_117.wav" type="audio/wav"></audio></td>
<td><audio controls=""><source src="demos/proposed/F2M/p360_005.wav" type="audio/wav"></audio></td>
<td><audio controls=""><source src="demos/baseline/baseline-adaptive-vc/F2M/293-360-117.wav" type="audio/wav"></audio></td>


 **Tacotron 2**  **FastSpeech**


<td><audio controls=""><source src="demos/proposed/F2M/293_360_117.wav" type="audio/wav"></audio></td>
<td><audio controls=""><source src="demos/proposed/F2M/293_360_117.wav" type="audio/wav"></audio></td>
<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->


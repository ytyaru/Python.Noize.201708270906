# このソフトウェアについて

Pythonでノイズ音を生成してみた。

# 実行

```sh
$ python noise_generator_pyaudio.py
```

`res/`配下に音声ファイルが出力される。

# ノイズ音

ノイズ色|Player
--------|------
white|<audio controls><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/wav/white.wav><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/flac/white.flac><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/ogg/white.ogg><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/mp3/white.mp3></audio>
pink|<audio controls><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/wav/pink.wav><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/flac/pink.flac><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/ogg/pink.ogg><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/mp3/pink.mp3></audio>
blue|<audio controls><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/wav/blue.wav><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/flac/blue.flac><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/ogg/blue.ogg><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/mp3/blue.mp3></audio>
brown|<audio controls><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/wav/brown.wav><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/flac/brown.flac><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/ogg/brown.ogg><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/mp3/brown.mp3></audio>
violet|<audio controls><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/wav/violet.wav><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/flac/violet.flac><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/ogg/violet.ogg><source src=https://raw.githubusercontent.com/ytyaru/Python.Noize.201708270906/master/res/noize/mp3/violet.mp3></audio>

# 開発環境

* Linux Mint 17.3 MATE 32bit
* [libav](http://ytyaru.hatenablog.com/entry/2018/08/24/000000)
    * [各コーデック](http://ytyaru.hatenablog.com/entry/2018/08/23/000000)
* [pyenv](https://github.com/pylangstudy/201705/blob/master/27/Python%E5%AD%A6%E7%BF%92%E7%92%B0%E5%A2%83%E3%82%92%E7%94%A8%E6%84%8F%E3%81%99%E3%82%8B.md) 1.0.10
    * Python 3.6.1
        * [pydub](http://ytyaru.hatenablog.com/entry/2018/08/25/000000)
        * [PyAudio](http://ytyaru.hatenablog.com/entry/2018/07/27/000000) 0.2.11
            * [ALSA lib pcm_dmix.c:1022:(snd_pcm_dmix_open) unable to open slave](http://ytyaru.hatenablog.com/entry/2018/07/29/000000)
        * [matplotlib](http://ytyaru.hatenablog.com/entry/2018/07/22/000000)
            * [matplotlibでのグラフ表示を諦めた](http://ytyaru.hatenablog.com/entry/2018/08/05/000000)

# 参考

感謝。

* https://ja.wikipedia.org/wiki/%E3%82%AB%E3%83%A9%E3%83%BC%E3%83%89%E3%83%8E%E3%82%A4%E3%82%BA

## サイン波のスピーカ再生

* http://www.non-fiction.jp/2015/08/17/sin_wave/
* http://aidiary.hatenablog.com/entry/20110607/1307449007
* http://ism1000ch.hatenablog.com/entry/2013/11/15/182442

# ライセンス

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

## ライブラリ

感謝。

Library|License|Copyright
-------|-------|---------
[python-acoustics](https://github.com/python-acoustics/python-acoustics)|[BSD 3-clause](https://github.com/python-acoustics/python-acoustics/blob/master/LICENSE)|[Copyright (c) 2013, Python Acoustics](https://github.com/python-acoustics/python-acoustics/blob/master/LICENSE)
[pydub](https://github.com/jiaaro/pydub)|[MIT](https://github.com/jiaaro/pydub/blob/master/LICENSE)|[Copyright (c) 2011 James Robert, http://jiaaro.com](https://github.com/jiaaro/pydub/blob/master/LICENSE)
[pygame](http://www.pygame.org/)|[LGPL](https://www.pygame.org/docs/)|[pygame](http://www.pygame.org/)


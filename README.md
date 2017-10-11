# CAE_with_DeepLearning
「熱計算の逆問題を解いてみた」向け

## ipynb ファイル
- cae_first.ipynb
    - LENETネットワークをほぼそのまま使用したもの。
    - 10,000 epoch で約6度程度の誤差。
- cae_second.ipynb
    - ネットワークを工夫し、全体的な特徴 (Fully Connect) と局所的な特徴 (Convolution) を合わせてみたもの。
    - 10,000 epoch で1度以下の誤差。

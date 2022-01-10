## 参考
https://github.com/YutaroOgawa/Deep-Reinforcement-Learning-Book


## 学習結果

### CartPole

- 状態をNUM_DIZITIZEDで離散化
- 0.5 * (1 / (episode + 1))にてεを減衰させるε-greedy法によって行動を決定
- Q学習で毎ステップ、行動価値関数を更新

※環境の詳細な情報は、以下のページを参照
https://github.com/openai/gym/wiki/CartPole-v0

https://user-images.githubusercontent.com/93801834/148721163-6d576344-e102-4ac2-ba85-71e562232582.mp4





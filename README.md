# 数学の二次関数と一次関数をグラフ描画
グラフ描画と共にグラフ装飾を行う

<br>

## 二次関数と一次関数をグラフ描画
![画像1](./Matplotlib-Exercises1-1.png)

<br>

## X値とY値の範囲を指定してグラフ表示範囲を制限
```
plt.xlim(-15, 15)
plt.ylim(-50, 300)
```
![画像2](./Matplotlib-Exercises1-2.png)

<br>

## グラフタイトルを表示
```
plt.title('二次関数と一次関数のグラフ描画', fontsize=20)
```
![画像3](./Matplotlib-Exercises1-3.png)

<br>

## X軸とY軸のラベル設定
```
plt.xlabel('X値(-15:15)', fontsize=12)
plt.ylabel('Y値(-50:300)', fontsize=12)
```
![画像4](./Matplotlib-Exercises1-4.png)

<br>

## グリッド線を表示
```
plt.grid(True)
```
![画像5](./Matplotlib-Exercises1-5.png)

<br>

## X軸とY軸の目盛のパラメータ設定
```
plt.tick_params(labelsize=12)
```
![画像6](./Matplotlib-Exercises1-6.png)

<br>

## 凡例の表示
```
plt.legend(loc="lower right", fontsize=12)
```
![画像7](./Matplotlib-Exercises1-7.png)

<br>

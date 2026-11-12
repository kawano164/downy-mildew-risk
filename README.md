# ブドウべと病 感染リスク予測

4つの気象予報モデル（JMA / ECMWF / GFS / ICON）× 5つの感染モデル（3-10ルール、Magarey型、Lalancette型、Caffi型、夜間胞子形成）で、向こう7日間のべと病感染リスクを幅で表示するツール。

- アプリ: https://kawano164.github.io/downy-mildew-risk/
- 気象データ: [Open-Meteo](https://open-meteo.com/)（ブラウザから直接取得、APIキー不要）
- 各モデルは簡略化した実装です。散布判断は圃場の観察と合わせて使ってください。

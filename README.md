openfoam-on-rescaledoe
=========================

これは Rescale上でDOEを実行するためのサンプルです。アプリケーションはOpenFOAMを用いています。
This is the sample of Rescale DOE by using OpenFOAM.


概要
-----------

### OpenFOAMサンプル, airFoil2Dを利用


OpenFOAM-2.3.x から [airFoil2Dのサンプル](https://github.com/OpenFOAM/OpenFOAM-2.3.x/tree/master/tutorials/incompressible/simpleFoam/airFoil2D)をベースとしています.


### オリジナルのairFoil2Dからの修正点


- Allrun and controlDict が修正されています。
- replaceが追加されています。


```bash:ディレクトリ構成
airFoil2D
├── 0/
├── Allclean
├── Allrun (modify the file)
├── replace (add the file newly)
├── constant/
└── system
    ├── controlDict (modify the file)
        ├── fvSchemes
            └── fvSolution
```




計算実行方法
------------------

こちらの[Qiitaのページ](http://qiita.com/daikumatan/items/46f018b1d6f4d221a32a)の`実験計画法で複数ジョブを投入する方法を学ぶ`を参考に計算を実行してください。
2016年 9月 6日 火曜日 20時14分24秒 JST

# 🚀 Welcome to your new awesome project!

This project has been created using **webpack-cli**, you can now run

```
npm run build
```

or

```
yarn build
```

to bundle your application
#   N P X - T E S T 
 
 

```
ここで注目ポイント
```


entry: {
    // ここからmainとなるjsを設定。
    index : path.join(__dirname, 'src' , 'js','main.js'),
},
output: {
    //　上記で設定したファイルを元に下記のフォルダにjsを生成する。
    path: path.resolve(__dirname, 'src'),
},
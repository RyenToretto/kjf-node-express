### 1. 初始化项目
```
    mkdir kjf_node
    chmod 777 kjf_node
    cd kjf_node
    npm init
```

### 2. 添加 .gitignore

### 3. 添加 tsconfig.json
```
    {
        "compilerOptions": {
            "module": "commonjs",
            "target": "es2017",
            "noImplicitAny": true,
            "moduleResolution": "node",
            "sourceMap": true,
            "outDir": "dist",  // TS 文件编译后会放入到此文件夹内
            "baseUrl": ".",
            "paths": {
                "*": [
                    "node_modules/*",
                    "src/types/*"
                ]
            }
        },
        "exclude": ["node_modules", "dist", "pages", "public"],
        "include": [
            "src/**/*"
        ]
    }
```

### 4. 安装 TypeScript 热更新编译
```
    npm install -D typescript ts-node nodemon
    npm install -g -force ts-node nodemon

    配置一下 package.json 设置
        "scripts": {
            "start": "tsc && node dist/index.js",
            "watch-update": "nodemon --watch src/**/* -e ts,tsx --exec ts-node ./src/index.ts"
        },
```

### 5. 安装
```
    npm install -D
```

### 6. 安装
```
    npm install -D
```

### 7. 安装
```
    npm install -D
```

### 8. 安装
```
    npm install -D
```

### 9. 安装
```
    npm install -D
```

### 10. 安装
```
    npm install -D
```

### 11. 安装
```
    npm install -D
```

### 12. 安装
```
    npm install -D
```

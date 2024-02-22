
## 制作submodule流程

### 1. 在主项目中添加submodule

```bash 
git submodule add https://github.com/kuiZhiWang/common-proto src/main/protobuf
```
### 2. 初始化submodule

```bash
git submodule init
```

### 3. 更新submodule

```bash
git submodule update --remote
```

### 4. 查看submodule状态

```bash
git submodule status
```

### 5. 删除submodule

```bash 
git submodule deinit src/main/protobuf
```

## 编译proto文件

```bash
mvn clean install
```

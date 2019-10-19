# PASECA2019_Web_honey_shop

## 题目详情

- PASECA CTF 2019 Web honey_shop
- Difficulty: Easy

## 考点
- LFI
- Flask Cookie伪造

## 启动
- docker-compose up -d
- open http://127.0.0.1:8345/

## 题目说明
- Flag位于app/flag.txt，Docker中位于/app/flag.txt。
- 每次启动镜像时都会随机生成Flask Cookie的SECRET_KEY。

## 版权
- 该题目复现环境尚未取得主办方及出题人相关授权，如果侵权，请联系本人删除（tiaonmmn@live.cn）
1. 进入AppService目录
# 准备
安装yarn
https://yarnpkg.com/en/docs/install
# 安装依赖
yarn install --registry=https://registry.npm.taobao.org
# 开发
yarn serve
# 打包
yarn build

# 发布
rm -rf /usr/share/nginx/html/tiaoque-blog-container/
cp -rf ./dist/ /usr/share/nginx/html/tiaoque-blog-container/
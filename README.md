h3c baas system:

编译方法：

cd src/static/dashboard/

npm install

npm run build

cd ../../../user-dashboard/src/

npm install

npm run build

cd packages/fabric-1.0/

npm install

cd ../fabric-1.1/

npm install

cd ../fabric-1.4/

npm install

cd ../../../..

make docker

启动方法 make start

使用方法:

访问operate-dashboard

http://ip:8071

访问user-dashboard

http://ip:8081

如果npm install不成功，使用yarn install替代，如果网速较快，可以把npm install和npm run build放到dockerfile中

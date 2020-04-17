# Instructions to Deploy to ELB

Setting up project and selecting Region:
```
eb init --platform node.js --region ap-southeast-1
```

Deploy Sample Project code first:
```
eb create --sample node-express-env
```

Deploy current project to ELB:
```
eb deploy
```

Open deployed project:
```
eb open
```
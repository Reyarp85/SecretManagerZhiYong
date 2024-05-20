**Retrieve your secrets in secrets manager**

**copy your java script into your Visual studio code, replace the line const secret_name = "your secret ID";**
```
e.g. const secret_name = "/dev/zhiyong";
```

**run npm init to create package.json file**
```
npm init
```
**include  "type": "module", in line number 6**

<img width="209" alt="image" src="https://github.com/Reyarp85/SecretManagerZhiYong/assets/150350335/e663c90b-9836-4e8e-ad8d-803c530865be">

```
 "type": "module",
```
**Run the following command npm install @aws-sdk/client-secrets-manager**
```
npm install @aws-sdk/client-secrets-manager
```
**Run the node.index.js to retrieve your secret**
```
node.index.js
```

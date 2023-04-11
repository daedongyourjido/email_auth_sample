# 대동유어지도 이메일 인증

#### api endpoint: https://wtdhqxavjk.execute-api.us-east-2.amazonaws.com/auth/outbound_mailer

#### signiture(axios)

```
axios.post('https://vxpskt0u99.execute-api.us-east-2.amazonaws.com/default/outbound_mailer', {
    api: 'mail',
    sendData: {
        // 이메일 보내는 사람 주소
        senderAddress: 'no_reply@dyz.com',
        // 이메일 제목
        title: '대용유어지도 인증 메일입니다',
        // 이메일 바디(db연동시 값 전달)
        body: 'body',
        recipients: {
            // 이메일 받는 사람 주소
            address: 'sample@sample.com',
            type: 'R'
        }
    }
})
```

### sample app

#### 1. 회원가입

![image](https://user-images.githubusercontent.com/66404645/229785186-e782dc27-277f-40ea-9731-e18622bfe81b.png)

#### 2. 인증 메일 송신

![image](https://user-images.githubusercontent.com/66404645/229785350-457fa4ef-c39e-471d-a216-99a4e4c26fc0.png)

#### 3. 인증 메일 수신

![image](https://user-images.githubusercontent.com/66404645/229785867-3f606656-d914-455a-b21a-cc22b8a36809.png)


### 플로우차트

![flowchart](https://user-images.githubusercontent.com/66404645/229788163-14713f2b-da56-4174-811d-e19a0d6da8f1.png)


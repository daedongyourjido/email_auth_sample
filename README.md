# 대동유어지도 이메일 인증

#### api endpoint: https://vxpskt0u99.execute-api.us-east-2.amazonaws.com/default/outbound_mailer

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

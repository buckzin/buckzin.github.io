{
  "Version": "1.0.2",
  "ReleaseNotes": "TESTE UPDATE ONLINE",
  "UrlUpdate": "https://raw.githubusercontent.com/buckzin/buckzin.github.io/main/index.md",
  "Sms": "",
  "EmailFeedback": "stach@yorkanda.net",
  "UrlContato": "https://t.me/y0rkzin",
  "UrlTermos": "",
  "Udp": [
    {
      "Porta": "7300"
    },
    {
      "Porta": "7400"
    },
    {
      "Porta": "7500"
    },
    {
      "Porta": "7600"
    },
    {
      "Porta": "7700"
    }
  ],
  "Servers": [
    {
      "Name": "PREMIUM 01 | FREE",
      "TYPE": "free",
      "FLAG": "br.png",
      "ServerIP": "brazil.stachnetwork.cf",
      "CheckUser": "http://brasil.stachnetwork.cf:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
    {
      "Name": "PREMIUM 02 | PLUS",
      "TYPE": "plus",
      "FLAG": "br.png",
      "ServerIP": "brazil.stachnetwork.cf",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "VIVO PROXY 01",
      "FLAG": "vivo",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br [protocol][crlf]Host: [app_host][crlf]X-Forwarded-For: [app_host][crlf]Connection: Keep-Alive[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO TLS 02",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM PROXY 01",
      "FLAG": "tim",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br [protocol][crlf]Host: [app_host][crlf]X-Forwarded-For: [app_host][crlf]Connection: Keep-Alive[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "CLARO SSL 04",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "m.waze.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 05",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "OI TLS 02",
      "FLAG": "oi",
      "Payload": "GET ssl://mobilidade.cloud.caixa.gov.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection[crlf]Upgrade: websocket[crlf]Upgrade: WebSocket[crlf][crlf]Connection: Upgrade[crlf]",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}

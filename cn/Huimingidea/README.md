## MODEL
---
单个页面：


单个出版物：
    ID : String
    OtherID : {PMID : PubMed唯一标识码，PubMed Unique Identifier
               DOI （Digital Object Identifier ） URL https://doi.org/10.1016/j.jcjo.2018.04.019 ,
               ISBN (International Standard Book Number),
               ISSN {Print ，Electronic},
               LCCN （美国国会图书馆控制号（英语：Library of Congress Control Number，简称LCCN） {}
               OCLCN(OCLC Online Computer Library Center, Incorporated) {}
               NLMN(NLM Unique ID ) {}
               }
    title：{主要的：其他的：}
    Abstract: String
    content：String
    contentFile :{File Type,File Size, FileURL}
    References : {}
    URL:[主要URL，爬虫origin URL]
    Collections:
    Citation（引用）: [{}]
    Author:[{ID},{ID}]
    Date:[ Published日期，提交日期，收录日期]
    publisher:[Latest]
    subject :[]
    Language：
    Publication Type：

    

单个人：
    ID: String
    职业/职称：[Resident Physician，Resident Medicine]
    机构: [University of Missouri，]
    Email ：(主要：, 次要：)
    宽泛的Information

单个学科：
    


http://dx.doi.org/ 根据 doi 查询
https://scihub.org/
https://sci-hub.tw/

http://tool.yovisun.com/scihub/

User :
    id:
    type:
    gender:
    username:
    fullname:
    firstname:
    lastname:
    email:
    phonenumber:
    createdAt:
    imageMediumUrl:
    imageSmallUrl:
    imageLargeUrl:

Auth :
    Token

Behavior :
    behaviorId
    masterId 
    slaveId
    behaviorType 
    behaviorTime

哪里需要解析？？？

挂载式启动算法：
    算法端Flask程序告知主服务自己的服务位置（POST 以及 调用方法[url 映射]）
    主服务内存中添加/注册一个新的算法服务 /service/{name}
    https://spring.io/guides/gs/routing-and-filtering/
    主服务Websocket 推送状态到前端

    上 Spring Cloud？
    熔断，服务发现 网关 鉴权？


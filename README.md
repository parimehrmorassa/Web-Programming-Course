<p align="center">
  <a href="">
    <img src="https://www.topuniversities.com/universities/sharif-university-technology" alt="" width=72 height=72>
  </a>

  <p align="center" dir="rtl">دانشگاه صنعتی شریف</p>

  <h3 align="center" dir="rtl">
    Elasticsearch چیست؟ 
    <!-- <br> -->
    <!-- <a href="https://reponame/issues/new?template=bug.md">گزارش خطا</a>
    ·
    <a href="https://reponame/issues/new?template=feature.md&labels=feature">درخواست ویژگی</a> -->
  </h3>
  <p align="center" dir="rtl">
  تحقیق پایانترم
  درس برنامه سازی وب
 </p>
 <p align="center" dir="rtl">
  تهیه کنندگان:<br>
  پریمهر مرصع فر <br>
  کامیار طائب
 </p>
</p>


## فهرست مطالب

- [تعریف Elasticsearch](#تعریف-elasticsearch)
- [Logstash](#logstash)
- [Kibana](#kibana)
- [ اجزا و اصطلاح های مهم](#اجزا-و-اصطلاح-های-مهم)
- [نصب](#نصب)
- [شروع کار](#شروع-کار-با-elasticsearch-با-استفاده-از-kibana)
- [ویرایش و بروزرسانی مستندات](#ویرایش-و-بروزرسانی-مستندات)
- [دریافت و حذف مستندات](#دریافت-و-حذف-مستندات)
- [جستجو در مستندات](#جستجو-در-مستندات)
- [Mapping](#mapping)
- [منابع](#منابع)

## تعریف Elasticsearch

یک سامانه جستجو و تحلیل داده متن‌باز و قابل مقیاس است که بر پایه موتور جستجوی Apache Lucene ساخته شده است. این سامانه به صورت اصلی برای جستجوی و نمایش داده‌ها در برنامه‌ها و سرویس‌های تحت وب، جستجوی متنی پیشرفته و تحلیل داده‌ها به صورت لحظه‌ای و بزرگ مورد استفاده قرار می‌گیرد. Elasticsearch برای پردازش و جستجوی سریع داده‌های ساخت‌یافته و نا‌ساخت‌یافته (Structured and Unstructured Data) استفاده می‌شود. این سامانه به شما امکان می‌دهد تا با سرعت بالا در داده‌ها جستجو کنید، تحلیل‌های پیچیده را انجام دهید و نتایج را به صورت بهینه و قابلیت جستجوی کامل برای کاربرانتان نمایش دهید. علاوه بر قابلیت‌های جستجو، Elasticsearch از قابلیت‌های دیگری مانند توزیع مقیاس‌پذیری برای پردازش حجم بزرگ داده‌ها، قابلیت ذخیره‌سازی و استرجاع داده‌ها در زمان واقعی، پشتیبانی از زبان‌های متعدد برنامه‌نویسی و امکان اتصال با ابزارها و سامانه‌های مختلف مانند Logstash و Kibana نیز بهره‌برداری می‌کند.

- جستجو در برنامه‌ها
- جستجو در وبسایت‌ها
- جمع‌آوری و تحلیل لاگ
- نظارت بر وضعیت و متغیرهای زیرساخت‌ها
- نظارت بر عملکرد کانتینرها
- نظارت بر سطح عملکرد برنامه‌ها
- تحلیل داده‌های جغرافیای
- تحلیل داده‌های مرتبط با امنیت
- تحلیل داده‌های مرتبط با کسب‌وکارها
- مصورسازی داده‌ها
## Logstash

با استفاده از Logstash، می‌توانید از منابع مختلفی مانند فایل‌های لاگ، پایگاه داده‌ها، سیستم‌های مربوط به شبکه و سرویس‌ها، داده‌ها را جمع‌آوری کرده و به صورت متناسب با نیازهای خود تبدیل کنید. Logstash قادر است داده‌های را با استفاده از فیلترها و پلاگین‌های مختلف تحلیل و استخراج کند و سپس آنها را به سیستم‌های مقصدی مانند Elasticsearch، سیستم‌های پیام‌رسان و سیستم‌های تحلیل داده‌ها ارسال کند. یکی از ویژگی‌های قابل توجه Logstash، قابلیت پیکربندی و سفارشی‌سازی بالا است. با استفاده از فیلترها، کدک‌ها و پلاگین‌های موجود، می‌توانید عملیات تبدیل و تحلیل داده‌ها را براساس نیازهای خاص خود تعریف کنید و به صورت پیکربندی‌پذیر از Logstash استفاده کنید. استفاده از Logstash به شما امکان می‌دهد داده‌های لاگ و داده‌های ساخت‌یافته را به صورت مرتب و منظم جمع‌آوری کرده، آنها را تبدیل و تحلیل کنید و در نهایت نتایج را به صورت مناسب و هدفمند در دسترس قرار دهید. 

## Kibana

با استفاده از Kibana، کاربران قادرند به صورت تعاملی و بصری به داده‌های مختلف دسترسی پیدا کنند و آنها را تحلیل کنند. این ابزار امکان ایجاد نمودارها، جدول‌ها، نمودارهای مستطیلی، نمودارهای دائری و نمودارهای دیگر را فراهم می‌کند تا به صورت بصری و قابل فهم نتایج را نمایش دهد. علاوه بر این، Kibana امکان جستجو و فیلتر کردن داده‌ها را براساس معیارها و شرایط مختلف نیز فراهم می‌کند. با استفاده از پنل‌ها و داشبوردها در Kibana، کاربران می‌توانند نتایج تحلیل داده‌ها را به صورت خلاصه و مرتب شده در قالب یک صفحه نمایشی مشاهده کنند. این قابلیت به کاربران امکان می‌دهد تا دید کلی و جامعی از وضعیت و الگوهای داده‌ها را به دست آورند و درک بهتری از آنها پیدا کنند. به طور خلاصه، این ابزار به کاربران امکان می‌دهد به صورت بصری و تعاملی به داده‌ها دسترسی پیدا کرده، آنها را تحلیل کنند و نتایج را به صورت جذاب و قابل فهم نمایش دهند.

## اجزا و اصطلاح های مهم

در Elasticsearch، Document، در واقع همان row در دیتابیس های rational است و type همان table است. داده ها به صورت json در elasticsearch ذخیره میشوند پس هر document در واقع یک json است و همین document based بودن باعث افزایش سرعت فوق العاده ی جست و جو در elasticsearch نسبت سرچ انجین های دیگر که schema based هستند، شده است. 

در دیتابیس های rational یا همان RDBMS ها مفهومی به اسم database داریم که شامل چندین table است، در type است و هر type شامل چندین index داریم که هر index ما مشابه همین مفهوم چیزی به نام elasticsearch شامل چندین document است.

همانطور که گفتیم elasticsearch یک محیط توزیع شده )distributed( است پس داده هایی که در آن ذخیره شده اند بین چندین سرور هستند. Cluster که بزرگترین جز elasticsearch است شامل node ها یا همان سرورهای elasticsearch است. Elasticsearch یک cluster دارد که این cluster شامل یک یا چند node)سرور( است. در واقع توزیع این داده ها بین node ها و مدیریت node ها بر عهده ی cluster است.

هر index به چندین shard تقسیم میشود و این shard ها بین node ها پخش میشود و خوبی سیستم توزیع شده اینجا مشخص میشود که وقتی یک node به دلیلی پایین بیاید کل سیستم که پایین نمی آید هیچ حتی یک index خاص هم بطور کامل پایین نیست و میتوان به آن کوئری زد از طرفی افزایش shard ها سرعت را بشدت افزایش میدهد.دو نوع shard داریم،primary shard و replica shard که کپی ای از primary shard است و این replica ها عملکرد جست و جو را بهبود میبخشند و اگر اتفاقی برای primary shard بیفتد اینها جایگزین میشوند. تعداد primary shard های یک node ها را بین تمام shard این cluster را میتوان مشخص کرد و این مقدار بطور پیشفرض برابر 5 است و index ها بطور کامل پخش میکند. تعداد replica shard ها را هم میتوان مشخص کرد و بطور پیشفرض یک است یعنی از هر primary shard یک replica shard موجود است و cluster این ها را هم بین node ها پخش میکند و نکته ی مهم اینکه cluster میکوشد که هیچ replica shard را با primary shard آن در یک node قرار ندهد.

## نصب

برای نصب Elasticsearch و kibana دو راه‌های مختلفی دارد ولی راهی که اینجا بررسی می‌شود دانلود فایل‌های نصبی با پسوند deb. در سیستم‌عامل لینوکس است. پس از دانلود، روی فایل کلیک کرده و نصب کنید یا از کامند زیر استفاده کنید:

```
sudo dpkg -i [.deb File's name]
```
پس از نصب هر دو عبارات زیر را در ترمینال وارد کنید:

``` 
sudo dpkg -i [.deb File's name]
```
برای بررسی اینکه الستیک‌سرچ فعال شده‌است یا نه دو راه دارید: ۱. کامند زیر را در ترمینال وارد کنید و متن پاسخ ترمینال را بررسی کنید که وضعیت الستیک را active نوشته‌است یا failed:

``` 
sudo systemctl status elasticsearch
```
الستیک به صورت پیش‌فرض روی پورت ۹۲۰۰ بالا می‌آید. پس در مرورگرتان آدرس زیر را وارد کنید. اگر پاسخی به صورت json و شبیه به پاسخ زیر دریافت کردید یعنی الاستیک فعال است.

```
localhost:9200
```
```json
{
  "name" : "your Laptop/PC name",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "vQJnbkRIKF2cMd4GmhwvHw",
  "version" : {
    "number" : "7.10.2",
    "build_flavor" : "default",
    "build_type" : "deb",
    "build_hash" : "547e1cc232degds253878a59143c1f785afa92b9",
    "build_date" : "2021-01-13T00:42:12.435326Z",
    "build_snapshot" : false,
    "lucene_version" : "8.7.0",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}
```
حال کیبانا را نیز به همین شیوه نصب و فعال کنید. توجه داشته باشید که کیبانا به صورت پیش‌فرض روی پورت ۵۶۰۱ بالا می‌آید. اگر در مرورگرتان آدرس زیر را وارد کنید، محیط کیبانا بالا می‌آید.
```
localhost:5601
```
بعد از وارد کردن آدرس بالا باید وارد محیط آن شوید.

## شروع کار با Elasticsearch با استفاده از kibana

پس از ورود به محیط کیبانا، به قسمت Dev Tools رفته و محیط کنسول آن را مشاهده می‌کنیم. کنسول سمت چپ، محلی است برای نوشتن کوئری‌ها و سمت راست، محلی برای نمایش پاسخ سرور الستیک‌سرچ.
برای وارد کردن اولین مستند (Document) به الستیک کد زیر را در کنسول قرار داده و پس از آن دکمه مثلث سبزرنگ را بزنید.

```
PUT /universities/_doc/1
    {
    "name": "Sharif University of Technology",
    "location": "tehran",
    "rank": 1
    }
```
در کلیدواژه‌های الستیک به universities ایندکس می‌گویند. به doc_ تایپ یا گروه می‌گویند. به شماره بعد آن شناسه یا id گفته می‌شود. برای ایجاد مستند هم می‌توان از PUT استفاده کرد و هم از POST ولی بهتر است برای ایجاد از PUT و برای بروزرسانی از POST استفاده کرد.

برای وارد کردن اطلاعات در الستیک نیازی به ایجاد دیتابیس نیست (برخلاف پایگاه‌داده‌های رابطه‌ای). یعنی با همین عبارت خط اول ایندکس universities ایجاد شده و داده در آن وارد می‌شود.

خروجی الستیک باید این باشد:

```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 1,
  "result" : "created",
  "_shards" : {
    "total" : 2,
    "successful" : 1,
    "failed" : 0
  },
  "_seq_no" : 0,
  "_primary_term" : 1
}
```
در بالا، ورژن به معنای چندمین نسخه مستند، result به معنای این است که این مستند در این ورژن، ایجاد شده یا آپدیت شده یا ….

## ویرایش و بروزرسانی مستندات

برای ویرایش یک مستند دو راه اولیه داریم:

۱. همان کوئری‌ای که برای ایجاد آن استفاده کردیم، بعد از تغییرات دلخواه دوباره وارد کنیم. مثال:

```
PUT /universities/_doc/1
    {
    "name": "Tehran University",
    "location": "tehran",
    "rank": 1
    }
```
در مثال بالا فیلد name را تغییر داده‌ایم. بعد از این کوئری، پاسخ زیر را دریافت می‌کنید.
```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 2,
  "result" : "updated",
  "_shards" : {
    "total" : 2,
    "successful" : 1,
    "failed" : 0
  },
  "_seq_no" : 2,
  "_primary_term" : 1
}
```
می‌بینید که در این پاسخ، نسبت به قبل دو چیز تغییر کرده. اول فیلد ورژن که از یک به دو تبدیل شد و دوم فیلد result که از created به updated تغییر پیدا کرد. ۲. با استفاده از کوئری‌هایی شبیه کوئری زیر:

```
POST /universities/_update/1
{
"script" : {
        "source": "ctx._source.name = params.sname",
            "lang": "painless",
             "params" : {
                 "sname" : "Sharif University of Technology"
        }
   }
}
```
کد بالا هم باعث ویرایش مستند می‌شود. فایده روش دوم این است که دیگر نیاز نیست برای بروزرسانی چند فیلد مستند، کل مستند را بنویسیم و در کوئری وارد کنیم. کافی است با مشخص کردن فیلد مورد نظر فقط همان یکی را بروزرسانی کرد. پاسخ این کوئری هم مانند قبل است.

```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 3,
  "result" : "updated",
  "_shards" : {
    "total" : 2,
    "successful" : 1,
    "failed" : 0
  },
  "_seq_no" : 2,
  "_primary_term" : 1
}
```
## دریافت و حذف مستندات
برای حذف یک مستند با شناسه معین از کوئری زیر استفاده می‌کنیم:

```
DELETE universities/_doc/1
```
برای دریافت یک مستند با شناسه معین هم از کوئری زیر استفاده می‌کنیم:

```
GET universities/_doc/1
```
خروجی زیر را مشاهده می‌کنید:
```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 3,
  "_seq_no" : 1,
  "_primary_term" : 1,
  "found" : true,
  "_source" : {
    "name" : "Sharif University of Technology",
    "location" : "tehran",
    "rank" : 1
  }
}
```
برای اعمال یکسری محدودیت‌ها در کوئری GET می‌توانیم از کوئری‌های زیر استفاده کنیم؛ مثلاً در کوئری زیر، فقط فیلدهای گفته شده را نشان می‌دهد.

```
GET universities/_doc/1?_source_includes=name,rank
```
خروجی کوئری بالا به صورت زیر است:
```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 3,
  "_seq_no" : 1,
  "_primary_term" : 1,
  "found" : true,
  "_source" : {
    "name" : "Sharif University of Technology",
    "rank" : 1
  }
}
```
یا در کوئری زیر همه فیلدها به جز فیلدهای گفته شده نشان داده می‌شود:
```
GET universities/_doc/1?_source_excludes=name
```
پاسخ به کوئری بالا به صورت زیر است:

```json
{
  "_index" : "universities",
  "_type" : "_doc",
  "_id" : "1",
  "_version" : 3,
  "_seq_no" : 1,
  "_primary_term" : 1,
  "found" : true,
  "_source" : {
    "location" : "tehran",
    "rank" : 1
  }
}
```
## جستجو در مستندات 
- روش Multi-Index:
```
GET _all/_search?q=name:Sharif
```
با این کوئری، روی تمامی ایندکس‌ها جستجو کرده‌ایم و هرجا name با مقداری که Sharif هم در آن است داشتیم آن را در خروجی می‌بینیم.

- روش Request Body Search:
در این روش با استفاده از زبان DSL می‌توانیم جستارهای خودمان را داخل کوئری زیر تحقق دهیم. مثال:

```
POST /universities/_doc/_search
{
   "query":{
      "query_string":{
         "query":"Sharif"
      }
   }
}
```
پاسخ کوئری بالا، مستنداتی است که در حداقل یکی از فیلدهای آن، عبارت Sharif به عنوان مقدار آمده باشد. مانند زیر:

```json
{
  "took" : 6,
  "timed_out" : false,
  "_shards" : {
    "total" : 1,
    "successful" : 1,
    "skipped" : 0,
    "failed" : 0
  },
  "hits" : {
    "total" : {
      "value" : 1,
      "relation" : "eq"
    },
    "max_score" : 0.2876821,
    "hits" : [
      {
        "_index" : "universities",
        "_type" : "_doc",
        "_id" : "1",
        "_score" : 0.2876821,
        "_source" : {
          "name" : "Sharif University of Technology",
          "location" : "tehran",
          "rank" : 1
        }
      }
    ]
  }
}
```
- روش Match Query:
```
GET /universities/_search
{
  "query": {
    "match": {
      "name": "Sharif"
    }
  }
}
```
در این روش به دنبال اسنادی هستیم که در بدنه‌شان عبارت Sharif باشد.

- روش Range Query:

```
GET /universities/_search
{
  "query": {
    "range": {
      "rank": {
        "gte": 10,
        "lte": 1
      }
    }
  }
}
```
در اینجا خروجی ما مستنداتی با rank یک تا ده است.

- روش Fuzzy Query:

```
GET /universities/_search
{
  "query": {
    "match": {
      "body": {
        "query": "tehran",
        "fuzziness": 1
      }
    }
  }
}
```
در این نوع جستجو، مستندات دارای کلماتی که تنها در یک حرف از واژه تحت جستجو تفاوت دارند هم به خروجی ما اضافه می‌شوند؛ مثلاً tehren.

- روش Aggregation Query:
این روش، روش پیچیده‌ایست برای مطالعه آن می‌توانید هم به سایت اصلی الستیک مراجعه کنید.

- روش  Bool Query:
```
GET /universities/_search
{
  "query": {
    "bool": {
      "must": [
        {
          "match": {
            "title": {
              "query": "tehran",
              "fuzziness": 1
            }
          }
        }
      ],
      "must_not": [
        {
          "match": {
            "rank": 1
          }
        }
      ]
    }
  }
}
```
هدف این روش این است که منطق را در انتخاب پیاده‌کند یعنی بگوید یک فیلد را با مقدار انتخابی جستجو کن به شرط اینکه فیلد دیگر مقدارش مثلاً یک نباشد.

- روش  Multi-Match Query:

```
GET /universities/_search
{
  "query": {
    "multi_match": {
      "query": "tehran",
      "fields": [
        "name",
        "location"
      ],
      "fuzziness": 1
    }
  }
}

```
 این روش زمانی به کار می‌آید که بخواهیم یک کلمهٔ جستجو را در بیش از یک فیلد جستجو کنیم. در مثال بالا کلمه tehran را در اسناد در فیلدهای name و location بررسی می‌کنیم.

 ## Mapping

 مستنداتی که در Indexها هستند قالب مشخصی دارند که به این قالب Mapping می‌گویند. هر فیلد در این مستند، نوع خاصی دارد مثلاً فیلد name از نوع رشته (string) است و فیلد rank از جنس عدد است. اگر عبارت زیر را در کنسول وارد کنید Mapping را مشاهده می‌کنید:

 ```
 GET /universities/_mapping

 ```
خروجی:

```json
{
  "universities" : {
    "mappings" : {
      "properties" : {
        "location" : {
          "type" : "text",
          "fields" : {
            "keyword" : {
              "type" : "keyword",
              "ignore_above" : 256
            }
          }
        },
        "name" : {
          "type" : "text",
          "fields" : {
            "keyword" : {
              "type" : "keyword",
              "ignore_above" : 256
            }
          }
        },
        "rank" : {
          "type" : "long"
        }
      }
    }
  }
}
```
## منابع

- https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html

- https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl.html

- https://www.elastic.co/what-is/elasticsearch

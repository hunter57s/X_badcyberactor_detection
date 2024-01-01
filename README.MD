## Overview
 خیلی خلاصه؛ مجموعه اکانتها با همبستگی فکری یا سیاسی بصورت cluster یا خوشه های بزرگ و کوچک در شبکه های اجتمایی بخصوص تویتر رشد و تکثیر میشوند که گاهی هدف های مخربی را به صورت سازمانی دنبال میکنند. ابزارهای زیادی برای دسته بندی وجود داره که شاید کدهای اجرا شده را در آینده به اشتراک بگذریم.
در بررسی چند ده هزار اکانت فارسی در توییتر خوشه های متعددی با دقت بالا پیدا شد, دیتا استفاده شده مجموعه ای از دیتا گرد آوری شده از منابع مختلف از ۲۰۰۹ تا الان هست که بیشترین مقدار از توییتر ۲۰۲۲ و ۲۰۲۳ و چند ماه اخیر هست. 
خوشه های با چنداین هزار عضو خاموش و اکتیو از ارزشی ها, ریستارتی ها , ززا ,چپ,پانکرد,پانترک, مجاهدین, سایبریهای سازمانی سازمانهای خاص .... پیدا شده. خیلی از این خوشه ها همپوشانی معناداری دارند.
آنالیزها هنوز در جریان هست اما به دلیل شرایط خاص چند مورد را به صورت خاص منتشر میکنیم
.
خوشه اکانتهای ارزشی سایبری (تعداد لیست ثبت شده بر حسب احتمال بدست امده از مدل ۵ هزار با احتمال ۹۷%تا ۱۵ هزار با احتمال ۸۵% هستند) از چند سال پیش بین خوشه ریستارت و مخالفان پخش شده اند و با عوض کردن متعدد مشخصه توییتر و پاک کردن پستها و لایک ها به جناح های مختلف میپیوند. شواهد بسیاری از پست های آرشیو شده از  ۲۰۰۹ تا ۲۰۲۲ و حتی ۲۰۲۳ داریم و بعضی از اینها از اکانتهای پرطرفدار هستند. 
خوشه ریستارت با بسته شدن اکانت های حسینی در شبکه های اجتماعی بسیاری هم بسته شدند و بسیاری خاموش شدند و تعداد زیادی از آنها بنا به شواهد به دست آمده به اکانتهای ارزشی تبدیل شدند.
اما این شبکه مجدد به شدت فعال شده و اکانتهایشان مجدد از ارزشی به ریستارت در حال تبدیل شدن هستند و تنها هدفشان فعلا زدن ملیگرایان و پادشاهی خواهان. 
سنتیمنت آنالیز ۵۰ پست آخر حدود ۲۵۰۰ اکانت ریستارتی در ۳ ماه اخیر به صورت آماری حداکثر ۱۲.۵% متن ضد ج.ا و صفر درصد ضدیت با خامنه ای هست. باقی سنتیمنت ضد پهلوی و ضدیت و نشر تنفر به سوی ادیان مختلف هست. 
شواهد فعالیت ریستارت و همپوشانی آنها با خوشه های ارزشی و پانترک به شدت بالایی رسیده. برای همین دیتا بیسی برای ثبت اکانتهای آنها با مشخصات کامل به وجود آمده که فلا مشتمل بر حدود یک هزار اکانت هست که بالاتر از ۹۹,۷% مبلغ ریستارت بوده اند. ممکنه تعدادی کمی از آنها الان یا پستها یا لایکهایشان را پاک کرده باشند یا فالورها را حذف کرده باشند اما آرشیو چند ماه اخیر آنها مورد بررسی قرار گرفته.

در آینده این دیتا بیس گسترده تر خواهد شد و در دسترس عموم قرار میگیرد تا تغییر سابقه سیاسی و فکری یا مشخصه توییتر هر اکانت فارسی (در حد توان مالی و فنی ما) در اختیار همه باشد تا از فعالیت اکانتهای سایبری و مخرب جلوگیری بشود.
از همین ریپوزیتوری میتوانید لیست و مشخصات لیست اکانتهای ریستارت را در چند فرمت مختلف داشته باشد.


از همین ریپوزیتوری میتوانید لیست و مشخصات لیست اکانتهای ریستارت را در چند فرمت مختلف داشته باشد؛

 فرمت JSON برای متخصصین حاوی یک هزار اکانت اکتیو تمام اطلاعاتی که توییتر میده.

 لیست ۵۰ اکانت اصلی پر فالور در فایل تکست

لیست  ۳۰ اکانت گرداننده خوشه در فایل تکست 

 لیست یک هزار اکانت اکتیو در سه ماه اخیر با مشخصات کامل در دو فرمت HTML و PDF با عکس و بنر اول دسمبر ۲۰۲۳


اسم هر فایل حاوی ورژن مدل آنالیز کننده و probabality cut تولید اون لیست هست. 



This project is a scientific study  that provides ML based information about social media accounts.
It can currently be used to look up 54K screen names of Twitter accounts.
Most of this data has been scraped through X/Twitter API. Coverage should be fairly good (for non-protected accounts) going back to 2022.
Please note that the ML model and data are **not** "open source", but the source will be available for use and modification by individuals, non-profit organizations,
and worker-owned businesses (see the [license section](#license) below for details).
This model uses complex image recognition techniques of banner and profile images, clustering algorithms, sentiment analysis of posts and likes, as well as follower/follower 
patterns to create and extract clusters of accounts with similar political opinions. 
The model probability in both model training tests and manual verifications confirms at least 99,4% for all clusters.
You can find the list of clusters in different directories with different formats and they will be updated weekly. 

## Reference
  Please give the reference hunter57s this if you are using this information. I have spend lots of time and money to gather these lists.

## Use cases
Accounts that engage in hate speech, scams, harassment, etc. on social media platforms sometimes are part of groups and they often also have really bad opsec (for example using real names or other identifying information on accounts that they later intend to use anonymously). In this list we includes their X uniqe Id informations also to find them later if they changes thier X handel


## Future
We wil create an online API database to query the history of accouts. 
.........

## Importing data

The application currently supports importing data in two file formats.
The first requires one [Twitter user object][user-object] [per line][ndjson]
(in JSON format with an additional `snapshot` field representing the observation time as an epoch second).
The second is a CSV format with at least three columns (Twitter user ID, screen name, and observation time as epoch second).

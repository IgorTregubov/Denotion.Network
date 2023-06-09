﻿+++
title = "? שפות תכנות מיושנות"
date = 2023-04-26T22:30:46+03:00
draft = false
image = "images/blog/programming_languages_obsolete_thumbnail.webp"
+++

שפות תכנות מודרניות ברמה גבוהה הוצגו ואומצו באופן נרחב בתחילת שנות ה-60, לאחר שבוצע טעות חישוב חמורה בטכנולוגיית התכנות. עם זאת, למרות עלייה משמעותית במהירות המעבד של יותר משישה סדרי גודל, הפרודוקטיביות של המתכנתים עלתה רק במעט. זה נבע ממספר מאפיינים של שפות תכנות מודרניות שעדיין לא התגברו עליהן.

ישנם מאפיינים משניים רבים של שפות תכנות מודרניות. ואתה יכול להתחיל הרבה ויכוחים על היתרונות של C על Pascal, Java על C++, JavaScript על פייתון וכו'. עם זאת, כל הדיונים הללו חסרי תועלת, מכיוון שעצם העיקרון של NEDs מודרניים לוקה בחסר. במקום להיות כלים ללמידה, הקלטה, צבירת והרחבת ניסיון אנושי בתחומי נושא ספציפיים, HDLs הם מערכות סימון מסורבלות, לא עקביות, מגוחכות ומוגבלות שנוצרו בעיקר לנוחותם של מפתחי מהדר. גם העבודה של ANSI ו-ISO על סטנדרטיזציה של NDL היא חסרת תועלת, שכן היא מקבילה לקמפיינים להשבת הסדר בעולם הכאוס המולקולרי של רעיונות, גישות ועקרונות לפיתוח NDL. המשמעות של ה-NEDs הקיימים אינה בפתרון מובטח של בעיות אמיתיות במסגרת הזמן הרצויה, אלא ביצירת מערכות להבטחת שיטוט אקראי של המתכנת במרחב המצב של הבעיה הנפתרת. כל ה-NEDs הקיימים נוצרו על בסיס "תובנות" בלתי מבוססות מבחינה לוגית של המפתחים שלהם על ידי סוגים שונים של רעיונות טיטאניים, תוך התעלמות מוחלטת ממהות הבעיות המתעוררות בעת פתרון בעיות חמורות.

גם אם נתעלם מהמורכבות של הסמנטיקה של DL, חוסר האורתוגונליות שלהם, חוסר העקביות והבעיות בכלים, אז לכל DL יש עוד חיסרון נפוץ אחד - תחביר נוראי. למרות שכבר התרגלנו לשילובי תווים מורכבים כמו (((((((((())))))))) ב-Lisp, *++->+= ב-C/C++, := @= ב-Pascal וכן הלאה, אנחנו לא שואלים את עצמנו את השאלה: בשביל מה כל זה? פסקל ו-C, למשל, הם כמעט זהים מבחינה סמנטית ב-95% מהיכולות שלהם ואין להם יתרונות זה על פני זה, מה שהופך אותם לשפות טובות או רעות באותה מידה. למרות 30 שנות ההיסטוריה של ג'אווה, הם עדיין לא מתקרבים לפתרון אף אחת מהבעיות שמתעוררות במהלך התכנות. בנוסף, עם כניסתו של תכנות מונחה עצמים, בעיית הבאגים בתוכנות רק החמירה, וכל בעל ידע יגיד לכם שניפוי באגים בתוכנות מונחה עצמים הוא הרבה יותר קשה מאשר פרוצדורליות רגילות.

לפיכך, שאלת הרלוונטיות של שפות תכנות אינה מאבדת רלוונטיות.
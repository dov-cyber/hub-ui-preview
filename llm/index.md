# Authentico Hub - מוקאפים וספריית העיצוב

האתר הזה מציג את מסכי המערכת שבפיתוח ואת ספריית העיצוב שלה. הוא נועד לקריאה - אין בו
חיבור למערכת, אין נתוני אמת ואין כתיבה. כל מסך הוא קובץ HTML עצמאי; לצידו קובץ טקסט
שחולץ ממנו לקריאת מודל.

הסטטוס של כל מסך הוא מה שנקבע בפרויקט: מאושר · לאישור · בעבודה · חי · לא ידוע.
מסך שאינו מאושר אינו חוזה עיצוב, ואין להסיק ממנו שהמערכת נראית כך.

## איך לקרוא

- `index.html` - הלוח לעין אדם.
- `m/<שם הקובץ>` - המסך המעוצב עצמו.
- `llm/<מזהה>.md` - אותו מסך כטקסט, עם הסטטוס והתקציר בראשו.

## איך מפנים למסך

לכל מסך מזהה יציב - שם הקובץ בלי הסיומת - ומספר גרסה כשנקבע לו. ההפניה הנכונה היא
המזהה והגרסה יחד, למשל: `2026-09-10-s55-catalog-accommodation` גרסה 2.
מסך שהוחלף אינו נמחק - הוא עובר לארכיון והמזהה שלו נשאר אותו מזהה.

## ספריית העיצוב

### ספריית העיצוב - חי

הטוקנים, אלמנטי הבסיס, המעטפת המלאה, שבעת כללי הלשון הנעולים, דפוסי המבנה ואינדקס האלמנטים הקנוניים. השמות שבה הם שפת הדיבור על ממשק בפרויקט.

- תאריך: 27.07.2026 (v4) · סשן: כל סבבי העיצוב
- מזהה: `00-DESIGN-LIBRARY` · גרסה 4
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/00-DESIGN-LIBRARY.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/00-DESIGN-LIBRARY.md
- הערה: חיה - נגזרת מהקוד בכלי ונשמרת בשער. גרסה 5 הוצעה ב-S35-CD.

## פעיל

### קטלוג השירותים - לינה - לאישור

כרטיסי עשר הקטגוריות, רשימת תעריפים ומרשם נכסים; עמוד רשומה מלא בשלוש לשוניות - סקירה, מחיר ותנאים, בדיקה ומקור. רשומה מיובאת נכנסת ללשונית הבדיקה עם תור שאלות פתוחות לצד קטע המקור. תעריף צוות, תקציב לינת צוות ושורה מהקטלוג הישן.

- תאריך: 10.09.2026 · סשן: S55 עיצוב ← S56 בנייה
- מזהה: `2026-09-10-s55-catalog-accommodation` · גרסה 3
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-09-10-s55-catalog-accommodation.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-09-10-s55-catalog-accommodation.md
- הערה: v3 - לאישור דב. נבנתה לפי כיוון העיצוב שנבחר בתשובת המאסטר מ-10.09.2026, אחרי שלושה סבבי ביקורת אדוורסרית. v2 (עמוד יחיד) ו-v1 (מגירה) נגנזו.

### הגדרות וחיבורים - v1.3 - בעבודה

מיפוי שדות, אופן הרצה, גרסאות מיפוי ופעולות באזור ההגדרות. המסגרת שממנה נגזר מוקאפ הקטלוג.

- תאריך: 08.09.2026 · סשן: S53
- מזהה: `2026-09-08-s53-settings-integrations-v1.3` · גרסה 1.3.6
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-09-08-s53-settings-integrations-v1.3.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-09-08-s53-settings-integrations-v1.3.md
- הערה: דב אישר את מחוון החיבור בלבד (09.09.2026). יתר העיצוב בבדיקה. הקטלוג והתבניות מחייבים דיון. אין אישור פריסה.

### הגדרות וחיבורים - v1.2 - מאושר

חזות כל אזור ההגדרות: מעטפת אחידה, נתיב ניווט מהסייר, הכניסות הקיימות, ודוגמת חיבור ומיפוי ספק עצמאי עם עורך שדות, סמכות, המרה והתנגשויות.

- תאריך: 08.09.2026 · סשן: S53
- מזהה: `2026-09-08-s53-settings-integrations` · גרסה 1.2
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-09-08-s53-settings-integrations.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-09-08-s53-settings-integrations.md
- הערה: מאושר בידי דב, 08.09.2026. בדיקת דפדפן וזרימות עדיין נדרשת; אין אישור פריסה.

## ארכיון

### רדיזיין כרטיס ההזמנה - בעבודה

חמישה טאבי-כפתורים עם נקודות מצב, פס סיכום דביק בעדכון אוטומטי, שכבת B2C נגזרת, מדינות רב-ערכיות ועורך מדרגות.

- תאריך: 29.07.2026 · סשן: S35-BUILD-B
- מזהה: `2026-07-29-s35cd-order-card-redesign` · גרסה 4
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-29-s35cd-order-card-redesign.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-29-s35cd-order-card-redesign.md
- הערה: הסטטוס באינדקס - בעבודה אחרי סבב הביקורת. הסשן שבנה לפיו (S35-BUILD-B) נסגר מאז.

### כרטיס ה-CIT כתוכנית - בעבודה

ימים בלבד, הרכבי ייחוס, יצירת הזמנה מהתוכנית, וכל הטאבים מחווטים.

- תאריך: 29.07.2026 · סשן: S35-BUILD-B
- מזהה: `2026-07-29-s35cd-cit-card` · גרסה 1
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-29-s35cd-cit-card.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-29-s35cd-cit-card.md
- הערה: הסטטוס באינדקס - בעבודה; דב אישר את הבסיס. הסשן שבנה לפיו נסגר מאז.

### כרטיס השותף - בעבודה

כרטיס מידע בלי נקודות מצב: אזור המסחר עם מטבע ומע"מ בירושה, מדינות רב-ערכיות, וחמישה טאבים כולל טבלת מקטעי השותף.

- תאריך: 29.07.2026 · סשן: S35-BUILD-B
- מזהה: `2026-07-29-s35cd-partner-card` · גרסה 1
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-29-s35cd-partner-card.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-29-s35cd-partner-card.md
- הערה: הסטטוס באינדקס - בעבודה אחרי סבב הביקורת. הסשן שבנה לפיו נסגר מאז.

### אזור ההגדרות - טיוטה ראשונה - בעבודה

בית ההגדרות ככרטיסים עם אייקונים, רדיזיין מסך המילון, היפוך ברירת המחדל בבורר השותף ורוחב אחיד.

- תאריך: 29.07.2026 · סשן: S35-BUILD-B
- מזהה: `2026-07-29-s35cd-settings-area` · גרסה 1
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-29-s35cd-settings-area.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-29-s35cd-settings-area.md
- הערה: הוחלף בפועל על ידי מוקאפ ההגדרות של S53 (08.09.2026).

### בולק בשורש הסייר - מאושר

כרטיסי תיקייה עם תיבת סימון בפינה ופס הבולק הקיים. אין עדכון שמות בבולק.

- תאריך: 29.07.2026 · סשן: S35-BUILD-B
- מזהה: `2026-07-29-s35cd-folders-root-bulk`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-29-s35cd-folders-root-bulk.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-29-s35cd-folders-root-bulk.md
- הערה: סגור עיצובית בהכרעת דב, 29.07.2026.

### תהליך התמחור המלא - מאושר

מהגישה ועד המחיר: פסי שלבים, שיוך מסמך, טבלת הרכבה, בורר תחבורה רב-בחירה, צוות, ברומטר מטבע, מודלי מרווח ומדרגות, עמלות, גרסאות, תקציב ולוח תשלומים.

- תאריך: 27.07.2026 · סשן: S34-S35
- מזהה: `2026-07-27-s32f-pricing-flow-e2e`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-27-s32f-pricing-flow-e2e.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-27-s32f-pricing-flow-e2e.md
- הערה: אושר סופית בפתיחת S35. זהו חוזה העיצוב של מנוע התמחור.

### חלון החישוב והדיאלוג - מאושר

חלון החישוב ברוחב מלא עם מעקב דו-רמתי ומילון פר תחנה, והדיאלוג המולטימודלי עם צ'יפ הקשר וכרטיס הצעת פעולה.

- תאריך: 27.07.2026 · סשן: S34-S35
- מזהה: `2026-07-27-s32f-calc-window-dialog`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-27-s32f-calc-window-dialog.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-27-s32f-calc-window-dialog.md
- הערה: אושר סופית בפתיחת S35; הוכרע ב-S34.

### אנטומיית הכרטיס - מאושר

כרטיס ההזמנה עם התמחור בראש והתקציב במקטע, וכרטיס התוכנית שעוצב שם לראשונה.

- תאריך: 27.07.2026 · סשן: S34-S35
- מזהה: `2026-07-27-s32f-card-anatomy`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-27-s32f-card-anatomy.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-27-s32f-card-anatomy.md
- הערה: אושר סופית בפתיחת S35.

### הדיאלוג ומסך המילון - מאושר

כותרת הדיאלוג המורחבת, בורר המודל, כפתור ההרחבה לפאנל צד, ומסך ניהול המילון בהגדרות עם דיאלוג עריכה, ולידציה ותצוגה מקדימה.

- תאריך: 27.07.2026 · סשן: S35
- מזהה: `2026-07-27-s35-dialog-and-dictionary`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-27-s35-dialog-and-dictionary.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-27-s35-dialog-and-dictionary.md
- הערה: מאושר בידי דב, 27.07.2026.

### חמישה אלמנטים - בעבודה

חיווי הפרש מול מערכת הלקוחות, מקור סנכרון בהרשאות, הודעת תאימות בתאריכים, ריבוי מטבעות פר מקטע, ובידוד דו-כיווני.

- תאריך: 24.07.2026 · סשן: S32c-S32e
- מזהה: `2026-07-24-s32-five-elements`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-24-s32-five-elements.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-24-s32-five-elements.md
- הערה: הרצף אושר; חלופות פר אלמנט לא נבחרו.

### מעטפת ספריית העיצוב - מאושר

מעטפת ספריית העיצוב ומפרט העוזר.

- תאריך: 21.08.2026 · סשן: S38-LIBFILL
- מזהה: `2026-08-21-s38-libfill-shells`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-21-s38-libfill-shells.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-21-s38-libfill-shells.md
- הערה: כותרת הקובץ אומרת מוקאפ מאושר. אינו רשום באינדקס ה-README.

### סרגל הצד - סטטוס לא ידוע

הקבוצה המתקפלת, פקד הכיווץ והמבנה השטוח.

- תאריך: 29.08.2026 · סשן: S8-SPLIT
- מזהה: `2026-08-29-s8-split-rail`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-29-s8-split-rail.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-29-s8-split-rail.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד.

### עוזר ה-AI על הדשבורד - סטטוס לא ידוע

עוזר ה-AI על הדשבורד האמיתי, גרסה 5.

- תאריך: 19.08.2026 · סשן: S37-ASSIST
- מזהה: `2026-08-19-s37-assist` · גרסה 5
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-19-s37-assist.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-19-s37-assist.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשנים שבנו את העוזר נסגרו.

### מסך המילוי לאחור בתיוג - סטטוס לא ידוע

מסך המילוי לאחור של תיוג הקבצים.

- תאריך: 13.08.2026 · סשן: S41-TAGON
- מזהה: `2026-08-13-s41-tagon-backfill`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-13-s41-tagon-backfill.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-13-s41-tagon-backfill.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשן נסגר.

### חיפוש אחד על הכל - סטטוס לא ידוע

סייר התיקיות: תיבת חיפוש אחת ושני ערוצים גלובליים.

- תאריך: 12.08.2026 · סשן: S41-SEARCH
- מזהה: `2026-08-12-s41-search`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-12-s41-search.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-12-s41-search.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשן נסגר.

### שורת התוצאה בחיפוש - סטטוס לא ידוע

טבלת הסייר מול טבלת התוצאות.

- תאריך: 12.08.2026 · סשן: S41-SCREEN
- מזהה: `2026-08-12-s41-screen-filerow`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-12-s41-screen-filerow.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-12-s41-screen-filerow.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשן נסגר.

### סייר התיקיות - סטטוס לא ידוע

חיפוש על העץ, מחיקה, השבתת ההעלאה ותיבת הסימון בכרטיס.

- תאריך: 11.08.2026 · סשן: S41-EXPLORER
- מזהה: `2026-08-11-s41-explorer`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-08-11-s41-explorer.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-08-11-s41-explorer.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשן נסגר.

### לוח ניהול הפרויקט - סטטוס לא ידוע

לוח ניהול הפרויקט.

- תאריך: 31.07.2026 · סשן: S39-STATE
- מזהה: `2026-07-31-s39-widget-mockup`
- מסך: https://dov-cyber.github.io/hub-ui-preview/m/2026-07-31-s39-widget-mockup.html · טקסט: https://dov-cyber.github.io/hub-ui-preview/llm/2026-07-31-s39-widget-mockup.md
- הערה: אינו רשום באינדקס ה-README - הסטטוס לא תועד. הסשן נסגר.

---

נבנה בכלי `tools/mockups-publish.js` מהמקור `coworker-notes/mockups/publish.json`.

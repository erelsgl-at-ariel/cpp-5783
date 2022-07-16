<div dir='rtl' lang='he'>

תיכנות מערכות ב - מטלות וציונים
==================================

מטרה
====
מטרת הקורס היא לאמן אתכם לתכנת ב- ++C ברמה גבוהה, וכדי להגיע לזה צריך לתכנת – והרבה.

כדי להצליח בקורס, מומלץ להקדיש כ-10 שעות בשבוע לחזרה, תירגול ופתרון המטלות.

חישוב הציון
============

**אופן חישוב ייקבע באופן סופי לפני תחילת הסמסטר. הכתוב למטה הוא טיוטה בלבד.**

הציון בקורס מתבסס על צבירת נקודות באופן הבא:

## מטלות שבועיות (חובה)
הגשת המטלות היא **אישית**.
מותר להתייעץ ולקבל עזרה, אבל יש לדווח בכתב באופן מלא ומפורט כל עזרה שקיבלתם, בהתאם ל[תקנון היושר של המחלקה](https://www.ariel.ac.il/wp/cs/wp-content/uploads/sites/88/2020/08/Guidelines-for-Academic-Integrity.pdf).

ניתן לפתור את המטלות בכל מערכת-הפעלה שאתם רוצים, אולם לאחר הפתרון יש לוודא שהפתרון רץ נכון על מערכת **לינוקס אובונטו**, כי זו המערכת שבה נבדקים הפתרונות.

יש להעלות את הפתרון שלכם למאגר (repository)
חדש בגיטהאב,
ולהגיש במודל קובץ טקסט
(txt) בפורמט הבא:
* השורה הראשונה תכלול את הכתובת של המאגר-גיטהאב שאליו העליתם את הפתרון;
* השורה שניה תכלול מזהה-commit הרלבנטי;
* השורה השלישית תכלול את תעודת הזהות שלכם.

פתרון נכון ומלא של המטלה השבועית מזכה ב-**1** נקודה.
 כל המטלות חובה. כדי לעבור את הקורס, יש להגיש את כל המטלות באופן עצמאי, ולקבל עליהן ציון עובר.

## הגשת מטלות באיחור

אחת ממטרות הקורס היא לאמן אתכם לעמוד בזמנים. 
זמני הגשת המטלות ידועים מראש, ויש לתכנן מראש את זמנכם כך שתספיקו לעמוד בהם - לא לחכות לרגע האחרון.

עם זאת, לפעמים יש סיבות מוצדקות להגשה באיחור. 
כדי לטפל בנושא בצורה יעילה, ולחסוך זמן לכם ולנו,
אנחנו מאפשרים לכם מראש להגיש באיחור
**שתי פעמים**,
מסיבה מוצדקת בלבד,
בלי לבקש אישור מאיתנו
(אנחנו סומכים עליכם שתדעו מהי סיבה מוצדקת).

אם בחרתם להגיש באיחור, עליכם לבדוק לעצמכם את המטלה
בעזרת `bash grade`
ולחשב את הציון שלכם.
לאחר מכן, עליכם להגיש את המטלה שלכם בתיבת-הגשה מיוחדת שנפתחה במודל:
"הגשה באיחור מסיבה מוצדקת - פעם ראשונה"
או
"הגשה באיחור מסיבה מוצדקת - פעם שניה".
הציון על הגשות באיחור יינתן בסוף הסמסטר.

בקשות להגשה באיחור שלוש פעמים או יותר יתקבלו רק במקרים חריגים ובהתאם לנהלי האוניברסיטה,
כגון: מילואים או מחלה במשך שלושה שבועות רצופים (עם אישור בכתב).
במקרים חריגים מסוג זה, יש לשלוח את כל האישורים הדרושים לבודק המטלות ולבקש שיבדוק לכם את המטלה באיחור.

**שימו לב**: 
גם אם הגשתם באיחור מסיבה מוצדקת, 
וגם אם לא הגשתם בכלל וויתרתם על הנקודות,
 *חובה להגיש את כל המטלות עד יום לפני בחינת מועד א.*
זאת כיוון שחלק מהשאלות בבחינה עשויות להסתמך על המטלות.

## הצגת קוד
בתיכנות יש דברים חשובים שקשה מאד לבדוק אוטומטית – למשל, קשה לבדוק שכתבתם בדיקות ברמה גבוהה, תיעדתם כמו שצריך, וכו'. חשוב לנו שתקבלו משוב גם על הדברים האלה, ולכן אנחנו מעודדים אתכם להציג את הפתרונות שלכם בפני 
המתרגל/ת במעבדה כדי לקבל הערות לשיפור הקוד - code review.
הצגה מוצלחת מזכה בעד **12** נקודות.
יש להציג שלוש מטלות לפי הפירוט הבא:

* מטלה 1 או 2;
* מטלה 3 או 4;
* מטלה 5 או 6.

כדי להציג שלוש מטלות יש להירשם להצגה אחת לכל ארבעה שבועות בממוצע.
תיכנון הזמן על אחריותכם - לא תהיה אפשרות להציג כמה פעמים בבת-אחת בסוף הסמסטר.

סטודנטים שיציגו ארבע מטלות או יותר (רק אם יהיה זמן לכך, ולא על-חשבון סטודנטים אחרים)
יקבלו את שלושת הציונים הגבוהים ביותר.

הציון נקבע ע"פ רמת ההבנה שלכם את הפתרון, וכן לפי הקריטריונים הבאים:

* בדיקות - כיסוי מלא של כל הפונקציות, מקרי-הקצה והחריגות.
* תוכנית-הדגמה המדגימה את כל הפונקציות, כולל אלה שאי-אפשר לבדוק אוטומטית.
* נכונות - מימוש מלא של כל הפונקציות, כולל אלו שלא נבדקות אוטומטית. מימוש ללא שגיאות - בפרט שגיאות שאינן נבדקות אוטומטית.
* קריאות - הקוד ברור ומובן גם למי שלא כתב אותו, ללא צורך בהסברים נוספים. יש הערות במקומות הנכונים. סגנון-הכתיבה עקבי.
* בטיחות - בדיקות תקינות קלט, זריקת חריגות בעת הצורך, ומניעת דליפת זיכרון.
* יעילות - בחירת אלגוריתם מהיר, מימוש יעיל ללא כפילות קוד, ניהול זיכרון יעיל.

בנוסף, יינתן מענק נקודות לסטודנטים היצירתיים והמקוריים ביותר בכל מעבדה.


## מענק על בדיקות

סטודנטים שהשקיעו בבדיקות יחידה בחלק א של המטלה, מוזמנים לשלוח את הבדיקות שלהם לבודק המטלות.
הבודק יבחר את הבדיקות הטובות ביותר, וישתמש בהן בחלק ב של המטלה.
הסטודנטים שהבדיקות שלהם ייבחרו יזכו במענק של **4** נקודות לציון הסופי.
כדי לזכות במענק, יש לתקן תקלות וטעויות שמתגלות בבדיקות במהלך העבודה על חלק ב.


## בחינה סופית
בבחינה הסופית אפשר לצבור עד **50** נקודות.
יש לקבל לפחות **30** נקודות מתוכן כדי לעבור את הקורס.

השאלות בבחינה הסופית יהיו דומות למטלות ולדוגמאות הקוד שהוצגו בשיעורים.
מומלץ לפתור את המטלות וללמוד ברציפות לאורך הסמסטר, ולא לחכות לרגע האחרון.

## אפשרות לשינוי הרכב הציון
אם מסיבה כלשהי (כגון: מגיפה) לא תהיה אפשרות לקיים בחינה סופית בקמפוס,
ייתכן שהרכב הציון בקורס ישתנה ויתבסס על מטלות בלבד.
במקרה זה, ייתכן שתקבלו הזדמנות להיבחן על מטלות נוספות מבין המטלות שהגשתם.
זו סיבה נוספת לכך שחייבים לפתור את כל המטלות בזמן ובאופן עצמאי.

</div>
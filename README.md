# Israel_Neighborhood_Data_Thesis
information of about 20 neighborhood characteristics of 159 nighborhoods in Israel
אתם מוזמנים להשתמש בקובץ כראות עיניכם רק תעשו את זה על אחריותכם, קחו בחשבון שעלולות ליפול טעויות ותנו קרדיט למי שמגיע.  ט.ל.ח
אז הטבלא מכילה 159 שכונות שהן כל שכונות המגורים ב-7 הערים הבאות: הרצליה, ת"א, חולון, ראשון לציון, מודיעין, אשדוד וב"ש. השכונות מתבססות על הפרסומים הרשמיים של העיריות ולפי גבולות האיזורים סטטיסטיים של הלמ"ס. כלומר, כל שכונה מכילה אחד או כמה איזורים סטטיסטיים {בסוגריים מסולסלים אני כותב את מקורות המידע עליהם התבססתי}
 הפיצ'רים שיש לכל שכונה הם: 
neighborhood_name- שם השכונה {עיריות}
Main_Style- סגנון השכונה הראשי כפי שהגדרתימתוך הסתכלות על תבעו"ת השכונה המקוריות ובחינת סגנון הבניה בה
FID- מס' סידורי לכל שכונה 
Shem_Yishu- העיר בה השכונה נמצאת
socio_Eshk- האשכול הסוציו-אקונומי { למ"ס מפקד 2008}
TimToAzr- זמן הנסיעה ממרכז השכונה למחלף השלום בת"א (מרכז המטרופולין ת"א) ביום חול בין השעות 08:00 ל- 09:00 {Google maps}
TimToMet- זמן הנסיעה בין 08:00 ל- 09:00 למרכז המטרופוליני שאליו כל שכונה שייכת. שזה מחלףהשלום לכל השכונותמלבד שכונות ב"ש, שלהן מרכז המטרופולין הוא מרכז העיר ב"ש {Google maps}
TimToOld- זמן הנסיעה למרכז העיר הותיק של כל שכונה (לרוב נמצא במרכז הפיזי של העיר) {Google maps}
TimToNew- זמן נסיעה מכל שכונה למרכז החדש של העיר (בדרך-כלל המרכז שמכיל קניונים  ו"ביגים" בשולי העיר) {Google maps}
IsSea- האם השכונה צמודה לים
IsPrk- האם השכונה צמודה לפארק עירוני גדול או מטרופוליני
PopDns- צפיפות תושבים לדונם {מפקד 2008 ושכבת האיזורים הסטטיסטיים של מפקד 2008}
BldCov- השטח הבנוי בשכונה ביחס לשטח הכללי שלה {Open Steet Map ושכבת האיזורים הסטטיסטיים של מפקד 2008}
MixUse- כמות מקומות העבודה הקיימים בשכונה ביחס לכמות התתושבים בה (עם משקולות כפולים למועסקים במזון ובמסחר) {מפקד 2008}
MixUse- כמות אפשרויות הליכה ממוצעות מכל בניין בשכונה במרחק הליכה של פחות מ-500 מטר {OSM}
Culdsc- הערכת כמות הרחובות ללא מוצא בשכונה במדד בין 1 ל-3 
Pub_stl- סגנון בנית מבני הציבור בשכונה- אם הם מרוכזים במקום אחד במרכז או מפוזרים בנקודות קטנות בתוך השכונה
Opn_stl- סגנון השטחים הציבוריים הפתוחים בשכונה- אם הם מרוכזים במקום אחד במרכז או מפוזרים בנקודות קטנות בתוך השכונה
ComStl- סגנון המסחר הראשי בשכונה
PrkStl- סגנון החניה הראשי בשכונה
Is_Tree- האם קיימים עצים לאורך הרחובות הראשיים בשכונה
Avg_mesh_4- מחיר ממוצע לדירת 4 חדרים בשכונה {רשות המיסים נתונים מ-1995 עד 2015}
LOG_4_Room_Price-  לוג מחיר ממוצע לדירת 4 חדרים בשכונה {רשות המיסים נתונים מ-1995 עד 2015}
Mean_Price_Percentile- דירוג מ-1 עד 20 של רמת המחירים בשכונה תוך השוואת המחירים בין דירות דומות במספר החדרים ובין אם הן בבית פרטי או משותף {רשות המיסים נתונים מ-1995 עד 2015}


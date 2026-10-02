# התקנה פשוטה

## Claude בדפדפן או באפליקציה

1. [הורידו את הערכה המלאה](https://github.com/Adidinahon/student-claude-skills/releases/download/v1.0.0/student-skills-pack.zip) וחלצו אותה.
2. פתחו [Customize > Skills](https://claude.ai/customize/skills). לחצו על `+` ואז `Create skill` > `Upload a skill`.
3. העלו כל אחד מששת קובצי ה-ZIP מתוך `install/` בנפרד. ודאו שהם מופיעים ברשימה ומופעלים.
4. פתחו שיחה חדשה. העלו קובץ לימוד שלכם או התחילו עם `examples/lecture-03.md`, והדביקו בקשה מ-`EXAMPLE-PROMPTS.md`.

לא מעלים את `student-skills-pack.zip` כולו למסך ה-Skills. זהו קובץ הערכה. מעלים את ששת קובצי ה-ZIP שבתוך `install/`, אחד בכל פעם.

## Claude Code במחשב

אחרי חילוץ הערכה, העתיקו את שש התיקיות מתוך `skills/` אל `~/.claude/skills/`. אם התיקייה לא קיימת, צרו אותה. התחילו שיחה חדשה וכתבו למשל `/lecture-organizer` עם קובץ הרצאה. אם כבר יש סקיל באותו שם, בדקו אותו לפני העתקה ואל תדרסו אותו.

## בדיקה מהירה

העלו את `examples/lecture-03.md`, הפעילו את `lecture-organizer` ובקשו מפת נושאים. התוצאה אמורה להפנות למספרי שקפים ולציין שהחומר מזכיר אחסון אך אינו מסביר אותו. פלט לדוגמה נמצא ב-`DEMO-OUTPUTS.md`.

## אם זה לא עובד

- Skills לא מופיע? בחשבון אישי הפעילו `Code execution and file creation` ב-Settings > Capabilities. בחשבון ארגוני ייתכן שמנהל החשבון צריך להפעיל את היכולת.
- ה-ZIP נדחה? ודאו שבחרתם קובץ מתוך `install/`, ולא את קובץ הערכה המלא.
- הסקיל לא מופעל? ודאו שהוא דלוק ברשימת Skills, פתחו שיחה חדשה ובקשו אותו בשמו.

מקורות רשמיים: [התקנה ב-Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude), [Skills ב-Claude Code](https://code.claude.com/docs/en/skills).

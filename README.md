<div dir="rtl">
<p align="center"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Resources/Whisper.png" /></p>
<h1 id="תמלול-אוטומטי-של-וידאו-ואודיו-באמצעות-whisper">תמלול אוטומטי של וידאו ואודיו באמצעות Whisper</h1>
<p><a href="https://openai.com/blog/whisper">וויספר</a> (Whisper) היא מערכת לזיהוי דיבור (ASR: Automatic Speech Recognition) מבית <a href="https://openai.com">OpenAI</a> הזמינה לציבור הרחב בקוד פתוח. מערכת זו אומנה על יותר מ-680 אלף שעות של אודיו באנגלית ובשפות רבות אחרות &ndash; בהן גם עברית וערבית. מטרת מחברות אלו היא להנגיש את יכולות התמלול של המערכת לציבור הרחב בצורה אינטואיטיבית ונוחה.</p>
<p>על אף שוויספר&nbsp;מיועדת בעיקר לתמלול קבצי אודיו, המערכת יכולה לעבוד גם עם סוגים אחרים של קלט דיבור, כגון נתוני וידאו המכילים דיבור.&nbsp;באופן כללי, המערכת יכולה לקבל כל סוג של קלט אודיו או דיבור בפורמט דיגיטלי שנתמך על ידי ספריית <a href="https://ffmpeg.org/about.html">ffmpeg4</a>, ובכלל זה קבצים בפורמט&nbsp;WAV, MP3, MP4 ו-MOV.</p>
<h2 id="שימוש-נכון-במחברות">שימוש נכון במחברות</h2>
<p>כדי להשתמש במחברות יש להיעזר ב-Google Colab, כלי שמאפשר לנו לצפות ולהריץ את המחברות שהכנו עבורכם מראש. כדי לפתוח מחברת בסביבת Google Colab יש ללחוץ על הכפתור הבא שנמצא בראשית כל מחברת:</p>
<p align="center"><img src="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Resources/colab.png" /></p>
<h2 id="סוגי-מחברות-במאגר">סוגי מחברות במאגר</h2>
<p>מאגר (Repository) זה מכיל מחברות לשימושים שונים:</p>
<div dir="rtl">1. <a href="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Colab/Whisper_Audio.ipynb">Whisper_Audio.ipynb</a>: מחברת לתמלול קבצי אודיו או וידאו (ישירות - ללא צורך בחילוץ שכבת האודיו). למתחילים מומלץ להתחיל עם מחברת זו.<br /> 2. <a href="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Colab/Whisper_Video.ipynb">Whisper_Video.ipynb</a>: מחברת זו מאפשרת לתמלל קבצי וידאו תוך חילוץ שכבת האודיו. לאחר מכן ניתן להשוות את איכות הפלט אל מול המקור.<br /> 3. <a href="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Colab/Whisper_from_Youtube.ipynb">Whisper_from_Youtube.ipynb</a>: מחברת זו מאפשרת להוריד ולתמלל סרטונים מ-Yotube.<br /> 4. <a href="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Colab/Whisper_Speaker_Diarization.ipynb">Whisper_Speaker_Diarization.ipynb</a>: מחברת לתמלול ראיונות וזיהוי דוברים.
<h2 id="דוגמה-מתוך-המחברות">דוגמה מתוך המחברות</h2>
<p align="center"><img src="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Resources/screenshot.png" /></p>
</div>
</div>

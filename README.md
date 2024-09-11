# NIck-name-generator-bot

Bu bot sizga qisqa va uzun nik (ya'ni ismlar va matnlarni) chiroyli ko'rinishga keltirishga yordam beradi. Foydalanuvchi botga qisqa nik yoki uzun nik bo'limlarini tanlab, ism yoki matn kiritadi va 1 dan 59 gacha bo'lgan raqamni tanlaydi.

## Xususiyatlar
- **NIck-name-generator-bot** orqali siz o'zingizga kerakli ism yoki matnni jo'natib, uni chiroyliroq qilishingiz mumkin.

## Texnologiyalar
- Python 3.7 yoki undan yuqori versiya
- aiogram kutubxonasi

## O'rnatish
1. GitHub repozitoriyasini klonlang:
    
    ```bash
    git clone https://github.com/fayozbekabdimannonov/NIck-name-generator-New-update.git
    ```
    
2. Virtual muhit yaratib, uni faollashtiring (ixtiyoriy):
    - **Linux/MacOS:**
      ```bash
      python -m venv venv
      source venv/bin/activate
      ```
    - **Windows:**
      ```bash
      python -m venv venv
      venv\Scripts\activate
      ```

3. Zaruriy kutubxonalarni o'rnating:
    ```bash
    pip install -r requirements.txt
    ```

4. `.envcopy` fayli nomini `.env` qilib o'zgartiring va quyidagi ma'lumotlarni qo'shing:
    ```bash
    BOT_TOKEN=your-telegram-bot-token
    CHANNELS=your-channels-id
    ADMINS=your-id
    ```

## Filtrlar
- **admin.py**: Adminlar uchun maxsus funksiyalarni filtrlaydigan kodlar joylashgan.
- **check_sub_channel.py**: Foydalanuvchining kerakli kanalga obuna bo‘lganligini tekshiruvchi kodlar.

## Klaviatura tugmalari
- **admin_keyboard.py**: Bot interfeysida adminlar uchun klaviatura tugmalari sozlanadi.

## Menyu buyruqlari
- **set_bot_commands.py**: Telegram bot menyusidagi buyruqlarni o'rnatish uchun skript.

## Ishga tushurish
Botni quyidagi buyruq orqali ishga tushiring:
```bash
python bot.py

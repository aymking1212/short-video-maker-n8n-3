# استخدام صورة Node.js الرسمية
FROM node:20

# تعيين مجلد العمل داخل الحاوية
WORKDIR /app

# نسخ ملفات المشروع
COPY . .

# تثبيت الاعتماديات مع تجاهل مشاكل peer dependencies
RUN npm install --legacy-peer-deps

# تحديد البورت
EXPOSE 3000

# أمر التشغيل (عدّله حسب مشروعك)
CMD ["npm", "start"]

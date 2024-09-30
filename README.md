Cara Menggunakan :
- jalankan npm install di cmd
- konfigurasi tailwind css
- install tailwind
- npm install -D tailwindcss
- npx tailwindcss init
- konfigurasi tailwind.config.js dengan cara :
  module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
  }
- tambahkan 3 css ini di file css anda
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
- Jalankan "npx tailwindcss -i ./src/input.css -o ./src/output.css --watch" untuk memproses CLI
- tambahkan file css pada head html
- jika sudah jalankan npm run dev
- dan enjoy 😊

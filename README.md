# 🤖 AI Chatbot Workflow Automation using n8n

<p align="center">
  <img src="https://n8n.io/favicon.ico" alt="n8n Logo" width="100"/>
</p>

<p align="center">
  <b>Automated AI Chatbot powered by n8n</b>
</p>

---

## 📌 Tentang Proyek Ini

Repositori ini berisi *workflow* (alur kerja) otomasi untuk **AI Chatbot** yang dibangun menggunakan **n8n**. 

Workflow ini mengintegrasikan model AI Agent (seperti OpenAI) dengan berbagai layanan lain (seperti HTTP Request, Email/Gmail, dan Memory) untuk menciptakan asisten virtual yang cerdas dan responsif.

## 🚀 Fitur Utama

- 💬 **Chat Trigger**: Menerima pesan secara *real-time*.
- 🧠 **AI Agent**: Memproses percakapan menggunakan model AI (OpenAI Chat Model).
- 🗂️ **Memory**: Menyimpan konteks percakapan agar bot tidak lupa dengan topik sebelumnya.
- 🔗 **Integrasi API**: Terhubung dengan layanan eksternal melalui HTTP Request.
- ✉️ **Notifikasi Email**: Kemampuan mengirim pesan langsung ke Gmail (opsional).

## 🛠️ Cara Menggunakan

1. **Download file workflow**: Unduh file `.json` dari repositori ini.
2. **Import ke n8n**: Buka aplikasi n8n kamu, lalu pilih **Import from File** dan masukkan file `.json` tersebut.
3. **Setup Kredensial**: Jangan lupa untuk mengatur *credentials* (API Key) untuk OpenAI, Gmail, atau layanan HTTP yang kamu gunakan di dalam node n8n.
4. **Jalankan**: Klik **Execute Workflow** dan bot siap digunakan!

---
<p align="center">
  Dibuat dengan ❤️ menggunakan <a href="https://n8n.io/">n8n</a>
</p>

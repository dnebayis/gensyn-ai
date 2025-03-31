Gensyn RL Swarm Node kurulum rehberi

Kendi bilgisayarınıza veya sunucuya kurabilirsiniz. Hangisini tercih ederseniz artık tamamen size kalmış.

⚙️ Kurulum

# Depoyu klonla

git clone https://github.com/gensyn-ai/rl-swarm.git

cd rl-swarm

# Sanal ortam oluştur ve etkinleştir
python3 -m venv .venv

source .venv/bin/activate  

Windows için : .venv\Scripts\activate)

# Gereksinimleri yükle
pip install -r requirements.txt

# RL Swarm'u çalıştır
chmod +x run_rl_swarm.sh  # (Gerekirse izin ver)

./run_rl_swarm.sh

Testnet’e katılmak için Enter bas. (Y seçeneği)

🔐 Giriş:

http://localhost:3000/ adresine gir.

Login butonuna tıkla ve hesabını seç.

Cihazın Swarm’a bağlandı, modelin eğitilmeye başladı.

---------------------------------------------------------

Giriş sorunu yaşarsanız bu kodu terminale yapıştırın

sudo rm swarm.pem

Swarm UI açmak için bu kodu yazın:
docker-compose up --build

Hepsi bu kadar.

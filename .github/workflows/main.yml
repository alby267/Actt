import time
from pypresence import Presence

# Ganti 'CLIENT_ID' dengan ID aplikasi Discord kamu
CLIENT_ID = 'MTA1NTA2MjczMjUzOTQ0NTMyOA.GCzpcq.r6heIAv1JtkHL1Kqz7y9btzqVITi-_PrZ0z-V0
'

rpc = Presence(CLIENT_ID)
rpc.connect()

# Atur detail presence
rpc.update(
    state="Sedang bermain game",
    details="Game favorit",
    large_image="large_image_name",  # Nama gambar besar
    small_image="small_image_name",  # Nama gambar kecil
    start=time.time()  # Untuk menampilkan waktu elapsed
)

while True:
    time.sleep(15)  # Update setiap 15 detik

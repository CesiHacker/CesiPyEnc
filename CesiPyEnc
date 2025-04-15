import requests
import os
import webbrowser

# Terminalı təmizlə
os.system('cls' if os.name == 'nt' else 'clear')

# Telegram kanalını aç
webbrowser.open("https://t.me/DarkHackerCesi")

# ASCII Logo
print("—" * 96)
print("""
       ███████╗ ███╗   ██╗  ██████╗  ██████╗  ██████╗  ███████╗ ██████╗
       ██╔════╝ ████╗  ██║ ██╔════╝ ██╔═══██╗ ██╔══██╗ ██╔════╝ ██╔══██╗
       █████╗   ██╔██╗ ██║ ██║      ██║   ██║ ██║  ██║ █████╗   ██████╔╝
       ██╔══╝   ██║╚██╗██║ ██║      ██║   ██║ ██║  ██║ ██╔══╝   ██╔══██╗
       ███████╗ ██║ ╚████║ ╚██████╗ ╚██████╔╝ ██████╔╝ ███████╗ ██║  ██║
       ╚══════╝ ╚═╝  ╚═══╝  ╚═════╝  ╚═════╝  ╚═════╝  ╚══════╝ ╚═╝  ╚═╝
""")
print("~ Programmer : @Mustafazade043 |  Channel: @DarkHackerCesi ~")
print("—" * 96)

# Tool menyusu
print("  1 - Encode tool [41 dənəlii]     |     Akti  ✅")
print("  2 - Encoder toolu [15 dənəlik]   |  Aktif ✅")
print("  3 - Joker encoder tool                |  Aktiv ✅")
print("  4 - Decode Tool                  |  Bakımda ❌")
print("  5 - Ninja encode tool            |  Aktif ✅")
print("—" * 96)

# Tool linkləri
linkler = {
    "1": "https://raw.githubusercontent.com/CesiHacker/Python/main/encode41.py",
     "2": "https://raw.githubusercontent.com/CesiHacker/Python/main/CesiPyEnc_cesipyenc.py",
     "3": "https://raw.githubusercontent.com/CesiHacker/Python/main/JokerEnc.py",
    "5": "https://raw.githubusercontent.com/CesiHacker/Python/main/ninja-enc.py"
}

# Seçim al
secim = input(" • Seciminizi daxil edin (1-5): ").strip()

if secim in linkler:
    try:
        # Terminalı təmizlə
        os.system('cls' if os.name == 'nt' else 'clear')
        print(f"{secim}-ci tool yüklənir və işə salınır...\n")

        # Toolu yüklə və işə sal
        kod = requests.get(linkler[secim]).text
        exec(kod, {"__name__": "__main__"})
    except Exception as e:
        print("\nXəta baş verdi! Yüklənmə zamanı problem oldu.")
        print(f"Xəta: {e}")
else:
    print("\nSeçdiyin tool hazırda aktiv deyil və ya yanlışdır.")

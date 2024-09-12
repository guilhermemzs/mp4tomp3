Um pequeno script em Python para converter arquivos de vídeo mp4 em áudio mp3. Útil para transformar vídeos de sites como www.ted.com em arquivos de áudio que podem ser usados em qualquer reprodutor de mp3.

Ele usa mplayer e lame para realizar a conversão.

Uso: python mp4tomp3.py [diretório de entrada [diretório de saída]] diretório de entrada (opcional) - define o diretório contendo os arquivos mp4 a serem convertidos (por padrão, usa a pasta atual) diretório de saída (opcional) - define o diretório para exportar os arquivos mp3 (por padrão, usa o diretório de entrada) exemplo: python mp4tomp3.py ./video ./audio

Nota: você precisará do Python (2 ou 3), mplayer e lame para que este script funcione

# Áudio opcional (substitui os sons sintetizados)

Coloque os arquivos em `sfx/` e `music/` e liste-os em `manifest.json`. Exemplo:

{
  "sfx":   { "hit": "sfx/hit.wav", "kill": "sfx/kill.wav" },
  "music": { "dungeon": "music/dungeon.mp3", "boss": "music/boss.mp3", "end": "music/end.mp3" }
}

Nomes de SFX aceitos: swing0 swing1 swing2 hit crit dash kill hurt soul spawn levelup select hover door slam telegraph arrow bossroar shatter victory death
Músicas: dungeon (salas comuns), boss (sala do chefe), end (tela de morte/vitória).
Sem manifest ou sem entrada, o jogo usa o som sintetizado.

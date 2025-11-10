# Nvim
🧠 Neovim Cheat Sheet – Básico y rápido


╔══════════════════════════════════════════╗
║        🟢 NEOVIM - COMANDOS BÁSICOS       ║
╚══════════════════════════════════════════╝

📂 ABRIR / GUARDAR / SALIR
------------------------------------------
nvim <archivo>       → abrir archivo
:w                   → guardar cambios
:q                   → salir
:wq                  → guardar y salir
:q!                  → salir sin guardar
:e!                  → recargar archivo descartando cambios

✍️ MODO INSERCIÓN
------------------------------------------
i  → insertar antes del cursor
I  → insertar al inicio de la línea
a  → insertar después del cursor
A  → insertar al final de la línea
Esc → volver al modo normal

🧭 MOVIMIENTO
------------------------------------------
h / j / k / l        → izq / abajo / arriba / der
0 / $                → inicio / fin de línea
w / b                → siguiente / palabra anterior
gg / G               → inicio / final del archivo
:n                   → ir a línea n (ej: :15)

✂️ EDICIÓN
------------------------------------------
dd  → cortar línea
yy  → copiar línea
p   → pegar
u   → deshacer
Ctrl + r → rehacer

🔍 BÚSQUEDA
------------------------------------------
/palabra   → buscar hacia abajo
?palabra   → buscar hacia arriba
n / N      → siguiente / anterior resultado

⚡ OTROS
------------------------------------------
:!comando  → ejecutar comando del sistema (ej: :!ls)
:set number → mostrar números de línea
:syntax on  → habilitar resaltado de sintaxis

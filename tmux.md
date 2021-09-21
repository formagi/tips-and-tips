# tmux tips

### Verificar sessões existentes
```bash
tmux ls
```

### Conectar/Atachar em uma sessão existente
```bash
tmux a -t nome_sessao
```

### Criar uma nova sessão do tmux
```bash
tmux
```

### Criar uma nova sessão do tmux, nomeada
```bash
tmux new -s nome_sessao
```

### Finalizar/Eliminar uma sessão existente
```bash
tmux kill-session -t nome_sessao
```

### Para dividir a tela na vertical
```
Ctrl+B "
```

### Para dividir a tela na horizontal
```
Ctrl+B %
```

### Para alterar entre paineis
```
Ctrl+B ->
```
Use as setas direcionais do teclado para navegar entre os paineis.

### Para criar um novo painel
```
Ctrl+B C
```

### Para alterar entre paineis
```
Ctrl+B n
Ctrl+B p
```

### Para fazer scroll up/down em um painel
```
Ctrl+B [
```
Use das setas direcionais do teclado para navegar.
Para sair, pressione q.

### Para redimensionar um painel
```
Ctrl+B, Ctrl+<-
```
Use das teclas direcionais para redimensionar o painel para o tamanho desejado.
Observe para não soltar a tela Ctrl enquanto pressiona o direcional.
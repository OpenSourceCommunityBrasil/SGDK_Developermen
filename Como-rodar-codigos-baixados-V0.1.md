# Como rodar códigos baixados das aulas (V0.1)

Este guia é para quem está tendo dificuldade de rodar os códigos disponibilizados nas vídeo-aulas de SGDK do canal **“REST Dataware - Oficial”**.

> Exemplo usado no documento original: vídeo de referência  
> https://www.youtube.com/watch?v=GxTxBK-c8jY&t=1655s

---

## 1) Crie uma pasta de teste

1. Crie uma pasta com o nome que você desejar (ex.: `colisao_exemplo`).

### ✅ Dica de ouro
Quem está começando **não precisa** manter o mesmo nome de pasta/arquivos do exemplo baixado.  
Usar nomes diferentes ajuda a entender melhor erros de caminhos e apontamentos de arquivos/diretórios.

---

## 2) Abra o VS Code em uma janela “limpa”

2. **Não** abra diretamente a pasta do exemplo no VS Code *antes* de criar o projeto.
3. No VS Code, vá em **File → New Window** (atalho **Ctrl + Shift + N**).

> Isso evita um comportamento que às vezes impede compilar/rodar corretamente.

---

## 3) Crie o projeto pela extensão Genesis Code

4. Use o comando da extensão **Genesis Code**:
   - Pressione **Ctrl + Shift + P**
   - Procure por **Genesis Code: Create Project**
5. Selecione a pasta criada no passo 1 (a pasta ainda estará vazia — sem arquivos do exemplo).

---

## 4) Compile e rode para validar o ambiente

6. Ainda no VS Code:
   - **Ctrl + Shift + P**
   - **Genesis Code: Compile & Run Project**

✅ Se compilou e executou (ex.: “Hello Sega!”), seu ambiente está OK.

---

## 5) Copie os arquivos do exemplo baixado para o seu projeto

7. No projeto baixado (o exemplo das aulas), você verá pastas como:
   - `.vscode`
   - `inc`
   - `res`
   - `src`

8. Selecione todas essas pastas/arquivos no diretório do exemplo.
9. Arraste para dentro do seu projeto **no VS Code** (preferencialmente segurando e usando o botão direito).

Quando o VS Code perguntar:
- **Copy Folders** (copiar pastas)
- Depois, **Replace** (substituir) para as pastas/arquivos que já existirem.

---

## 6) Se “parecer que o código está errado” (bug comum)

Em alguns casos o VS Code não “entende” direito a troca de arquivos do passo anterior e você pode achar que o código veio com erro.

✅ Solução rápida:
1. Abra o arquivo `main.c`
2. **Copie todo o conteúdo**
3. **Apague tudo**
4. **Cole novamente**
5. Compile e rode outra vez

---

## Resultado esperado

Após esses passos, o projeto deve compilar e executar conforme demonstrado na aula.

---

## Próximos passos
- Verifique se a extensão **Genesis Code** está instalada e atualizada
- Mantenha um template “limpo” funcionando para reutilizar quando baixar novos exemplos

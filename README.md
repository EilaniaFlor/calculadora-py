Para rodar este script em ambientes Unix (Linux ou macOS), siga os passos abaixo no terminal:

### 1. Dar permissão de execução
Por padrão, arquivos baixados do GitHub não possuem permissão para rodar como programas. Primeiramente, mude o terminal para a pasta onde o arquivo foi baixado e execute o comando abaixo para dar a permissão necessária:

```bash
chmod +x calculadora.sh
```

### 2. Executar o script
Após liberar o acesso, você pode iniciar o script com o comando:

```bash
./calculadora.sh
```

---

> **Nota:** Caso o script utilize comandos que exijam privilégios de administrador (o que não é o caso desta calculadora padrão), adicione `sudo` antes do comando de execução: `sudo ./calculadora.sh`.

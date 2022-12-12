Requisitos:
- binutils
- bfd / libbfd

libbfd não está disponível no binutils padrão, recomendado que instale a versão dev

```
sudo apt install binutils-dev
```

Para compilar, use:

```
g++ *.cc -o binloader -lbfd
```

Futuras atualizações:

- [ ] Permitir a visualização de conteúdo de uma seção específica informada pelo usuário
- [ ] Implementar filtro de Simbolos (Remover simbolos que não possuem correspondência no binário)

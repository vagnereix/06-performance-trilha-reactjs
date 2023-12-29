<p align="center">
  <img alt="Rocketseat Education" src="https://avatars.githubusercontent.com/u/69590972?s=200&v=4" width="100px" />
</p>

## 💻 Projeto

### Como a renderização do React funciona:

- Criar uma nova versão do componente
- Comparar com a versão anterior
- Se houverem alterações, vai atualizar o que alterou

### Quando utilizar Pure Functional Components

- Renders too often
- Re-renders with same props
- Medium to big size

### Quando utilizar useMemo ou useCallback

- Cálculos pesados
- Igualdade referencial (quando a gente repassa aquela informação a um componente filho)

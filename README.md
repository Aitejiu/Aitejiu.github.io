# Aitejiu 的博客

基于 [Astro](https://astro.build/) + [Fuwari](https://github.com/saicaca/fuwari) 的个人博客。

## 本地开发

```bash
pnpm install
pnpm dev
```

## 构建

```bash
pnpm build
```

产物在 `dist/`，推送到 `main` 后由 GitHub Actions 自动部署到 [aitejiu.github.io](https://aitejiu.github.io)。

## 写新文章

```bash
pnpm new-post <filename>
```

文章位于 `src/content/posts/`，站点配置在 `src/config.ts`。

# Gen code
with vscode


when you input `@dom` command, can show below code
```

const dom = {
  id: "@dom"
}
dom.tpl = () =>{
  return `
<div>
</div>
`;
}
export default dom

```

## publish
```
vsce package

vsce publish
```
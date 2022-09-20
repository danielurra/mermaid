# Mermaid
Diagrams using Markdown files with Mermaid<br>
<br>
<img src="/img/mermaid-diagrams.png" alt="Mermaid diagram"><br>
<br>
Example taken from: https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/
<br>
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
      st{Green};
      good((Blue));
      en>Red];
      style en fill:red,stroke:#f66,stroke-width:2px,color:#000,stroke-dasharray: 5 5;
      style good fill:blue,fill-opacity:0.35,color:#FFFFFF,stroke-opacity:0.2;
      style st fill:#008000,stroke:#333,stroke-width:4px;
      
      
```




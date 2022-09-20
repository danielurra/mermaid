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
      st{Rhombus};
      good((Circle));
      en>Flag];
      style st fill:#34eb67,color:#FFFFFF,stroke:#040969,stroke-width:4px;
      style good fill:blue,fill-opacity:0.35,color:#FFFFFF,stroke-opacity:0.2;
      style en fill:yellow,color:#008000,stroke:#4c34eb,stroke-width:3px,stroke-dasharray: 5 5;
      
      
```




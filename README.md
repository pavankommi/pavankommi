<svg fill="none" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
@keyframes text {
 from {background-position: 0% 50%;}
 to {background-position: 100% 100%;}
}
.graphicStyle {
 letter-spacing: 1px;
 font-weight: bold;
 background: url("./assets/background.png");
  -webkit-background-clip: text;
 background-clip: text;
 -webkit-text-fill-color: transparent;
 animation: text 7.5s linear infinite;
}
div {
    display: flex;
    flex-direction: row;
    align-items: center;
}
svg {
  width: calc(var(--letter-count) * 40px);
  height: 180px;
}
      </style>
      <div>
        <h1 class="graphicStyle">Hi there</h1><h1 >👋</h1>
      </div>
    </div>
  </foreignObject>
</svg>
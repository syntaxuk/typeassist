**typeassist**

typeassist is a simple, open-source script that can type automatically for you on certain sites. it’s just a small helper—nothing complicated.

**how it works**

1. paste the script into your console on a typing site

2. it checks the URL to see which site you’re on

3. if the site is supported, it brings up the gui if not, it’ll tell you it’s not supported

**supported sites**

none yet, but more will be added soon

**how to use?**

run this in ur browser console on a supported site: ```(async () => {
  const r = await fetch(`https://raw.githubusercontent.com/syntaxuk/typeassist/refs/heads/main/main.js?_=${Date.now()}`);
  const code = await r.text();
  const s = document.createElement('script');
  s.textContent = code;
  document.body.appendChild(s);
})();```

**disclaimer**

i’m not responsible for anything you do with this, including bans or other issues. use it at your own risk

**want to help?**

this is fully open-source. feel free to fork it, improve it, and share it—just credit me if you post it anywhere public (github, youtube, etc.)

**questions or feedback?**

add me on discord: syntax.uk
or join the server: https://discord.gg/GbBDxCT9cP

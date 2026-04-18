LumiCon .co.uk redirect repo

What this is:
- A tiny GitHub Pages site for lumi-con.co.uk
- It immediately redirects visitors to https://lumi-con.com/

Files:
- index.html  : main redirect page
- 404.html    : fallback redirect page
- CNAME       : custom domain file for GitHub Pages
- .nojekyll   : disables Jekyll processing

GitHub setup:
1. Create a new public repo, for example: lumi-con-co-uk
2. Upload these files to the repo root
3. Go to Settings > Pages
4. Source: Deploy from a branch
5. Branch: main, Folder: /(root)
6. Save
7. In Custom domain, use: lumi-con.co.uk



Notes:
- Wait for DNS/HTTPS propagation after saving
- www.lumi-con.co.uk should redirect as the alternate name once Pages validates it

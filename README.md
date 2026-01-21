# Gauntlet Vault Allocation Charts

Interactive Sankey chart visualizations for Gauntlet vault capital allocations on Morpho Protocol.

## 📊 Charts Included

1. **USDC Frontier V2** - Multi-level V2→V1→Markets flow ($57.92M)
2. **USDC Prime** - Blue-chip collateral strategy ($177.48M)
3. **WETH Prime** - Liquid staking markets ($72.37M)

## 🚀 Deploy to Vercel (5 Minutes)

### Option 1: Using Vercel CLI (Fastest)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   cd gauntlet-charts-vercel
   vercel
   ```

3. **Follow the prompts:**
   - Login/signup to Vercel
   - Set up and deploy (just press Enter for defaults)
   - Your site will be live at: `https://your-project.vercel.app`

### Option 2: Using Vercel Dashboard (No CLI)

1. **Go to** [vercel.com](https://vercel.com)
2. **Sign up/Login** (free account)
3. **Click "Add New..."** → **"Project"**
4. **Choose "Deploy without Git"** 
5. **Drag and drop** this entire `gauntlet-charts-vercel` folder
6. **Click "Deploy"**
7. Done! Your site is live

### Option 3: Using GitHub + Vercel (Best for Updates)

1. **Create GitHub repository:**
   - Go to github.com
   - Create new repository (e.g., "gauntlet-charts")
   - Upload all files from this folder

2. **Connect to Vercel:**
   - Go to vercel.com
   - Click "Add New..." → "Project"
   - Import your GitHub repository
   - Click "Deploy"

3. **Future updates:**
   - Just push changes to GitHub
   - Vercel auto-deploys

## 🔗 Sharing

Once deployed, share the main URL:
- **Landing page:** `https://your-project.vercel.app`
- **Individual charts:** 
  - `https://your-project.vercel.app/gauntlet-usdc-prime`
  - `https://your-project.vercel.app/gauntlet-weth-prime`
  - etc.

## 📁 File Structure

```
gauntlet-charts-vercel/
├── index.html                                    # Landing page
├── gauntlet-usdc-frontier-v2-multilevel.html    # V2 vault chart
├── gauntlet-usdc-prime.html                      # USDC Prime chart
├── gauntlet-weth-prime.html                      # WETH Prime chart
├── vercel.json                                   # Vercel config
└── README.md                                     # This file
```

## 🎨 Adding New Charts

1. Create new chart HTML file
2. Add to this folder
3. Update `index.html` to include new chart card
4. Redeploy:
   - **CLI:** Run `vercel` again
   - **Dashboard:** Drag & drop updated files
   - **GitHub:** Push changes

## 💡 Tips

- **Custom domain:** Add in Vercel dashboard → Settings → Domains
- **Analytics:** Enable in Vercel dashboard → Analytics
- **Preview URLs:** Every deployment gets a unique preview URL
- **Free tier:** Unlimited bandwidth for personal projects

## 🔧 Troubleshooting

**Charts not loading?**
- Check browser console (F12) for errors
- Ensure file names match exactly in index.html

**Deployment failed?**
- Verify all HTML files are in the same folder
- Check vercel.json is valid JSON

## 📝 Notes

- All charts use Plotly.js (loaded from CDN)
- No build process required (pure HTML/CSS/JS)
- Mobile responsive
- Works offline once loaded

## 📞 Support

For deployment issues, check [Vercel Documentation](https://vercel.com/docs)

---

**Created:** January 2026  
**Updated:** Data as of January 21, 2026

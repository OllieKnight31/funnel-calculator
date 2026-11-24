# Funnel Calculator (Financial Model Maker)

A calculator that shows what your funnel is really worth, and what it would take to hit a revenue target.

Pick how you sell (Instagram DMs, a VSL funnel with paid ads, a webinar, a Skool community, cold email, a local service business and 17 more). Enter your price, your volume and the share of people who make it through each step. The page shows revenue, ad spend, profit and new customers, compares every step with published benchmarks, and works backwards from a monthly revenue target to the leads, calls and ad spend you would need.

The whole calculator is one page, `index.html`, with its fonts in the `fonts` folder beside it. There is nothing to install, no account, and no internet connection is needed to use it. Your numbers never leave your computer.

## How to open it

1. Save the whole `funnel-calculator` folder somewhere you will find it again, for example your Desktop. If it arrived as a zip file, unzip it first. Keep `index.html` and the `fonts` folder together.
2. Double click `index.html`. It opens in your web browser.
3. If it opens in a text editor instead, right click the file, choose Open With, and pick Google Chrome.

It was tested in Google Chrome on a Mac. Other up to date browsers should work but have not been checked.

## Your first five minutes

1. **Choose a model** from the list on the left. Each one is a different way of winning customers.
2. **Pick your market** at the top right. UK or US changes the ad cost benchmarks and the starting numbers. The menu beside it changes the currency symbol.
3. Open **Set your funnel**. Type your volume or monthly ad budget at the top, then your own rate for each step (for example the share of booked calls that show up) and your price. Every figure on the page updates as you type.
4. Open **Add your costs**. Four numbers: sales commission, payment fees, delivery cost and fixed monthly costs.
5. Open **Set your target**. Type the monthly revenue you want. The page tells you how many leads, calls and sales a month, a week and a day that takes, and the ad spend if you pay for traffic.
6. Open **Find your biggest win** to see which step is furthest below benchmark and what fixing it is worth over 12 months.
7. Open **See the next 12 months** for a month by month projection of revenue, costs and profit.

**Simple view and Advanced view.** Simple view has fewer steps and hides the detail. Advanced view splits the funnel into more steps and adds payment plans (cash collected against sales signed), a low, expected and high range, and cost and revenue per step.

**Bring in your real numbers** (optional). If you track your funnel, type in how many you had at each step over a period, or upload a spreadsheet saved as CSV. Press Apply to the model and your real rates replace the starting ones. Download template gives you a file with the right column names.

**Build your own.** The button at the bottom of the list makes an empty model. Press Edit steps to rename, add, remove and reorder steps and to say where money is earned.

**Options menu.** Duplicate a model, reset it to its starting numbers, print it or save it as a PDF, and switch between light and dark.

## How the numbers are worked out

- Volume at the top is turned into a monthly figure. A month is treated as 52 weeks divided by 12, which is 4.33 weeks. So 40 a day on 6 days a week is 1,040 a month.
- If you set a budget instead, volume is the budget divided by the cost of each one. A budget of 6,000 at 2 a click is 3,000 clicks.
- Each step is a share of the step before it. 3,000 clicks at 80% is 2,400, then 5% of those is 120, and so on.
- Revenue is the number of sales multiplied by the price. Profit is revenue minus ad spend, commission, payment fees, delivery cost and fixed costs.
- The target works backwards. If you make 84,000 a month and want 100,000, everything needs to be 100,000 divided by 84,000, which is 1.19 times bigger: volume, calls, sales and ad spend.
- Rates are held between 0% and 100%, and a number typed outside the range a box allows is pulled back when you leave the box.

## How to read the benchmarks

Under every step you will see a line like this: **Low 50% · Typical 65% · Good 80%**.

- **Low, Typical, Good** is the range that published sources report for that step. For costs (such as the cost of a click or a lead) it reads **Good, Typical, High**, because lower is better.
- The **label** beside it says where your own number sits: Below benchmark, On benchmark or Above benchmark. The small bar shows the range as a grey band, the typical figure as a tick and your number as a dot.
- **Confidence** (Low, Medium or High) says how solid the evidence is. Low usually means the figures come from agencies and software companies describing their own clients, not from a large neutral dataset.
- **The source line** tells you how many sources stand behind the range and whether they agree: "4 sources agree", "5 sources, they disagree", or "1 source only". Click it. It opens a short note on how the range was chosen and a list of every source with a link and what that source actually says.
- **"No published data, planning estimate"** means exactly that. Nobody has published a figure for that step, so the range is a sensible starting guess. Treat it as a placeholder until you have your own number.
- Some steps have a **Compare with** menu to switch the range to a particular type of business.
- A source marked "page no longer online" was online when the research was done and has since been taken down. It is still listed so you can see where the figure came from.
- Under **Go deeper** in Advanced view, **What to track** lists the measures worth watching each week and every source used for that model.

Benchmarks are published ranges, not promises. They were collected in 2026 and markets move. Once you have a few weeks of your own tracked numbers, trust those over any benchmark. The projections are arithmetic on the numbers you enter. They are not a forecast or a guarantee of income.

## Where your numbers are kept

Your changes are saved automatically in your browser on your own computer. Close the page, open the file again and they are still there.

- They are tied to that browser on that computer. A different browser or a different computer starts fresh.
- Clearing your browsing data wipes them. A private or incognito window does not keep them.
- To keep a permanent record, use Options, Print / PDF.

## Putting it on a web address (free)

You only need this if you want a link you can open on your phone or send to someone else. The page is a single static file, so any free static host works. Two easy routes:

**Netlify Drop (no technical knowledge needed)**
1. Go to app.netlify.com/drop and create a free account.
2. Drag the whole `funnel-calculator` folder onto the page.
3. You get a web address within a minute. You can rename it in the site settings.

**GitHub Pages**
1. Create a free GitHub account and a new public repository.
2. Upload `index.html` and the `fonts` folder to it.
3. In the repository go to Settings, Pages, choose Deploy from a branch, pick the main branch and save. Your address appears on that page after a minute or two.

Once the page is on a web address, **Options, Copy share link** gives you a link that opens the model you are looking at with your numbers in it. The link carries the numbers inside itself and it is long, so paste it into an email or a link shortener if a messaging app cuts it off. Anyone who opens the link gets their own copy. They cannot change yours.

Each visitor's numbers are saved in their own browser. Nothing is stored on the host.

## Troubleshooting

| What you see | What to do |
|---|---|
| The file opens as a page of code | Right click `index.html`, choose Open With, pick Google Chrome. |
| Nothing happens when you double click on a phone | Phones do not open files like this well. Host it (see above) and open the web address. |
| "Copy share link" shows a message instead of copying | That is expected when the page is opened from a file. Share links work once the page is on a web address. |
| Your numbers have gone | They are saved per browser. Check you opened it in the same browser as before and have not cleared browsing data or used a private window. |
| A model looks wrong and you want to start again | Options, Reset to starting numbers. It only resets the model you are looking at. |
| You typed 150 in a rate box and it changed to 100 | Rates run from 0 to 100. Numbers outside the range a box allows are pulled back. |
| Revenue shows 0 | One of the steps, the volume or the price is zero or empty. Check each box in Set your funnel. |
| "Upload CSV" says no names matched | The column names must match the step names of the model you have open. Use Download template to get them. |
| The Google Sheet link will not load | In Google Sheets use File, Share, Publish to web, choose the tab and "Comma separated values (.csv)", and paste that link. An ordinary sharing link will not work. |
| A source link does not open | Websites move and remove pages. The note above the list explains how the range was chosen, and the other sources still stand. |
| The lettering looks plain or different | The `fonts` folder is not beside `index.html`. Put them back in the same folder. The calculator works either way. |
| A red bar appears at the top of the page | That is an error message from the page. Reload it. If it comes back, use Options, Reset to starting numbers on that model. |

## What is in this folder

| File | What it is |
|---|---|
| `index.html` | The whole calculator: every model, the benchmarks and their sources. |
| `fonts` | The three typefaces the page uses, with their open licences. |
| `README.md` | This guide. |

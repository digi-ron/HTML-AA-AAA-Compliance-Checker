# HTML-AA-AAA-Compliance-Checker
 
This is a very simple tool where you input a hex color code, and the webpage will display any color which is AA or AAA compliant, grouped by R/G/B bias and shown as simple colored boxes

## Notes:
- No updates planned as this was a solution to an immediate client indecisiveness issue, which I thought might be useful to someone else
- It's all in one file. This was a combination of laziness, lack of time, and so I didn't have to run a live server to use everything (js is horrible at solutions that work both locally *and* on a server)
- Enter 1 as the iteration count ***at your own risk***. In my testing it *can* work, but choosing something insane like #000000 and entering 1 as an iteration count will stall the page. Chrome for example has memory limits and will force close the page if it hits it.
- Default of 17 is not coincidental, it means that each color code by default can be a 3 character code if needed, e.g. #0FA matches #00FFAA
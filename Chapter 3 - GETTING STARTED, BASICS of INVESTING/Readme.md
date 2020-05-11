Don't lose money! This is the most important rule.

Trading is very emotional - your state of mind when you make money and need to invest again is VERY different from when you lose money and need to invest again. Your CFA or university degree won't teach you this, for a very simple reason: you need to lose money first to feel and understand it. Discipline helps avoid the emotional mistakes, so pay attention to how you behave when you make mistakes and create rules to avoid them next time. There are plenty of resources out there explaining this, from Jim Cramer on CNBC to Investopedia.

General rules:
<li><b>Loss Cut Discipline</b> - maybe the most important of them all. Understand how much loss you can tolerate per position, then cut the position when it happens, and look for other opportunities. There are plenty of stocks in the market, highly unlikely the current LOSING position is the only one that can bounce back!</li>
<li><b>Manage your Risks.</b> There is a reason why you have a whole industry of financial advisers our there that focus specifically on understanding investors risks. This has to do with the kind of equities you invest in, like higher or lower volatility equities, or growth vs stable and so on.</li>

<br>From a programming point of view, the above rules would need to apply to EVERY part/flow of your program, to work like a function decorator for all your algo. It means that at any time, the program can execute only if the relevant above conditions are true. Otherwise, the program would need to execute the "special" operations required to protect it from losses, like a "stop loss" or additional trading meant to minimize/get rid of losses.

(Fig 1 - the thinking/logical flow in implementing the above)
(Example 1 with loss cut and manage risks)

Philosophically speaking, "don't loose money" is actually the opposite of "maximizing returns". Mathemtically speaking (especially in optimization), <b>"don't loose money"</b> is a <b>"greater than zero"</b> condition, which can always be transformed into a <b>greater than X condition</b>, where X is your minimum targeted return.

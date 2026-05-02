# Prompt & Context Engineering Recommendation

As explained, writing good prompts and providing helpful context is essential for achieving good results.

Therefore, here are some recommendations / best practices you should consider.

---

**Concise & Precise**

Keep your prompts concise and focused. Don't overdo; you should, of course, accurately and clearly describe the task you want the AI to tackle. But absolutely avoid including details that don't matter or unnecessary fluff.

---

**No Unnecessary Context**

Providing useful (!) context is crucial. But providing context that actually doesn't matter can be counterproductive.

For example, avoid referencing *(@some-file*) a file you ***THINK*** may matter. Focus on pointing at files you ***KNOW*** matter. 

The same is, of course, true for documentation articles or any other kind of information that's not really relevant => Avoid it!

---

**Think, Plan, Prompt**

When working with AI, you may be tempted to just start typing and then "fix stuff over time". Don't do that!

Think first, then make a plan, then write a good prompt. If you find yourself asking for follow-ups or providing clarifications a lot, consider putting more effort into upfront planning. Even when using "Plan" mode (which you should use for all tasks that aren't super trivial).

---

**Don't "Test" The AI**

If you know that a task will need the AI to overcome a certain challenge, or if you know about a particularly challenging part involved in a task, DON'T hide that information from the AI.

Sure, it can be a nice feeling to see the AI struggle and fail, but if you want to get the job done, share all crucial information with the AI agent.

So, for example, if you know about a particular pitfall or common mistake, include it (AND a recommended solution) in your initial prompt.

---

**Explicitly Tell The AI About Tools It Should Use**

AI agents like Claude Code can use many tools - some built-in (like the "bash" tool, web requests etc.) and some provided via MCP servers (covered later in the course). There also are features like "subagents" or "skills" you can leverage (also covered later).

If you know that a certain tool or feature should be used for a (part of a) task - explicitly tell the AI to do so. Don't hope it automatically uses the right tool or feature just because it theoretically could.

---

As you can tell, there's one main theme across pretty much all recommendations: **YOU** are in control. **YOU** steer the AI.
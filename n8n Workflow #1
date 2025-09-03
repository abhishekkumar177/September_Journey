# 🎯 Beginner-Friendly Things to Do in n8n (Free)
1. Hello World Workflow
Use the Cron node to trigger every 1 minute/hour.
Connect a Set node → add a field like {"message": "Hello World"}.
Connect to a Webhook Response node → browser test.
👉 This teaches triggers → data → output.


🟢 Step 1: Open n8n

If running locally → go to 👉 http://localhost:5678
If using n8n Cloud → just log in.

🟢 Step 2: Add a Trigger

Click the big “+” button.
Choose Manual Trigger (this lets you run it manually to test).
Later, you can replace it with a Cron node to run on schedule.

🟢 Step 3: Add a Set Node

Click the + next to the Manual Trigger.
Choose Set.
In the Set Node, click Add Field → String.
Name: message
Value: Hello World!
So now, your workflow generates the text.

🟢 Step 4: Return the Result

Add another node → choose Respond to Webhook.
(If you don’t see it, just add a NoOp node to test output inside n8n.)
Connect Set → Webhook Response.
In Webhook Response, set:
Response Mode: Last Node
Response Data: All Entries
This ensures your “Hello World” is returned when the workflow is called.

🟢 Step 5: Run It

Click Execute Workflow.
In the Execution preview, you should see:
{
  "message": "Hello World!"
}

🟢 Step 6: (Optional: Make it Automatic)

Replace Manual Trigger with Cron Node.
Set it to run every minute/hour.
Each time it runs, it will generate “Hello World”.

✅ Congratulations — you’ve just built your first working automation in n8n.
This teaches you: Trigger → Process → Output.

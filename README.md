# Vidyen Personal Career Chatbot

This is a small personal experiment where a chatbot speaks as **me** — Vidyen — and answers career-related questions based on what it knows about my background. The idea is simple. What if someone could instantly learn about my experience, my choices, and where I want to go next just by asking?

The model reads a few things from my profile folder:
- My resume
- A short summary I wrote about myself
- My photo (because a face helps set the context)

Then it tries to respond in my voice. When someone asks why I worked in a certain role, or what skills I’ve built, the chatbot answers like I would.

Live Demo:  
https://huggingface.co/spaces/Vidyen/career_conversation

---

## Why I made this

I wanted to learn how to build something that feels personal and has a real-world use case. People often ask similar questions about my career path. This makes that conversation easier, more fun, and more accessible — especially for future networking and interviews.

It’s also a nice way to explore:
- Prompt engineering in a practical setting
- How well a model can mimic a specific persona
- Deploying a lightweight AI app people can try instantly

---

## What’s inside

```text
Vidyen_Personal_Career_Chatbot/
├── app.py           # The chatbot logic and Gradio interface
├── requirements.txt # Python dependencies
└── me/              # Personal data the bot learns from
    ├── linkedin.pdf
    ├── profile.jpg
    └── summary.txt

The app runs with Gradio and an LLM. That’s really all there is to it.

⸻

If you want to try something like this yourself

Fork the project, replace the files in me/ with your own:
	•	Your resume (same filename)
	•	Your picture
	•	A short text about yourself

Tweak the system prompt inside app.py so the model becomes you.
Suddenly you have your own “mini-you” answering questions.

⸻

Acknowledgments

I built this while taking a Udemy course on agents and Gradio.
The structure came from one of the labs, and I modified the behavior to make it personal.

Everything inside the me/ folder and the tone of the chatbot are customized by me.
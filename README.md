# MedBank

(lol sorry quick note, my resume I uploaded says I'm a 2026 grad, since that was from last semester when I was planning on graduating early and I forgot to change it. I'm going to be a 2027 grad since I'm submatting in math and graduating on the regular timescale). 

MedBank is a tool that allows anyone to get an initial cursory self-diagnosis, and find the hospitals nearest
to them with the cheapest copays (most likely) based on these symptoms. It also allows you to
upload medical documents and bills and helps keep track of all this and finance your medical expenses.

The features I added are (at a high level)
- Login Page
- Voice to Text
- Language Translation
- Financing Bills
- Computer Vision
- LLMs / OpenAI API
- Function tool calling (JSON outputs)
- Probability Analysis
- Databases
- Classes (Pydantic Objects)
- Components
- Some responsiveness (wasn't able to finish)
- Smoothing
- A lot more!

[Demo Video](https://drive.google.com/drive/folders/1cUDj_AxYzAXVg9ZRWnMWxfuGQ_fsusUg?usp=sharing)

You can also host it yourself if you make a venv (install python packages),
run the backend with "uvicorn app.main:app --reload --port 8002" and run the 
frontend with 'npm run dev'

Had to remove a lot of files since they were too large (mostly eda and .csv files, all the code is still here -- except for eda of course)

I spent around 10 hours of time actually being locked-in developing this, and another 1-2 on bug fixes/final UI changes, and all that.
I wanted to also put this on my resume so I want a bit beyond lol.

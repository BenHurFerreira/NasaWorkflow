# 🌞 NASA Solar Flare Alert Workflow (n8n)

This project is a hands-on example of automation using [n8n](https://n8n.io/) and NASA’s public API. The goal is to monitor weekly solar flare events and automatically send alerts when C-class events are detected.

---

## 🚀 What does this workflow do?

- Schedules automatic weekly execution
- Queries the DONKI API (NASA) to fetch solar flare events from the last 7 days
- Filters the results to find "C-class" events
- Sends a POST alert to an external endpoint whenever a relevant event is detected

---

## 🔧 How to use

1. Import the [`NasaWorkFlow.json`](NasaWorkFlow.json) file into your n8n instance ("Import Workflow" option).
2. Add your NASA API credentials (free, [sign up here](https://api.nasa.gov/)).
3. Configure the alert destination endpoint (in this example, [PostBin](https://postb.in/) was used to simulate the receiver).
4. Activate the workflow and watch it in action!

---

## 🖼️ Screenshots

### Full workflow in n8n
<img width="1509" alt="Screenshot_nasa_worflow" src="https://github.com/user-attachments/assets/2969260c-cb19-42cb-b811-cb5aa0349001" />

### Example of alert received at the external endpoint (PostBin)
<img width="1710" alt="Screenshot_postbin_nasa" src="https://github.com/user-attachments/assets/0f9b4769-f765-4471-9677-c1f8fe585a75" />


---

## 💡 Motivation

This project was created as part of my practical learning about no-code/low-code automation, public API integration, and real-time event monitoring.  
Feel free to adapt, clone, or suggest improvements!

---

## 📚 Resources

- [n8n Documentation](https://docs.n8n.io/)
- [NASA API](https://api.nasa.gov/)
- [DONKI Solar Flare Docs](https://api.nasa.gov/)
- [PostBin](https://postb.in/)

---

## 📝 License

MIT

---

> Created by [Ben-Hur](https://www.linkedin.com/in/ben-hur-ferreira/) — feedback is welcome!

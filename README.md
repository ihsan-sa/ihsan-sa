## Hi, I'm Ihsan

I'm Ihsan, an electrical engineering student at Waterloo. This fall I directed a team of AI agents through an entire hardware project: [HiFi Lite](https://github.com/Hive-RSI-Lab/hifi-lite), a streaming stereo amplifier. The agents designed the board, firmware, app, case and test bench. Five were built, and all five passed the board's self-test.

The system that runs the agents is [The Hive](https://github.com/ihsan-sa/hive), which is open source ([hivelab.ca](https://hivelab.ca)). Agents share one sandbox and one knowledge base, start each other and split up the work. Changes to its own instructions and code get benchmarked, and only land if they score better. Before The Hive there was [autobox](https://github.com/ihsan-sa/autobox), where agents merged over 3,400 PRs across 26 repos in 8 weeks.

I build the same kind of tooling for hardware. [pcb-flow](https://github.com/Hive-RSI-Lab/hive-pcb-flow) (formerly hwde) takes a written brief to a board a factory can make, with 4 human sign-offs along the way, and its checks caught all 218 faults we planted. [chip-flow](https://github.com/Hive-RSI-Lab/hive-chip-flow) designs GF180 chips, and is currently working on a charge-pump PLL for a Tiny Tapeout tile.

My co-ops were all hardware: signal integrity on 224G links and power for co-packaged optics at Arista, a 200 W GaN inverter for RF plasma at Fab2 (first plasma in three weeks), and power electronics at aiRadar. They're why I can tell when an agent is wrong.

I'm looking for a January to April 2027 co-op. Reach me at hi@ihsan.cc

### Where to start

- [hive](https://github.com/ihsan-sa/hive) · the Hive: a team of Claude Code agents on your own machine
- [hifi-lite](https://github.com/Hive-RSI-Lab/hifi-lite) · the amplifier the agents designed, with the full design record
- [interp](https://github.com/Hive-RSI-Lab/interp) · small interpretability experiments on GPT-2 and Pythia, with predictions written first
- [pcb-flow](https://github.com/Hive-RSI-Lab/hive-pcb-flow) · written circuit brief to an order-ready JLCPCB package; [hwde-boards](https://github.com/ihsan-sa/hwde-boards) has the boards it made
- [chip-flow](https://github.com/Hive-RSI-Lab/hive-chip-flow) · Claude Code skills for chip design with open tools; [ece298a-pll](https://github.com/ihsan-sa/ece298a-pll) is the PLL
- [lesson-builder](https://github.com/ihsan-sa/lesson-builder) · course notes and slides into lessons with an AI tutor inside
- [Ionic-Thruster-and-HVPC](https://github.com/ihsan-sa/Ionic-Thruster-and-HVPC) · 50 kV converter and EHD thruster, behind my research paper

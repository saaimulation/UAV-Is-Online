# 🛩️ "UAV is online"

This is my personal record for the 2026 IMechE UAS Challenge. I lead CFD.  
I’m logging what I’m working on, why I’m changing things, and results I’m happy to share.  
It’s a cockpit view, not a tutorial.

**Quick links**  
• [logbook.md](logbook.md) — dated entries and decisions  
• [UASRules.pdf](UASRules.pdf) — official rules for quick reference  
• media/ — small screenshots and plots  
• docs/ — short write ups when needed

### What this repo is
External aerodynamics for a small delivery-mission UAV. Goal is simple. Build one baseline that runs on a normal laptop. Make small changes that are easy to compare. Keep plots clean with axes, units and a caption that actually says something.

I use SimScale for easy access and because its beginner-friendly for both me and the team. Star-CCM+ might be used when I can get a seat.  
The CAD team uses SolidWorks, so we shall follow that.  
Light Python or MATLAB for quick plotting if needed.  
To protect team IP, there will be no raw CAD or giant solver files here.

### Rules in one paragraph

The wider rulebook covers flight safety, autonomy, time caps, geofence, batteries and isolation links, scrutineering, documents and deadlines. It sets the frame for what we can build and how we fly.    
For the fine print see UASRules.pdf, below are only the bits that change aero decisions.

### Rules that affect aero

• mass and cg  
tight take off mass and a fixed battery spec mean every gram matters and cg bands drive trim and stability targets

• mission time cap  
short autonomous flights set realistic cruise and climb numbers and a thrust to energy budget for sizing

• autonomous path length  
waypoints and geofence make turns wider than straight legs so flown distance is longer and bank adds some drag

• flight termination  
zero thrust behaviour must be predictable, think about glide attitude and how quickly drag grows when props stop

• payload corridor  
water is dispensed between p1 and p3, keep local flow at the release smooth and avoid spray back onto tail and fuselage

• surface junctions and access  
scrutineering and quick assembly force panel splits and doors, place them so they do not trip separation or create sharp steps

• visibility and recovery markings  
high contrast tapes or panels are required, so we need keep edges flush so they do not become unwanted trip strips

If a decision depends on a specific clause I will reference the page from UASRules.pdf in the logbook.

### Credits
Airframe and testing are a team effort. I’ll name teammates in entries when they want to be named as well as linking their profiles.  
This repo is published with the team’s OK. Please don’t reuse images commercially without consent.



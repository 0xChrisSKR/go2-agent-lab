# Roadmap

This roadmap is a public research plan. It does not claim that the milestones are already completed.

## 1. Environment Setup

- Prepare Ubuntu development environment.
- Install ROS2 following official documentation.
- Keep secrets, device identifiers, and private network details out of the repository.
- Document setup notes only after they are tested.

## 2. ROS2 Basics

- Learn ROS2 nodes, topics, services, actions, launch files, and workspace structure.
- Create simple local examples before connecting to GO2 hardware.
- Document what is learned in public-safe form.

## 3. GO2 Connectivity

- Confirm safe connectivity path to Unitree GO2 Air.
- Document only public-safe connection notes.
- Do not publish private network topology, device identifiers, or unsafe command procedures.

## 4. Function Calling To Robot Command Schema

- Design typed command schemas for high-level robot intents.
- Separate AI-generated intent from hardware execution.
- Add validation and approval boundaries before any physical command execution.

## 5. TRACE Agent Skill Integration

- Explore future integration between TRACE Agent workflows and robotics commands.
- Keep TRACE Runtime changes out of this repository.
- Treat this as a research direction until tested.

## 6. Demo Video

- Record a short, safe, public demo after the basics are verified.
- The first demo should focus on a narrow, non-dangerous action and clear explanation.
- Do not claim autonomous navigation or production robotics deployment.

## Claim Boundary

No completed ROS2 integration, autonomous navigation, shipped robotics product, or production deployment is claimed by this roadmap.

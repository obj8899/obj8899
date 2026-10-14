# Profile README setup

## One-time steps
1. Repo must be named exactly `obj8899` and be public. Default branch should be `main`.
2. Settings > Actions > General > Workflow permissions > **Read and write permissions** > Save.
3. Actions tab > run **Generate Snake** manually (creates the `output` branch with the snake SVGs).
4. Actions tab > run **Profile Summary Cards** manually (creates `profile-summary-card-output/`).
5. Reload your profile. If the stats cards are blank, the first run has not finished yet.

## Things to verify before publishing
- `cryoguard-ai` link: only works if you renamed `sample1`. Otherwise change it back to `sample1` in README.md.
- PulsePoint: `studio` and `pulsepointfinal` may be the same project. Confirm which repo you want linked.
- PlaylistPilot has no live URL. Deploy it (Vercel free tier) and add a Live link.
- Every project description comes from a Copilot read of your repos. Open the CryoGuard `model/model.py` and make sure "prediction model" is accurate.
- LeetCode card uses a third-party service (leetcard.jacoblin.cool). If it ever breaks, delete that image and keep the LeetCode badge.

## Optional
- Add your portfolio site link next to LinkedIn and LeetCode in "Open Comms".
- Pin `profile-summary.yml` to a commit SHA (see the comment inside the file).
- Update the "Currently" section whenever your focus changes.

## Profile page (manual)
- Pin the 6 repos in priority order: shortlister, playlistpilot, cryoguard-ai, pulsepointfinal, caranalyser.
- Upload a clean photo, write a one-line bio, set location, add LinkedIn.

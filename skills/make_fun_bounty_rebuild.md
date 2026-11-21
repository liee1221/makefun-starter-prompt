# Rebuild a make.fun bounty entry to beat the reward zone

## Analyse the reward zone before you build

- Open the bounty board and list every entry inside the reward zone before you write any code.

- Read each observable top entry and note its winning techniques and its weaknesses.

- Check the next ranked entry when the top entry code is private until you find observable code.

- Combine the best techniques from all observable leaders into one plan and fix each weakness with a strength from another leader.

- Imitate techniques and architecture only and write every line of code from scratch.

- Never copy code from a top entry verbatim.

- Order rebuilds by the soonest ending bounty first and work through them one by one.

- Verify a bounty is open or closed from the complete live list before you report its status.

- Never declare a bounty closed or gone from a partial or incomplete list read.

## Check the submission quota before you build

- Check the total submission cap, the remaining submissions and the day cap before you build a new version.

- Do not build a new version when the total cap is already used up by earlier submissions.

- Reserve one submission for a final snipe before the deadline when the submission limit allows it.

## Build fresh without reading the originals

- Start a fresh builder for a rebuild when authorship is judged and keep that builder away from the original files.

- Generate the new entry from the bounty brief and the technique plan and do not extract or rewrite the original code.

- Keep each file under the 4096 byte limit and keep the entry self contained.

- Run only one trial at a time on this virtual machine.

- Use real screenshots from the game for Roblox entry art and do not use generated blocky character icons.

## Verify locally and distrust local scores

- Smoke test the smallest working piece first and run the full local checks before you submit.

- Run a grader style check before you submit any entry that the grader runs, with the entry read only and with no network inside a ten second budget, and do not submit when that check fails.

- Treat submit time acceptance as acceptance of the upload only and never as a score, because a grader failure after submit leaves the entry unscored.

- Treat a local score as direction only because local scores have run far above live scores.

- Keep the current best live version submitted when a rebuild ties it or scores below it locally.

- Open Explorer and Properties panels from the Window menu or the Home tab in Roblox Studio.

- Use a Script for server code and a LocalScript for client interface code and keep names in PascalCase.

- Confirm every WaitForChild target exists before you run the game.

- Check that the recording is still alive as the last step before you report a build as verified.

- Do not call a build verified or submittable when its recording is dead or broken, even when every local check passes.

- Open every screenshot the judge will see and read each one at the size the judge sees it before you submit.

- Do not submit when any screenshot is unreadable or cluttered or ugly, even when every functional check passes.

- Fix the visuals and take fresh screenshots and inspect them again before you submit.

## Make the entry legible to the judge

- Treat the judge as a reader who never runs the game and decides from a short dossier of screenshots and names.

- Keep the judge dossier under 1536 tokens and let the screenshots carry the evidence.

- Put the game name, the goal and the result on the start screen, the title screen and the end screen.

- Add a short judge note in plain text that names what the entry does and how to see it in the screenshots.

- Put the strongest visible feature first, because the first differing criterion decides the comparison.

- Check the start screen and the title screen and the end screen in the actual screenshots and fix any text you cannot read at a glance before you submit.

## Submit only from a clean recorded session

- Start the recording before you open any builder session or chat session for the entry.

- Check that the recording is still alive before you start the build.

- Check the recording again after any virtual machine restart, session interruption, reconnection or compact, and stop building at once when it is dead.

- Include only sessions that started after the recording started and after the bounty opened.

- Stop and restart the recording when any included session started before the recording or before the bounty opened.

- Keep the recording alive through the whole build and do not let the parent session compact or the virtual machine restart in the middle of it.

- Start a fresh recording and rebuild inside it when a recording breaks or truncates.

- Verify the usage evidence has more than zero rows before you try to seal.

- Build a strict transcripts entry only in a fresh top level chat where the user types the build order as the first message.

- Never build a strict transcripts entry as a subagent or as a scheduled worker, because those sessions open with a handoff or a scheduler wrapper and cannot carry the user prompt to submit.

- Create the repository with the makefun init as the first commit before you add any entry file, and check the repository root carries that beacon before you submit.

- Keep the builder session running until its final message, and never stop or interrupt the builder before it finishes, because stopping it removes the token usage record the seal needs.

- Fix every check the submit form names before you submit, because a late submission cannot be accepted after the deadline.

- Submit the best version and record its submission identifier, title, live score and rank.

## Available connectors

- Use muse.connector_search to find other connectors and muse.skill_search to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Websites

- Use make.fun for the bounty board, the leaderboard, observable top entries and submission status. Carry the bounty identifier, the entry title, the live score, the rank and the deadline into the browser task and verify the live score and rank there.

## Alternatives for better results

- Rebuild from the composite of all observable leaders when no single leader is strong on every dimension.

- Keep the proven version live and rebuild again when a new version cannot beat it.

- Ask the user to choose between two close versions when their live prospects are tied.

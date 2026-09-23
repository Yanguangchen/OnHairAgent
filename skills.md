---
name: heygen-burmese-facebook-workflow
description: Create Burmese June-avatar videos in HeyGen Video Agent, download the MP4 locally, and distribute requested campaigns to the usual Facebook groups or ON Hair & Beauty Google Business Profile galleries and Burmese updates.
---

# HeyGen Burmese video, Facebook outreach, and GBP distribution

## Repository synchronization — every session

The shared repository is https://github.com/Yanguangchen/OnHairAgent.git. The project checkout is the source of truth for workflow knowledge, campaign records, and assets.

- **At the start of every session**, before campaign work or edits, inspect the current branch, remote, and working-tree status, then run `git pull --ff-only` from the configured upstream. Re-read the pulled `AGENTS.md`, `skills.md`, and relevant dated records before acting.
- Preserve uncommitted work. If local changes would be overwritten, the histories diverge, authentication fails, or the pull cannot complete, report the concrete issue and resolve it without destructive reset, automatic conflict choices, or force-pushing. Do not perform duplicate-sensitive publishing on knowingly stale campaign records.
- For an empty repository with no remote branch yet, an initial pull cannot succeed; verify it is empty, then create the initial commit and establish upstream with the first push.
- **Before ending a session**, inspect new and modified project files. Review the diff and explicitly stage relevant workflow instructions, records, reports, and campaign assets; commit with a descriptive message, then `git push` whenever new files or relevant changes were added. Verify the pushed commit matches the upstream. If there are no relevant changes, no empty commit is needed.
- When the user directly asks to **git push**, run the push for the current tracked branch even if the working tree is clean. If Git reports “Everything up-to-date,” say so plainly; do not create an empty commit or claim new files were uploaded.
- Never blindly stage the entire workspace: exclude credentials, browser/session data, unrelated personal documents, caches, and temporary output. If a new file contains sensitive information outside the authorized project scope, pause before publishing it. Keep the repository visibility unchanged.
- On a rejected push, fetch and inspect the remote changes; integrate safely and retry only after checking conflicts. Never force-push or claim synchronization succeeded when it did not.
- Keep the installed skill synchronized with the repository's `skills.md` after an intentional skill update. Relative record/media paths resolve from the project checkout, not the installed skill directory. On another computer, use that computer's checkout and locally verified media paths.


## Remembered user preferences

- Open HeyGen Video Agent at https://app.heygen.com/home/video-agent.
- Always select the avatar **June**, using the **Avatar** control inside the AI chat box. Verify the actual selection; mentioning June in the prompt alone is insufficient.
- Explicitly instruct the agent to **speak Burmese** and use **Burmese words** for the script, subtitles, and on-screen text. Use Myanmar Unicode, not romanized Burmese. Retain accurate business names and contact details where needed.
- Generate the finished video and download the MP4 to a folder on the user's computer. The established default is `/Users/yanguangchen/Downloads/`, unless the user specifies another local folder.
- When asked to use the full workflow, post the downloaded video to the usual Facebook groups with a Burmese caption.
- The established Facebook identity is **Jia Li in Safari**. Chrome had a different Facebook session in the September 2026 run; verify current identity instead of assuming browser sessions match.
- Proceed through the requested stages using authorization already provided in the conversation. Do not ask the same permission repeatedly. Follow current tool/platform requirements when an additional confirmation is actually required.

These preferences are durable. Business claims, group permissions, membership counts, pending queues, and interface labels are changeable and must be checked when relevant.

## Scope and entry points

Interpret “do the usual workflow” in this project as HeyGen → local MP4 → Burmese Facebook group distribution, unless the user narrows the request. “Download only” stops after the verified local download. “Post this video” reuses that video; it does not authorize generating a replacement.

Creating or updating this skill does not authorize a new campaign, recurring automation, or changes to existing posts. A prior completed campaign is a reference and duplicate marker, not an instruction to repost it.

Before creating content, identify the current business, message, and any offer from the user's request or current campaign material. ON Hair & Beauty was the September 2026 campaign, not a mandatory brand for every future video. Do not confuse its details with TRUST Hair & Beauty. If essential campaign content is missing and cannot be inferred from the active task, ask one concise question while completing independent preparation.

For Facebook research, qualification, and posting, also use the installed skill at `/Users/yanguangchen/.codex/skills/run-singapore-burmese-facebook-outreach/SKILL.md`. Its `references/known-groups.md` is the historical destination registry; this skill supplies the HeyGen stage and newer operational lessons. Use the current computer-use tool documentation. If an older reference mentions an unavailable computer-use skill or obsolete API, use the available supported computer-use interface rather than treating that dependency as a blocker.

## 1. Prepare and check for an existing campaign

1. Identify the requested stages, target account, source media or HeyGen project, and local destination.
2. Read the relevant dated record under `workflow-records/`. For the established September campaign, read [2026-09-22.md](workflow-records/2026-09-22.md).
3. Check whether generation or download is already complete. Reuse a verified finished artifact when the user is continuing that campaign.
4. Before posting, form a campaign identity from the brand, media filename, date, distinctive caption phrase, and eventual Reel URL. Match the specific campaign, not merely a recurring brand or phone number.
5. If generating new content, verify factual claims against user-provided/current business material. Do not invent prices, discounts, locations, service guarantees, staff language ability, or branch counts.

## 2. Generate in HeyGen Video Agent

1. Open the specified Video Agent URL in the user's appropriate logged-in browser session.
2. Click **Avatar** in the AI chat box, select **June**, and verify the selected avatar before submitting the generation request. If June is unavailable, report the concrete issue; do not silently choose another avatar.
3. Supply the campaign brief and explicit language requirements. This is a reusable prompt structure, with bracketed fields filled from the current brief:

   > Create a video for [business] about [verified campaign message]. Use the selected avatar June throughout the speaking scenes. June must speak entirely in Burmese (Myanmar language). Write the narration, subtitles, and all explanatory on-screen text in natural Burmese using Myanmar Unicode, not English narration or romanized Burmese. Preserve the exact business name and verified contact details: [details]. Use only these factual claims: [claims]. End with [approved call to action].

4. A vertical 9:16 video around 30–45 seconds is a practical default for this Facebook workflow when the user has not specified length or format. This is an implementation default, not an explicit user requirement.
5. Review the proposed script/storyboard and available language/avatar settings. Correct English narration, missing Burmese text, or an incorrect avatar before rendering.
6. Start generation and follow the visible progress to a completed playable video. Do not buy credits, upgrade plans, or create a subscription without authorization. If existing credits are insufficient, preserve the project and explain the blocker.
7. Preview the finished video. Check June, Burmese narration, readable Burmese text, correct business information, aspect ratio, and audio/video playback. If an element cannot be verified, state that limitation instead of claiming it passed.

## 3. Download and verify locally

1. Use HeyGen's download/export controls to save the completed MP4 locally. A web link alone does not fulfill the download request.
2. Prefer a descriptive filename such as `[Brand]-Burmese-June-YYYY-MM-DD.mp4`. Preserve existing files; use a distinct suffix for a revision instead of overwriting an earlier campaign.
3. Confirm the exact absolute path exists, is nonempty, and is an MP4. Inspect duration and dimensions with available media tools and preview enough content to confirm this is the intended export.
4. Record the local path, size, duration, dimensions, HeyGen project URL if available, avatar, and language checks. Do not invent an unavailable project URL.
5. Preserve the downloaded original. Transcoding, replacing narration, or editing the video requires an appropriate request or a necessary, explained implementation choice within the current scope.
6. If the task stops at download, return the clickable absolute file link and the verified result.

## 4. Qualify the usual Facebook destinations

1. Verify the current Facebook account is Jia Li in the composer/profile context. Use the user-selected account if the latest request changes it.
2. Resolve destinations by **group ID**, never display name alone. Two usual groups have identical names, and several have very similar Burmese names.
3. Use the established 14 destinations in the dated record as a starting list. Recheck availability, promotion rules, membership, and posting restrictions. Do not expand to new groups merely to compensate for blocked destinations.
4. The four excluded IDs are `645671696293852`, `973381313849352`, `520816972874683`, and `1526842467811315`: prior rules prohibit advertising or self-promotion. Skip them unless a fresh rule review establishes that the prohibition has changed and the current request includes them.
5. A paused group cannot receive a post. A group showing the pending-content limit cannot receive another queued submission. Record the restriction and continue elsewhere; never remove old pending posts or change accounts to bypass it.
6. Search each eligible destination for the distinctive campaign phrase and matching Reel/video. An existing matching post should be recorded as already posted. A pending or uncertain submission is not a reason to submit another copy.

## 5. Publish the video and distribute it

1. Draft a natural Burmese caption based on the verified campaign facts. Preserve accurate brand names/contact details. Do not blindly reuse the historical caption's claims.
2. Upload the **downloaded local MP4** and caption to one suitable public source group. The historical source was `715798822492338`; use it only if it is currently suitable.
3. Inspect the live composer after selecting the file. A media attachment or upload-progress indicator is authoritative even if a native file-picker button looked disabled. Do not reattach while upload/processing is underway.
4. Submit when ready, wait for processing, and locate the finished post by its distinctive phrase and video. Record the source Reel/post URL.
5. Share this completed public video post to each remaining eligible group, one at a time, adding the full Burmese caption in every destination composer. This preserves the normal workflow: upload the local video once, then distribute the resulting Facebook video.
6. If sharing is unavailable but the group permits posting, upload the original MP4 directly. If the user specifically requests separate native uploads, follow that instruction.
7. Observe the outcome after each submission. A closed or cleared composer establishes an attempted submission, not necessarily publication. Capture a success notice, moderation notice, error, or exact live result before deciding whether further action is needed.
8. Do not resubmit solely because an immediate search returns no results. Review the pending-content surface or record the submission as unconfirmed. Never bypass a checkpoint, platform restriction, or group moderation.

## 6. Safari and Facebook operational notes

Use supported computer-use APIs with fresh accessibility state after actions. Re-resolve element indices each time; historical index numbers must not be reused. Prefer accessible controls; inspect screenshots when text is insufficient.

- If Safari shows a nearly empty page tree after navigation or opening a composer, switch to another existing tab, inspect state, then switch back and inspect again. This recovered rendering in the September run.
- If a group is absent from the share picker, search its current displayed name or scroll the list, then visit its canonical group URL to inspect the actual reason. Absence does not prove membership is missing.
- Search a known phrase directly using `https://www.facebook.com/groups/<group-id>/search/?q=<URL-encoded-phrase>` when useful. Verify the loaded group ID and that the result matches the current campaign.
- The composer may clear but remain open after a successful share. A moderated submission may close the composer and display a toast. Neither UI shape alone proves a live post.
- Do not interpret an old account-specific or group-specific restriction as permanent; record its observed date and recheck on a future authorized run.

| Observed Vietnamese label | Meaning/action |
|---|---|
| `Chia sẻ lên nhóm` | Share to group |
| `Tìm kiếm nhóm` | Search groups |
| `Tạo bài viết công khai...` | Public-post caption field |
| `Đăng` | Post |
| `Đã tham gia` | Joined |
| `Cảm ơn bạn đã đăng bài! Hệ thống đã gửi bài viết cho quản trị viên nhóm phê duyệt.` | Submitted for administrator approval; record as pending |
| `Bạn đã đạt giới hạn nội dung đang chờ trong nhóm này.` | Pending-content limit reached; do not submit |
| `Nhóm này đang tạm dừng` | Group paused; skip |

## 7. Google Business Profile galleries and updates

Use this stage when the user requests GBP distribution; saving this procedure does not authorize a fresh upload or make GBP an automatic addition to a Facebook-only request. For GBP work, also read the available local-business-profile skill at `/Users/yanguangchen/.codex/skills/create-yelp-fresha-accounts/SKILL.md`.

1. Reuse the intended local June/Burmese video. Check the recorded path; if the Downloads copy is missing, verify the project copy before considering regeneration.
2. Read the [23 September GBP record](workflow-records/2026-09-23-gbp.md) in the project checkout for campaign identity, exact profile IDs, media, and prior outcomes. That campaign already has eight published updates and eight completed gallery uploads observed pending review. Do not repost it.
3. Verify the current Google account and inventory all matching managed profiles, including business groups and ungrouped profiles. The historical Chrome account was Chen Yanguang (yanguangchensp@gmail.com); verify rather than assuming it remains active. Match branch names, addresses, and profile IDs. Exclude unrelated brands and closed listings unless explicitly requested.
4. The established eight ON Hair targets are Toa Payoh, Simei, Bukit Merah 163, Bukit Merah 164, Block 2 Jalan Bukit Merah, Bedok North 539, Yishun, and Clementi. This is a dated starting registry, not a permanent count: recheck current eligible ON Hair profiles when asked for all.
5. Check the original's duration, dimensions, size, audio, and content against [Google's current gallery guidelines](https://support.google.com/business/answer/6103862?hl=en). On 23 September 2026 these were up to 30 seconds, 75 MB, and at least 720p. When generating specifically for GBP, plan within the current limit rather than the Facebook-only 30–45-second default.
6. If compliance requires a shorter version, preserve the full original and explain the separate derivative. Prefer a complete spoken thought and natural ending; preview the result and verify its metadata. Ask if shortening would materially change the message. The prior 24.6-second trim was campaign-specific, not a standing duration or instruction to speed up speech.
7. For **each branch**, open **Photos → Add photos and videos**, verify the “Posting publicly as” identity, and upload the local MP4 through the supported file chooser. An attachment to an Update alone does **not** satisfy an actual-gallery request. Wait for upload completion and verify the new video in Photos and videos. Do not upload again while processing or pending.
8. Separately publish a natural Burmese **Update**, based on verified campaign facts and a branch-appropriate call to action. Do not add invented prices, branch counts, promotions, or staff-language claims. A text-only Update plus the gallery video fulfilled the September request; attach media to the Update too when requested.
9. Google's **Copy post** flow can distribute the same suitable Update to the remaining branches. Select only intended profiles, verify checked destinations before posting, and then check every destination independently. Never infer that batch submission proves publication everywhere.
10. Confirm each Update through its matching text and Published status or visible latest-owner update. Record galleries separately as uploaded/pending, live verified, rejected, or failed. Pending review is not public availability; do not resubmit merely because media is not yet visible publicly.

If the Update form claims the summary is empty despite pasted text, inspect its state and try a normal keyboard edit in the textbox before submitting again. Check for an existing published post before retrying. After navigation or upload timeouts, inspect the current page first; the action may already have succeeded.

## 8. Durable record and completion report

Write a dated campaign record in this project with local artifact metadata, campaign phrase, source URL, account, and one row per destination ID. Use explicit outcomes: **live verified**, **pending admin approval**, **submitted but unconfirmed**, **already posted**, **blocked**, **skipped by rules**, or **failed**. Preserve prior records and unresolved uncertainties.

Return the local video link, source Facebook link, verified live count, pending count, and blocked/skipped reasons. Do not call pending submissions live. If audience figures are requested, use current observed counts and label their sum nominal combined memberships; unique reach is unknown.

For GBP, record one row per profile ID with separate gallery and Update outcomes, the original and derivative paths/metadata, the caption, account, and any available post IDs. Report the number of completed gallery uploads and published updates separately, explicitly identifying pending Google review. Preserve dated records so future runs avoid duplicates.

Do not automatically schedule monitoring or retries. If the user requests follow-up monitoring, use the product's supported automation mechanism and retain this campaign identity to prevent duplicates.

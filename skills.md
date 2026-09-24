---
name: heygen-burmese-facebook-workflow
description: Create Burmese June-avatar and June-voice videos in HeyGen Video Agent, download the MP4 locally, and distribute requested campaigns to the usual Facebook groups or ON Hair & Beauty Google Business Profile galleries and Burmese updates.
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
- Always select the **June avatar** using the **Avatar** control inside the AI chat box, and separately select the **June voice** in the voice control. Verify both selections; choosing the June avatar or mentioning June in a prompt does not establish the voice. **Do not filter the voice library to Burmese as a prerequisite:** select June voice, explicitly prompt for Burmese speech and text, and assess the generated result. Never silently substitute Coral or another voice.
- Explicitly instruct the agent to **speak Burmese** and use **Burmese words** for the script, subtitles, and on-screen text. Use Myanmar Unicode, not romanized Burmese. Retain accurate business names and contact details where needed.
- Generate the finished video and download the MP4 to a folder on the user's computer. The established default is `/Users/yanguangchen/Downloads/`, unless the user specifies another local folder.
- When asked to use the full workflow, post the downloaded video to the usual Facebook groups with a Burmese caption.
- The established Facebook identity is **Jia Li in Safari**. Chrome had a different Facebook session in the September 2026 run; verify current identity instead of assuming browser sessions match.
- Proceed through the requested stages using authorization already provided in the conversation. Do not ask the same permission repeatedly. Follow current tool/platform requirements when an additional confirmation is actually required.

These preferences are durable. Business claims, group permissions, membership counts, pending queues, and interface labels are changeable and must be checked when relevant.

## Scope and entry points

For this ON Hair project, the user's remembered **full workflow** is HeyGen → local MP4 → Facebook in Safari → all eligible ON Hair GBP galleries → GBP Updates. Follow a narrower current request when given: “download only” stops after the verified local download; “post this video” reuses that video; a request to replace gallery media and post to Facebook does not require duplicate GBP Updates. Resume completed stages from the dated record rather than starting the whole pipeline again.

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
2. Click **Avatar** in the AI chat box and select **June**. Separately open the voice control and select **June voice**. Verify both selections before submitting the generation request. Do not require a Burmese voice-library filter match; the user wants June voice selected and Burmese requested in the prompt. If either June selection is unavailable, report the concrete issue; do not substitute another avatar or voice.
3. Supply the campaign brief and explicit language requirements. This is a reusable prompt structure, with bracketed fields filled from the current brief:

   > Create a video for [business] about [verified campaign message]. Use the selected June avatar and the separately selected June voice throughout the speaking scenes. June must speak natural Burmese (Myanmar language) in a calm, warm, conversational tone at a moderate pace and normal volume—never shouting or using an exaggerated announcer voice. Write the narration, subtitles, and all explanatory on-screen text in natural Burmese using Myanmar Unicode, not English narration or romanized Burmese. Preserve the exact business name and verified contact details: [details]. Use only these factual claims: [claims]. End with a gentle [approved call to action].

4. A vertical 9:16 video around 30–45 seconds is a practical default for this Facebook workflow when the user has not specified length or format. This is an implementation default, not an explicit user requirement.
5. Review the proposed script/storyboard and available language, avatar, and voice settings. Correct English narration, missing Burmese text, the wrong voice, an incorrect avatar, or shouty delivery before rendering. Audition the spoken Burmese in every speaking scene when the preview is available.
6. Start generation and follow the visible progress to a completed playable video. Do not buy credits, upgrade plans, or create a subscription without authorization. If existing credits are insufficient, preserve the project and explain the blocker.
7. Preview the finished video and actually listen to its narration. Check June avatar **and June voice**, natural Burmese pronunciation and calm delivery, readable Burmese text, correct business information, aspect ratio, and audio/video playback. **Inspect actual caption pixels in every speaking scene:** a Burmese-capable font label or HeyGen assurance does not prove that Myanmar letters rendered; square boxes/vertical bars are a failure. Do not finalize or distribute a preview with missing glyphs. Audio presence or loudness measurements alone do not verify the voice or delivery. If the available interface cannot deliver audio to the model, complete the visual and file checks and use the user's listening approval for that exact version when already provided. Only request listening review if it remains missing; record user approval separately from independent assistant audio verification.

## 3. Download and verify locally

1. Use HeyGen's download/export controls to save the completed MP4 locally. A web link alone does not fulfill the download request.
2. Prefer a descriptive filename such as `[Brand]-Burmese-June-YYYY-MM-DD.mp4`. Preserve existing files; use a distinct suffix for a revision instead of overwriting an earlier campaign.
3. Confirm the exact absolute path exists, is nonempty, and is an MP4. Inspect duration and dimensions with available media tools and preview enough content to confirm this is the intended export.
4. Record the local path, size, duration, dimensions, HeyGen project URL if available, avatar, and language checks. Do not invent an unavailable project URL.
5. Preserve the downloaded original. Transcoding, replacing narration, or editing the video requires an appropriate request or a necessary, explained implementation choice within the current scope.
6. If the task stops at download, return the clickable absolute file link and the verified result.
7. If HeyGen's normal Chrome download unexpectedly shows `ERR_BLOCKED_BY_CLIENT`, check whether the MP4 appeared locally despite the error. For a routine retry, close only the affected HeyGen project tab, reopen that saved project in a fresh Chrome tab, and retry its native Download control once; a Chrome restart may also resolve a stale browser session. Verify the actual local MP4 before claiming success. Do not disable browser protections or bypass a persistent block through direct asset URLs. This recovery worked for the 24 September 2026 project after Chrome was restarted; it is not guaranteed for future exports.

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

Use this stage for the authorized full ON Hair workflow or an explicit GBP request. Saving this procedure does not authorize a fresh campaign or add GBP to a narrower Facebook-only request. For GBP work, also read the available local-business-profile skill at `/Users/yanguangchen/.codex/skills/create-yelp-fresha-accounts/SKILL.md`.

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

## 9. Mistakes and recoveries to apply on future runs

These lessons come from the [23–24 September June/Coral correction and distribution record](workflow-records/2026-09-24-gentle-change.md). Read that record when continuing the same campaign. The observations below are dated; the recovery principles are reusable.

- **Wrong voice and unwanted delivery:** the earlier Coral-voice export did not meet the user's June requirement and sounded aggressive to the user. The correction explicitly selected both June controls and requested calm, conversational Burmese at normal volume. The user approved the replacement after listening. Check actual selections and the result; a prompt mentioning June is insufficient, and the exact cause of the aggressive sound was not established.
- **Unreadable Burmese captions:** font changes and HeyGen's assurances still produced missing-glyph boxes. Direct/rasterized Burmese overlays with the broken caption renderer disabled produced readable glyphs in the final export. Inspect actual rendered text throughout the video, including contrast over bright backgrounds, before accepting a caption fix.
- **Premature manual-download handoff and unsupported attribution:** an earlier response claimed the user had manually downloaded the old video without evidence, then treated that as a reason to stop. The user said they had not. A Chrome restart resolved the later download, and the local file was verified. Use the close/reopen native-download recovery in section 3 before declaring a routine download blocked. State what is observed without inventing who saved the file; changing asset hosts is not a remedy for a persistent browser block.
- **Repeated prompting and incomplete follow-through:** carry forward the approved file, listening approval, posting scope, and deletion confirmation. Complete authorized stages autonomously after routine UI recovery. A user-approved exact version does not need another identical audio approval; a fresh version needs its own checks.
- **Safari file selection appeared stuck:** clicking the visible MP4 and Select All did not select it. In the native picker, Command–Shift–G followed by the exact absolute MP4 path and Return selected the file and enabled Upload. Verify the attached filename/progress in the Facebook composer before any retry.
- **An unrelated notification switched Facebook identity:** a “your Reel is ready” notification belonged to an older campaign under another managed profile. Opening it switched the active identity. The correction restored Jia Li, verified the profile, and found the current source Reel by its distinctive caption. Inspect notification age, owner and campaign before opening; recheck the posting identity after notifications or profile changes.
- **Async navigation and posting raced ahead of the UI:** some reads still showed an old group/search URL, and early searches missed newly published posts. Verify the loaded URL, group ID and campaign phrase before interpreting a result. After Post, wait for posting to finish and inspect the outcome before navigating. Re-resolve controls from fresh state; an empty search, closed composer, or generic Jia Li container alone does not prove failure or publication. Check the exact current post in the group feed or pending-content view and avoid duplicate submissions.
- **Duplicate-name picker entries were treated as ordered destinations:** an attempted publish without resolving the exact ID was rejected by automatic approval review because it could target the wrong group. Neither duplicate-name destination was submitted. Resolve identity and current eligibility through read-only checks before composing; picker order is not evidence. Continue safe, authorized work elsewhere. If the specific ambiguity cannot be resolved, explain the automatic review rejection and its reason explicitly instead of calling it a generic permission requirement or claiming distribution is complete. Do not disguise the same unresolved action through a different route.
- **GBP gallery order was not a reliable campaign identifier:** after the new upload, several “Video 2” items were unrelated older campaigns. Open candidates and compare actual creative frames with the known old export; duration is supporting evidence only. Only Clementi's matching Coral item was identified and deleted in this run. Verify the replacement upload and old-media removal separately for every branch. “No match found” does not prove deletion or Google rejection; “pending” disappearing does not prove public availability. Preserve unrelated gallery media and text-only Updates.
- **Progress counts and completion claims need a ledger:** derive totals from per-ID outcomes, including whether the source is included. Record uploads, public visibility, old-video deletions, Updates, and Facebook submissions separately. Verify the exact caption and Reel in each destination; preserve uncertainty when evidence is incomplete. Report a successful Git push separately from an independent remote-head check if that check fails.

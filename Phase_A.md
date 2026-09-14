## Returning to what I built

Two artifacts were built from a script that was a coach advisory narrative grounded in descriptive statistics from Syracuse Women’s Lacrosse season. The audio artifact was from ElevenLabs and video was from D-ID driven by audio from ElevenLabs MP3 rather than D-ID’s own audio.
Revisiting it, I realize the artifacts by themselves are not identifiable as AI generated without the disclosure. Generating such high quality media is very seamless with today’s tools and only requires few dollars for subscription. Although the paywall deters some users from irresponsibly creating media, it doesn’t help to stop a motivated bad actor. The friction to stop a bad actor is simply non-existent in these tools.

## Reasoning across the axes

### Truth axis

In a hypothetical scenario where a fraudulent company trying to financially scam candidates through job applications by charging application fees. It would be very easy for an individual to generate synthetic media with fake employees talking about plausible work at the company and marketing the brand across social media. Candidates generally rely on social media to verify a company’s authenticity and AI content makes it very signal this on social media. Someone not careful enough might get caught in the trap and potentially disclose sensitive information in the application.

### Consent axis

Considering the same example of Syracuse’s Lacrosse coach. Their voice is used to generate a seemingly fake press brief against their wishes and the brief is circulated widely with the material that coach never agreed upon. This would greatly harm the team’s reputation as people have already seen it without knowing this is fake.

### Context axis

It’s very easy for someone to record the artifact from the their mobile off their laptop screens. This would strip the metadata and the artifact could be passed off as real. Someone could claim this to be a real person and hence providing veracity to a non-existent human. This could potentially make people act on the content which otherwise they would have not had they known this is AI generated.

### Scale axis

I would not say anyone with laptop could mass produce because there is expensive compute involved and vendors charge users for it. Although it definitely doesn’t stop a motivated user to spend dollars so they could gain undue benefits. This axis could also be applied to the hypothetical scenario of truth axis where a fraudulent company generates synthetic employees and post them on social media to ensure veracity.

## Mitigation

### Disclosure

This can be a label or watermark so that the user knows it’s synthetic. Breaks because label is separate than the content and if embedded within the content, various tools are available to cheat it. Disclosure also tends to reach the people who were already paying attention rather than the person scrolling past a fifteen second clip, which is exactly the person it needs to reach.

### Provenance and content credentials

Promises a cryptographic record of how the file was made, attached to the file itself, so its history travels with it. I did not test this in Task 6. I tested detectors and not content credentials, and neither ElevenLabs nor D-ID offered credentials anywhere on the free tier export path I used. It breaks because it only works if the tool cooperates. Signed content can be checked, but unsigned content proves nothing, because most real media is also unsigned. So it can raise confidence in something real and it cannot lower confidence in something fake.

### Detection

Promises catching it after the fact with no cooperation needed. This breaks as some of free tier detectors couldn’t call out my AI video. There are better detectors but again they are behind a paywall. This points to a very interesting situation where the creator is motivated and has spent dollars to generate a plausible media but the intended consumer is laid back and I not so careful and wouldn’t spend dollars to figure if the media is real or not and take it at face value.

### Law and regulation

Promises binding penalties regardless of cooperation. EU AI Act Article 50 applicable since 2 August 2026, fines to EUR 15M or 3% of turnover. But Article 3(60) defines a deepfake by *resemblance to* something existing, my avatar resembles nobody, so my artifact likely falls outside it. Breaks because, enforcement is territorial, distribution isn't.

### Platform policy

Intervene when scale harm happens and watermark the content that can be detected without paywall. Breaks if there is an army of individual generating minimum permissible limit on content. Usually performed by actors that operate at industrial scale.

### Professional norms

Corporations should ensure guidelines are met while it’s members use their AI provided tools. This breaks because of nuances when a bad practice is white washed and justified as necessary for business use.

## Policy

## The organizational context

### The Office

The Office of International Recruitment and Admissions at Syracuse University. The staff consists of a director, regional recruitment managers covering South Asia, East Asia, Middle East and Africa, 2 admission counselors, a content coordinator. There is no in house counsel and no dedicated video production staff.

### What they produce

Program overview and campus tour videos. Student and alumni testimonials. Recorded webinars for prospective students in time zones that cannot attend live sessions. Social content for Instagram, YouTube, WeChat and WhatsApp. Translated versions for the priority markets like India, China, Korea etc.

### The Audience

Prospective students from 16 to 25 year olds and their parents. Most will never visit campus before they enrol. The decision they are making is worth 50000\$ to 200000\$ depending on masters or undergrad program and the type of funding.

### Where synthetic media is promising

One student testimonial dubbed into twelve languages costs a fraction of finding twelve students. A dean's welcome message personalized by name for every admitted student is a yield tactic that would take one afternoon to build. A synthetic presenter never graduates, never asks for a release, and never revokes consent.

### The Risk

The audience has almost no capacity to verify and an enormous amount riding on being right. Significant amount of recruitment runs through commissioned education agents, who are paid per enrolment. They have the strongest incentive to exaggerate and the least exposure to consequences.

## Policy on the Use of Synthetic Media in International Recruitment

### Permitted uses

- Voiceover in a language we do not have staff coverage for, where the voice is not presented as belonging to any specific person and the content is factual and institutional like application deadlines, degree requirements, campus facilities, tuition figures.

- Generated background imagery or graphics that does not represent a real person and does not claim to show campus or any real location.

- Machine translation of captions, provided a fluent human reviews every line before publication.

### Prohibited uses

- Synthetically altered testimonial. A student or alumni testimonial must be a real person. Do not dub a testimonial into a cloned or synthetic voice.

- Any synthetic depiction of a person making claims about contextual outcomes like job placement, salary, visa process or admission chances.

- An AI avatar presented as a student, staff or faculty.

- Do not release any synthetic media assets to any education agent without agreement on file to not alter or change the asset in any form.

### Consent workflow

- Consent is obtained in writing before recording in the person’s preferred language. The release states what is being recorded, how long it will be used and it may be subtitled into other languages and will not be synthetically altered.

- Consent is only valid for 24 months and renewal requires fresh signature.

- Consent may be withdrawn at any time by email.

- Participants under eighteen at the time of recording require a parent as a co-signer

### Disclosure standards

Where a permitted synthetic element is used, all of the following are required together.

- A burned in on screen line saying the narration in this video is AI generated.

- A spoken version of the same statement in the language of narration.

- A persistent corner label for the full duration of the video.

- The same statement in the post description on every platform.

### Provenance requirements

- Retain the original file for atleast 3 years after it has been pulled out of circulation. Also maintain the manifest of associated settings change and edits from the default version.

- Attach C2PA content credentials at export wherever the production tool supports it.

- Maintain a public registry of all the synthetic artifacts on University’s domain URL.

### Review and Approval

- Any content containing AI material is reviewed before production by the director and one reviewer from outside the department.

- The question asked is would a seventeen year old in Hyderabad or Lagos, seeing only this clip, with no label attached, forwarded by an agent, be misled about who is speaking or about what Syracuse is promising? If the answer is yes, or if the reviewers are unsure, it does not ship.

- Every decision is logged with its reasoning. The log must be analyzed at every policy meeting.

### Incident Response

- Any staff member who becomes aware of misuse must report to the director within 24 hours.

- The director notifies University and counsel within 24 hours.

- If a real person’s voice or video was used in a way not known to them, that person is contacted before university publishes anything on the incident.

- If a Syracuse asset was misused by an agent, their access is suspended immediately.

- Incident log is maintained and reviewed at every policy meeting.

### Refusal

The office does not produce synthetic media in the following circumstances.

- The content concerns visa outcomes, immigration processes, financial aid decisions, or employment and salary outcomes. These are the subjects where being wrong costs a family the most.

- The content is intended for a channel where we know our disclosure will not survive.

- The request originates from an education agent rather than from this office.

- The timeline does not allow for the review as described above.

## Limitations

### The agent network is the largest hole and the policy barely reaches it

Agents are paid per enrollment , are not employees and operate outside Syracuse jurisdiction. They have the strongest incentive to fabricate and least exposure to the consequences. The policy’s only real instrument is to suspend access but that happens only after harm has been done.

### Nothing here governs the people who are not us

This policy only controls what Syracuse produces. It does nothing about a third party generating a synthetic Syracuse recruitment video from scratch. A public registry of artifacts gives a motivated user a way to check but that protection is thin.

### It relies on self reporting

Nothing in this policy detects a coordinator who runs a rushed translation a night before a fair in Mumbai. My task 6 suggest that if anyone cared to check, audio might get caught through detectors but chances are video might not. Compliance here is self reported and review step only catches the work that gets submitted for review.
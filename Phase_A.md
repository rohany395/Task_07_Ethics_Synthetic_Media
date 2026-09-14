**Returning to what I built**

Two artifacts were built from a script that was a coach advisory narrative grounded in descriptive statistics from Syracuse Women’s Lacrosse season. The audio artifact was from ElevenLabs and video was from D-ID driven by audio from ElevenLabs MP3 rather than D-ID’s own audio.  
Revisiting it, I realize the artifacts by themselves are not identifiable as AI generated without the disclosure. Generating such high quality media is very seamless with today’s tools and only requires few dollars for subscription. Although the paywall deters some users from irresponsibly creating media, it doesn’t help to stop a motivated bad actor. The friction to stop a bad actor is simply non-existent in these tools.  
  
**Reasoning across the axes**

**Truth axis:**  
In a hypothetical scenario where a fraudulent company trying to financially scam candidates through job applications by charging application fees. It would be very easy for an individual to generate synthetic media with fake employees talking about plausible work at the company and marketing the brand across social media. Candidates generally rely on social media to verify a company’s authenticity and AI content makes it very signal this on social media. Someone not careful enough might get caught in the trap and potentially disclose sensitive information in the application.

**Consent axis:**  
Considering the same example of Syracuse’s Lacrosse coach. Their voice is used to generate a seemingly fake press brief against their wishes and the brief is circulated widely with the material that coach never agreed upon. This would greatly harm the team’s reputation as people have already seen it without knowing this is fake.  
  
**Context axis:**  
It’s very easy for someone to record the artifact from the their mobile off their laptop screens. This would strip the metadata and the artifact could be passed off as real. Someone could claim this to be a real person and hence providing veracity to a non-existent human. This could potentially make people act on the content which otherwise they would have not had they known this is AI generated.

**Scale axis:**  
I would not say anyone with laptop could mass produce because there is expensive compute involved and vendors charge users for it. Although it definitely doesn’t stop a motivated user to spend dollars so they could gain undue benefits. This axis could also be applied to the hypothetical scenario of truth axis where a fraudulent company generates synthetic employees and post them on social media to ensure veracity.

**Mitigation:  
**  
**Disclosure:** This can be a label or watermark so that the user knows it’s synthetic. Breaks because label is separate than the content and if embedded within the content, various tools are available to cheat it. Disclosure also tends to reach the people who were already paying attention rather than the person scrolling past a fifteen second clip, which is exactly the person it needs to reach.  
  
**Provenance and content credentials:** Promises a cryptographic record of how the file was made, attached to the file itself, so its history travels with it. I did not test this in Task 6. I tested detectors and not content credentials, and neither ElevenLabs nor D-ID offered credentials anywhere on the free tier export path I used. It breaks because it only works if the tool cooperates. Signed content can be checked, but unsigned content proves nothing, because most real media is also unsigned. So it can raise confidence in something real and it cannot lower confidence in something fake.

**Detection:** Promises catching it after the fact with no cooperation needed. This breaks as some of free tier detectors couldn’t call out my AI video. There are better detectors but again they are behind a paywall. This points to a very interesting situation where the creator is motivated and has spent dollars to generate a plausible media but the intended consumer is laid back and I not so careful and wouldn’t spend dollars to figure if the media is real or not and take it at face value.

**Law and regulation:** Promises binding penalties regardless of cooperation. EU AI Act Article 50 applicable since 2 August 2026, fines to EUR 15M or 3% of turnover. But Article 3(60) defines a deepfake by *resemblance to* something existing, my avatar resembles nobody, so my artifact likely falls outside it. Breaks because, enforcement is territorial, distribution isn't.  
  
**Platform policy:** Intervene when scale harm happens and watermark the content that can be detected without paywall. Breaks if there is an army of individual generating minimum permissible limit on content. Usually performed by actors that operate at industrial scale.  
  
**Professional norms:** Corporations should ensure guidelines are met while it’s members use their AI provided tools. This breaks because of nuances when a bad practice is white washed and justified as necessary for business use.
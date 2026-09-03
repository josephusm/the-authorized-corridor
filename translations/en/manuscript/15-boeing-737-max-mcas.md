---
title: Boeing 737 MAX MCAS
pov: ""
draft: 1
source_path: manuscript/15-boeing-737-max-mcas.md
source_hash: 702f91b45f9fa3f985383accc02e625854e9c088
---

# Boeing 737 MAX MCAS

Part V has to get its hands dirty.

So far the corridor has been described as a device: filter, reducer of overflow, blindness of verification, capture of critique, illegible resistance. But a theoretical device that cannot stand up to a concrete case is only conceptual furniture. Elegant, perhaps. Still furniture. The Boeing 737 MAX serves this purpose: not as an emotional example, not as a tragedy used to add rhetorical weight, but as a stress test. If the authorized corridor means anything, it has to explain why a chain full of engineers, regulators, procedures, simulations, manuals, certifications, and pilots could produce a seam so fragile and yet so difficult to attribute before it failed.

The easy answer is: MCAS.

It is also the wrong answer, or at least too small.

The Maneuvering Characteristics Augmentation System was the visible point of failure. An automated system, tied to angle of attack, capable of commanding nose-down stabilizer input under certain conditions. After Lion Air 610, on October 29, 2018, and Ethiopian Airlines 302, on March 10, 2019, those initials became almost a character: MCAS the culprit, MCAS the killer software, MCAS the bug. I understand the temptation. Initials concentrate. Initials look good in headlines. Initials seem to give pain an address.

But the corridor does not work only by producing a culprit. It also produces the kind of culprit we are able to see.

The MAX did not emerge in a technical vacuum. It emerged under a precise commercial pressure: build an aircraft new enough to compete, old enough not to force airlines and pilots to pay for extensive new training. The new LEAP engines, larger and mounted farther forward and higher, changed the aircraft’s dynamics in parts of the flight envelope. MCAS entered as a seam: not a grand announcement of transformation, but an addition that helped the aircraft behave, at least within the grammar of certification, like a continuation of the previous 737. Already the case ceases to be a software accident. It is a seam joining aerodynamics, market, certification, and training.

A seam is not neutral. It decides where the strain will run.

The brutal point is that MCAS, in its original configuration, could rely on input from a single angle-of-attack sensor. If that sensor lied, the system could believe in an aerodynamic condition that was not there and push the nose down. This was not merely a local defect. It was an architectural choice that granted a single signal disproportionate authority within a scene of high speed, high cognitive load, and little tolerance for ambiguity. The sensor did not have to persuade a robust forum. It had to speak in the right format to the right circuit.

This is the corridor in engineering form: what passes is not what is true, but what the circuit is authorized to treat as valid input.

After the disasters, the NTSB stated the point without poetry, and therefore better: the safety analyses had assumed a certain degree of recognition and a certain response from pilots, but actual crews faced multiple alerts and indications at once. Robert Sumwalt said there was a gap between the assumptions used to certify the MAX and the crews’ real experience.[^boeing-ntsb] It is an almost perfect sentence for this book, and unfortunately I did not invent it. The gap was not outside the system. It was inside the authorized image of the pilot.

The pilot in the certification model was legible.

The real pilot was overloaded.

This difference is the center of the case. The pilot in the model recognizes, interprets, reacts. The pilot in the actual cockpit receives stick shaker, warnings, conflicting readings, moving trim, altitude, airspeed, communications, procedural memory, surprise, seconds disappearing. Certification had not eliminated the human. It had formalized the human. The human was there, but as a predicted function. They were supposed to absorb the deviation within the time and form granted by the model. When they did not—not because they were incapable in the abstract, but because the real scene differed from the modeled one—the corridor displayed its most elegant cruelty: it had left room for the human only where the human had already been simplified.

Here the Boeing case does not repeat Chapter 4. It makes it specific.

The closed loop said: the system eliminates the occasion for verification. The MCAS case shows how that occasion is eliminated earlier, across separate layers, without anyone having to declare, “let us close the forum.” No villain with a cigar is required. It is enough for each layer to have a local reason not to reopen the entire seam.

The commercial layer wants continuity: the same type rating, limited training, no simulator if possible, the promise of a smooth transition. The engineering layer wants to compensate for a handling characteristic without turning the aircraft into a new administrative object. The documentary layer wants to describe the change as small enough to remain manageable. The regulatory layer, even when it is not corrupt in the sense required by a bad novel, works within delegation, trust, information asymmetry, schedule pressure, and dispersed expertise. The cockpit layer finally receives a surface in which the seam has been made opaque precisely because every previous passage treated it as local.

Stratified responsibility does not mean evaporated responsibility.

The opposite. It means the forum must be designed to travel back up through the layers. If it remains in the wrong layer, it produces only neatly sorted scapegoats. The pilot as final operational authority. The engineer as technician who assessed a function. The certifier as bureaucrat who approved a change. The manager as generic pressure. Boeing as company. The FAA as regulator. Each visible in pieces, the whole seam invisible until the aircraft falls.

The corridor loves this form of piecemeal accountability. Not because it absolves everyone, but because it makes the design nearly impossible to contest before the catastrophic event. Every objection has to enter through its own door: software safety here, training there, the manual farther on, sensor redundancy in another office, human factors in a note, market pressure as background noise without a technical field. If you say the problem is the combination, you risk sounding vague. If you say the problem is the seam, the corridor asks which form you mean.

And a seam never has only one form.

Afterward, the Joint Authorities Technical Review saw many things that had previously remained too distributed: MCAS had not been assessed as an integrated function with sufficient transparency; the FAA had not been fully informed as the function expanded; documentation and communication were inadequate; the way pilot recognition and response times were assumed needed to be updated. The House Committee investigation added the political and industrial side: pressure on costs and schedules, weaknesses in ODA, training decisions that minimized the value of training and inhibited more robust technical solutions.[^boeing-jatr-house] These are not appendix details. They are the map of the seam.

The question, then, is not: why did no one see MCAS?

Someone saw pieces of MCAS. Someone knew enough to write, enough to approve, enough to train or not train, enough to document or omit. The correct question is more unpleasant: what forum would have forced those pieces to become one accountable whole before the disaster?

A decent forum would have done at least four jobs.

First: it would have treated MCAS as an integrated function, not as the sum of local changes. Not “this software changes a behavior under certain conditions,” but “this seam connects sensors, stabilizer, manuals, training, expectations about the pilot, and the commercial promise of continuity.” It sounds like a long sentence. It is. Important things are often long because power prefers short fields.

Second: it would have made the assumption about the pilot contestable. Not the ideal pilot, not the pilot as a well-behaved component of the model, but the pilot in the cockpit with multiple alerts and compressed time. The point here is not to insult simulation. Simulation is useful. The point is to stop simulation from becoming a corridor into which only the human already compatible with the hypothesis can enter. If safety depends on human response, then the human scene must be part of safety, not a moral footnote at the end of the chain.

Third: it would have given inconvenient signals the power to stop the process. It is not enough for a risk to be written down somewhere. Chapter 4 called it residue: the alarm waiting for an archaeologist. In the MAX, residue takes many forms: technical information not escalated, manuals that do not tell enough, training built around continuity, classifications that keep a function small after it has become large. A real forum does not archive these frictions as documentation. It hooks them to a lever: until this seam is explained as a whole, it does not pass.

Fourth: it would have made fictitious continuity costly. This is the least technical and most political point. The promise that “no new training is required” is not merely a commercial decision. It is an epistemic decision: it says that the difference introduced does not deserve a new form of attention. Once that promise becomes dominant, every change tends to present itself as a non-change. The corridor does not erase novelty. It disguises it as inheritance.

The inherited signifier returns here with the noise of the engines.

“737” is not merely a model. It is a carrier of trust, procedures, familiarity, type rating, market, schedule. The MAX inherits that signifier and alters it at the same time. This is a dangerous position: new enough to require seams, old enough to want them hidden. The authorized corridor works perfectly in such cases because it does not have to forbid difference; it has to make difference transit as continuity.

The tragedy lies there too: in difference forced to wear the mask of sameness.

There is no need to turn Boeing into a metaphysical monster. That would be convenient, and convenience is almost always a poor investigative tool. Companies apply pressure, protect margins, sell continuity, minimize friction; regulators delegate, chase complexity, trust pieces of process; engineers work within constraints; pilots inherit the latest version of the scene. The point is not to say that everyone is equally guilty. That is another way of accusing no one. The point is that responsibility, when it is stratified, must take a form capable of remaining stratified without dissolving.

The whole seam must be attributable.

A seam is attributable when you can ask: who decided that one sensor was enough for this degree of authority? Who decided that this function remained small enough not to change training and manuals? Who could contest that decision without losing to schedule and cost? Who had a duty to examine the combination rather than the component? What information would have stopped certification instead of merely adding to the file? Where was the brake?

The question of the brake returns because it is vulgar and precise. On the MAX, the brake could not reside only in the cockpit, in the final seconds, on the shoulders of two people discovering the seam while the aircraft used it against them. A brake placed there is already blame disguised as control. The brake had to be upstream: at the moment when the function expanded; at the moment when authority remained vested in a single sensor; at the moment when omission from the manual became convenient; at the moment when “no simulator required” stopped being a technical conclusion and became the corridor through which every other conclusion had to pass.

This is the hardest lesson of the MCAS case: the late forum may be excellent and remain late.

After the disasters, the reports saw. They named. They corrected. The worldwide grounding of the MAX, the software changes, the use of two sensors, the training updates, the revisions to certification: all of this matters. There is no honor in scorning repair. But a posthumous repair does not falsify the thesis of the corridor; it confirms it at its coldest point. The system produced knowledge when the price had already been paid by 346 people.

The corridor is not the absence of verification. It is often verification after irreversibility.

That is why the Boeing case has to open Part V. Not because it is the newest case, or the most elegant. By now it is almost too familiar, and therefore risks becoming a blunted icon. But that is precisely why it has to be restored to its hard form: not a bug, not a chain of bad apples, not generic “complexity.” An authorized seam that let continuity pass where there was difference, simplicity where there was load, documentation where a forum was needed, human response where real time for understanding was required.

The corridor asked the pilot to be the system’s final moral sensor.

Then it removed the scene in which that sensor could function.

This is not automation against humanity. It is worse, and therefore more real: automation that preserves the human as the final signature on a choice that other layers have already made nearly impossible to contest. The pilot remains in the loop enough to bear responsibility, not enough to reopen the model. It is the same trick seen elsewhere: the subject present as a terminal of attribution, not as a witness capable of wounding the circuit.

A less indecent corridor would have had to do one simple and difficult thing: slow down where the market wanted continuity, expose where documentation wanted compression, integrate where procedure wanted separation, listen to the disturbance before it became wreckage.

It did not.

And when an aircraft falls, theory too has to stop speaking on tiptoe. The authorized corridor kills when it manages to turn the whole seam into a series of locally acceptable passages. No passage, taken alone, carries all the weight. Together they bring the aircraft down.

The post-mortem can reconstruct the sequence. A live forum had to interrupt it.

[^boeing-ntsb]: National Transportation Safety Board, *Safety Recommendation Report ASR-19-01*, 2019, on the gap between safety-assessment assumptions and actual crew response when faced with multiple alerts.

[^boeing-jatr-house]: Joint Authorities Technical Review, *Boeing 737 MAX Flight Control System: Observations, Findings, and Recommendations*, 2019; U.S. House Committee on Transportation and Infrastructure, *The Design, Development & Certification of the Boeing 737 MAX*, 2020.

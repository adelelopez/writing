- faerie
	- Intro
		- Once upon a time, there was a species that became conscious.
		    
		  I'll call them Faeries, so that you'll remember that this story is not based on facts about neuroscience or evolution, but is complete speculation. Whether human consciousness works in a similar way is yet to be seen, but I thought it would be interesting to have any explanation at all for the main facts of consciousness.  
		-
		- My approach is to think through what evolutionary pressures would shape minds into the sort of thing that started saying things like "Wow, this red is just so red!". Evolution can't just make new mind-parts out of nothing! Each new aspect has to have a clear precedent, along with the pressure to shape it in the required way. This is very constraining, which makes it very helpful for thinking about this clearly.
		-
		- When I refer to things that the faerie's mind is doing, these should not be assumed to be at all in her conscious awareness (which would presuppose the very thing I'm trying to explain). I'll try to use the word *process* instead of *thinks* for this to help make this point clear.
	- Evolution
		- Ideas:
			- Modeling
				- Good Controller Theorem -> needs to be models, something which tracks the state of the environment in which actions are performed
				- This fractalizes: you can slice the control loop at various places and you still need models, this is why it's compositional. I.e. if there's a gap where certain representations exist, and an action still needs to be computed, the controller needs to learn to model the environment out of these representations.
				- This flow of information from sensory processing, resulting in a model, and then used to compute actions, is the natural way for information to flow, since otherwise you start needing to remodel things.
				- Models are things which can answer a particular class of question
				- Even very early on (transcription factors), it's useful to have a syntax-semantics distinction, with symbols standing in for entire models
				- Earlier in evolutionary history, models are genetically hardwired. Later, they're still genetically specialized for specific tasks, though are much more able to adapt within the context of an organism's life. New models at the hardware level arise from duplication of specialized hardware. This is called **analogizing**.
				- Computation can be done much more efficiently on the symbols than on the entire representations, as long as you have a way to get the representation you need once the symbolic computation has been done (evaluation)
				- Since computation is part of what needs to be controlled, it itself fractalizes, you learn representations of intermediate symbolic computations (dereferencing)
				- Conceptualization is the capacity to *notice* that there's a missing mental model, along with the ability to start a new model to fill in. importantly, this does not imply *conscious* noticing, it's just an operation a mind can do at a certain level of modeling skill
				- Reduction is another mental operation, the one invoked when a mind seeks an explanation. It involves paying attention to the inputs into a hierarchical model.
				- None of this is yet conscious *thinking*, that would presuppose what is to be explained.
			- Imagination
				- Models need to be connected directly to the volitional apparatus
				- However, it's very useful to also be able to ask about hypothetical questions, for planning and other things
				- An evolved creature in a dangerous situation cannot afford to have a gap of significant length, during which models are unavailable for action. However, they also need to be able to assess various possible actions to plan the best approach in such situations. Hence, the need for the GRS
				- Also needs to be robust to continuous learning... being able to think yourself into thinking something is real is a pretty serious footgun. That's why the GRS itself is not part of a model, but an external signal.
				- You can deal with state by simply swapping it in sync with the GRS, so that the models are always running on the appropriate state.
				- By evolutionary necessity, the REAL phase of the GRS will be much more salient
			- Conspecific Model
				- There's a model specialized for modeling conspecifics, in the faerie ancestors which first began to live as social creatures.
				- The conspecific model is specialized at the hardware level, and co-opts signals from various representations which are implicitly used in self-modeling (at a very basic and mechanical level, like a perception model used to imagine a specific perspective)
				- Simply due to heavy use of co-option of models important for both perception and volition, its use has a more an effect which is more similar to how models are used during the REAL phase. This naturally amplifies the muted affect during the IMAGINED phase, resulting in a more noticeable response (which is useful during selection). This is Empathy.
				- Using volitional models would normally break the model hierarchy. To get around this, the fact that volitional outputs cause subtle sensations (changes in muscular tension or blood-flow) is exploited, and the sensory processing of these is treated as another sensory input into the conspecific model. These are called **emotions**.
				- It provides new kinds of symbols and judgements:
					- conspecific symbols, which it can use to produce predictions about that conspecific
					- "verbs", symbols which are about various things that conspecifics can be doing or experiencing
					- judgments about whether conspecifics are doing well, what sort of states they may be in, what lies within their domain of control (e.g. territory), and whether they are awake/aware at all
				- For faeries with language, (verbal) thinking begins as a way for the conspecific model to conceptualize more complex behaviors of conspecifics.
			- Reflecton
				- A faerie may be able to conceptualize a conspecific symbol SELF
				- Using SELF with the conspecific model (and presently available sensory/volitional symbols) is allowed to run during the REAL phase of the GRS. This leads to a striking sense that there is both a SELF conspecific having this specific experience AND that this is real and present and vivid. Faeries call such symbols **qualia**.
				- As part of the conspecific model, there's a notion of a conspecific having a specific experience. As applied to SELF, that notion of experience can itself be metaphysically given the judgement 'here' (or REAL) as a 1st-person logical judgement. The Hard Problem is resolved by noting that the entire notion of what it means to be having an experience is tied up to this notion of the conspecific model, and that whether or not it is *real* depends on whether it occurs during the REAL phase, and qualia are exactly the intersection of these two conditions.
				- Reduction inherently occurs during the IMAGINED phase. Attempts to reduce SELF (or anything for that matter) will therefore always be missing qualia, and hence, qualia will feel particularly mysterious and ineffable. Relatedly, reduction in general will feel like it "loses magic" or takes away from the experience.
				- The natural reduction machinery also tries to reduce SELF in a straightforward way. It's not sophisticated enough to use mathematical tricks used in things like quining, it only knows how to try to do the infinite regress thing (since there's no evolutionary pressure for it to get better at this). This, of course, is not possible, leading to a blindspot around the fixed-point.
				- reduction on the conspecific model is inherently blind to the volitional aspects, which have
				  to get filtered through emotions processed as sensory things. as a result, explanations are  
				  incomplete, especially where it comes to more volitional aspects of conspecifics. that's  
				  why the part of observation that feels mysterious isn't that the sensory stuff can happen,  
				  it's that there's something that can be an observor.  
				- additionally, reduction cannot happen during the REAL phase, and hence does not form qualia.
				  conscious objects about reduction only happen after, as SELF begins to make judgements  
				  about what SELF is thinking.  
				-
				-
		- draft
			- 1
				- Evolution
					- To begin, I'll first cover various developments in the evolution of the faerie ancestors, various pieces which evolved which ended up resulting in the phenomenon known as faerie consciousness. It's important to remember none of these pieces alone should be considered to be conscious or phenomenal or anything like that, which would presuppose that which is to be explained.
					- Modeling
						- The faerie ancestors had to model their environment. This is a mathematical mandate of the Good Regulator Theorem, inasmuch as a mind is trying to control its body and environment, it must have something which tracks the state of those.
						- And these models tend to be compositional. My intuition for this, which I think could be formalized, builds on the intuition from the Good Regulator Theorem — we can slice the feedback loop between the controller and the environment at various points. In particular, if there's a gap where certain representations exist and an action still needs to be computed, then the theorem applies to this gap and the controller needs to learn to model the environment out of these representations.
						- Similarly, you can slice things at the gap where the computations themselves are happening. Once these details begin to lie under the controller's purview, they themselves require modeling.
						- Even starting with the single-celled ancestors, there were transcription networks which served these sorts of functions. One transcription factor might come to represent the presence of high temperature, another factor might represent a decision to move in the ventral direction.
						- Faerie neurons evolved in order to efficiently transfer this sort of information across cells once they became multi-cellular. But the new medium proved to be much more versatile, and it was increasingly important to process information effectively as the relevant part of the world started looking bigger and faster. Faerie brains pass symbols much like the transcription factors of old, summaries of models and decisions.
						- What exactly are these models? I'll think of a **model** simply as something which can answer a certain class of questions about something. It doesn't have to be perfect of course, just some non-trivial relation to reality. Evolutionary selection pressure is brutal enough to optimize these pretty well.
						- And models come with various symbols that are associated with them. These symbols can be thought of as part of the interface for the model, the things you use to ask questions, and the way it provides answers. It's up to the upstream and downstream models to learn how to use these effectively.
						- A big advantage of faerie ancestor's brains is that they were able to have models adapt and learn over the lifetime of the individual. From an evolutionary perspective, this is almost unimaginably fast! But they were, initially, still very specialized towards certain domains. Creating an entirely new model from scratch is almost completely unviable. Instead, you would need to get lucky with duplicate hardware, one copy of which would then have the bandwidth to adapt to modeling a broader set of things. I'll call models which share this sort of relationship **analogous**, though as genetic adaptations pile on, they can become increasingly distinct.
						-
						-
						-
					- Computation
						-
						-
						-
			- 2
				- ## Modeling
					- The faerie ancestors had to model their environment. This is a mathematical mandate of the Good Regulator Theorem.
					- These models tend to be compositional. My intuition for this, which I think could be formalized, builds on the intuition from the Good Regulator Theorem — we can slice the feedback loop between the controller and the environment at various points. In particular, if there's a gap where certain representations exist and an action still needs to be computed, then the theorem applies to this gap and the controller needs to learn to model the environment out of these representations.
					- Similarly, you can slice things at the gap where the computations themselves are happening. Once these details begin to lie under the controller's purview, they themselves require modeling.
					- Even starting with the single-celled ancestors, there were transcription networks which served this function. Many transcription factors in these can be thought of as symbols, indicating some sort of information. One factor might come to represent the presence of high temperature, another factor might represent a decision to move in the ventral direction.
					- Faerie neurons evolved in order to efficiently transfer this sort of information across cells once they became multi-cellular. But the new medium proved to be much more versatile, and it was increasingly important to process information effectively as the relevant part of the world started looking bigger and faster. Faerie brains pass symbols much like the transcription factors of old, summaries of models and decisions. But they can be much richer, and can carry contextual information with them.
				- ## Imagination
					-
					- Now as the Faerie ancestors lived, mated, and thrived, they evolved sensory organs to perceive the world around them, and minds to skillfully integrate and act on this information.
					    
					  These minds were shaped to create internal representations – first of their raw perceptions, and then of the things they loved and feared.  
					- As they became more adept, they became capable of updating their representations, and even creating new representations within their own lifetimes.
					- But representations have uses beyond mere representation. In fact, it's incredibly useful to see what it would predict given false information. Used like this, it no longer is a representation, but a **model**.
					- I'll think of a **model** here simply as something which can answer a certain class of questions about something. It doesn't have to be perfect, just some non-trivial relation to reality. Evolutionary selection pressure was brutal enough to optimize these.
					-
					- These imagined outputs of models need to be distinguished from genuine representations, even though it's also important that you use same model for used for both representation and imagination. Models can't process both at the same time, and it would be dangerous to have sensory models busy doing other things for a significant length of time.
					- Ancient faerie ancestors therefore evolved to rapidly alternate between processing real data and imagined data. This is governed by a general signal: the Global Reality Signal (GRS). During the "real" phase of the GRS, models are connected to the present sensory data and present volitional drives. The models do their thing, letting the individual understand its present circumstances, and act accordingly. A fraction of a second later, the "imagined" phase of the GRS turns on, and models are fed whatever imagined data the mind is interested in. At each point, the status of the GRS is carefully tracked, with relevant state automatically being swapped in sync. This gives the mind an unambiguous reality signifier that can't (easily) be fooled by thinking imagined sensory data is real (as would be the case if "real" was treated as another model subject to mental manipulations).
					- When talking about symbols from models, the value of the GRS which inherently accompanies each symbol is a meta-judgement on it. I'll denote it in parentheticals, like `sight of red (REAL)`.
					- One key thing about the REAL phase is that the brain is really strict about what counts. During the REAL phase, each model is being fully utilized with REAL sensory data and REAL volitional control. So even something a faerie would be quite confident of, e.g. that the tree she's standing in the shade of is still right behind her, is not going to be active during the REAL phase. That doesn't mean that every representation marked REAL is actually *real*, faeries love to amuse themselves with false images which get marked as REAL, however their minds are sophisticated enough that the symbols that end up getting tagged as REAL are things like `sight of false bird (REAL)`.
					- [system 1/2?]
					- By evolutionary necessity, real outcomes must cause a much stronger response than their equivalent imagined outcomes: much more salient and important. Under normal operating circumstances, there's also never any ambiguity or uncertainty to any part of the mind about whether something is real, or simply a figment of the imagination.
				- ## Symbolic reasoning, and some terminology
					- Models come with various symbols that are associated with them. These symbols can be thought of as part of the interface for the model, the things you use to ask questions, and the way it provides answers. It's up to the upstream and downstream models to learn how to use these effectively.
					- These symbols here lie on the syntactic side of a syntax-semantics distinction, where richer symbols can be combined and manipulated in more diverse ways, corresponding to richer semantic meanings. However, these richer meanings are expensive to compute, especially in their fullness.
					- So faerie brains evolved to be able to do many more operations purely via syntactic operations (especially once some lossiness is accepted), and only convert these into the full semantic model at the end of these operations.
					- When a symbol is **dereferenced**, what happens is that the model that the symbol represents gets invoked. With an important exception, this happens quickly -- in a fraction of the GRS frequency. The models themselves are stateless -- they may improve over time, but that's better thought of as a change to the model than as an internal state its tracking. Whatever part *is* stateful is swapped in sync with the GRS, which allows the mind to continue an imagined chain of thought even as the GRS cycles.
					- The faerie ancestors evolved the capacity for abstraction. I've given different types of abstraction special names.
					- **analogizing** - using an existing model as a starting point for a new model (more efficient than starting from scratch).
					- **generalizing** - creating a new model to be a more efficient model (though typically less precise) of several other models.
					- **conceptualizing** - where a "missing model" can be noticed and fleshed out within the network of existing models.
					- **reducing** - a process which attempts to replicate a given model using a network of simpler and "smaller" models (i.e. do not reference any models which reference the original model - no circular dependencies).
				- ## The Conspecific Model
					- At some point, the faerie ancestors began to live as social creatures. It was increasingly important to model their conspecifics, not just as occasional mates or rivals, but as detailed fixtures of their lives. As a result, they developed specialized modeling for conspecifics. Like all models, this model makes extensive use of existing models which are useful: and in this case, an especially wide range of perceptual and volitional models are useful. Since these models are useful in the context of non-present perceptions and intentions, the conspecific model does its work during the IMAGINED phase of the GRS.
					- The conspecific model provides new kinds of symbols and judgements to the rest of the mind. First of all, there are now symbols for specific conspecifics. And to complement these, there are now a wide range of "verbs", symbols which are *about* the various things conspecifics can be doing or experiencing. Just as important are the symbols which represent the judgements of the conspecific model, whether so-and-so is doing well or not, what sorts of states they are likely to be in, what lies within their domain of control, and whether they are currently awake or aware at all.
					- To elaborate on how these new symbols work, let's consider "Sees", the conspecific symbol for relating a conspecific to a visual sensation. Pre-existing modeling already has symbols for representing e.g. "the sight of grass", and other sorts of visual sensations, and these can now be with the new symbols like "Sees" to query the conspecific model about things like "Does B See 'the sight of grass'"? But remember that none of this is consciously verbalized or anything like that -- this is just my abstract way of being able to loosely describe the new sorts of machinations that are now possible.
					- Due to the effect where even IMAGINED outputs cause a small but non-zero response in the faerie, the conspecific model results in an effect I'll call 'empathy'. Let's walk through how this works.
						- Our faerie sees her friend stub her toe.
						- The unconscious processes in her mind recognize this as a situation where the conspecific model would be useful.
						- During the imaginative phase of the GRS, her conspecific model utilizes models of our faerie's own leg and foot as being in a particular relation with the rock, models a certain lack of anticipation, and then the subsequent prediction of pain and the reflexive kick back.
						- Since this is happening during the imaginative phase, this only results in a muted version of the response, a ghost of pain and a catching of breath.
						- But it ended up being evolutionarily expedient to slightly amplify this response in the case of the conspecific model, since this helps signal care and attention to the other faeries, and gives her a concrete stake in their well-being. So our faerie now makes a visible wince and whispers "oof". This wince is involuntary and reflexive.
					- ### Emotions
						- One of the major outputs of the conspecific model are *emotions*. These are symbols analogized from the faerie's own interoception.
						- This will make more sense with an example, so here's one depicting a faerie learning the concept of anger:
							- The faerie sees her friend discover that her food was stolen.
							- The unconscious processes in her mind recognize this as a situation where the conspecific model would be useful.
							- Her mind predicts the sensory state of her friend, and what volitional drives she has, and that she expected to see food.
							- During the imaginative phase of the GRS, the predicted senses and volitions are imagined, and cascade through the rest of her mind.
							- As a result, the faerie has a muted version of the response: her face and head feeling hot, her pulse and breathing increasing, and her eyes/attention focusing sharply.
							- These predicted sensations are then wrapped up into an empathy symbol, which represents something like "she FELT her chest pound and her face turn red".
							- After several observations of similar situations, the pattern matching of her brain decides to create a new model which analogizes that particular combination of senses, and attaches it to predictions of what her friend will do. This model gets assigned a new symbol: ANGER.
							- This allows our faerie's mind to process things like "She is ANGRY because her food is gone, and she is likely to start a fight soon."
						- This is different from concepts already learned via ordinary pattern matching, such as the likely already existing concept of DangerousAnimal, and which of course becomes associated with the new Anger symbol. Without empathetic reasoning, its difficult to predict that an ordinary situation where a faerie is merely observed to be in a place she frequents and with ordinary circumstances (food is often scarce) would have a dramatic outburst.
						- In general, the emotional symbols were analogized from body-motor symbols, which is why most emotions are associated with specific body parts and states. This is also why faeries use the same word "feel" for both bodily sensations and emotions.
					- ### Thoughts
						- Faeries found that they quite enjoyed playing complicated social games with each other, awarding such skill with reproductive success. This lead to an evolutionary arms race to develop the empathetic models as much as possible!
						    
						  Further development of empathy introduces symbols for "X Imagines {sensory symbol}", "X thinks {narrative symbol}", "X remembers {episodic symbol}", "X really sees {sensory symbol}".  
						    
						  Let's re-examine the same scenario as above, and see how the new symbols are formed:  
						- The faerie sees her friend discover that her food was stolen.
						- Her mind generates the symbol "X is Angry" (real) as before.
						- The unconscious processes in her mind recognize this as a situation where empathy would be useful.
						- During the imaginative phase of the GRS, the predicted senses and volitions of our faerie being angry are imagined, and cascade through the rest of her mind.
						- As a result, she subvocalizes things like "gotta find out who did it and get it back!". These subvocalizations are then reinterpreted as sensations. (Or it may be that speech generation has a direct connection with auditory senses, in which case subvocalization is unnecessary.)
						- These predicted sensations are then wrapped up into an empathy symbol, which represents something like "She is ANGRY and now Wants to get back at whoever stole it".
						- Steps 3-7 are iterated, generating a chain of empathetic symbols, eventually resulting in predicted speech (or predicted imagined sensory data).
						- After several observations of similar situations, the pattern matching of her brain decides to create a new model which combines that particular combination of senses, and attaches it to predictions of what her friend will say. This model gets assigned a new symbol: THINKS.
						- This allows our faerie's mind to think things like "She is Thinking about who did it"
						- After more observations of such situations, her conceptualization ability recognizes that there is are Thoughts which don't get said, but nevertheless have strong Foresight.
						- After even more observation, she will recognize that these "unsaid thoughts" are the norm.
						    
						  Notice how indirect and drawn-out this process is! It's no wonder faerie children only develop theory-of-mind about a year or two after first learning to talk! (Note though that speech is only necessary for the development verbal thoughts, and that predicted-imagined-sensory-data in a specific sensory modality may be the primary mode of thought for some faeries, i.e. "visual thinkers").  
		- Reflection
			- The missing faerie
				- Sometime after faeries had long lived as social creatures, they developed strong conceptualization abilities, which allowed them to notice that there was a "missing faerie". Another faerie which seemed involved with all the friends and the lovers. Someone dear to her parents and children. The faerie whose face could be seen in a still pond.
				- Let's examine what such a realization may have looked like.
					- The faerie sees her reflection in the pond.
					- The unconscious processes in her mind recognize this as a situation where the conspecific model would be useful.
					- Her mind predicts the sensory state of the reflected faerie (recognizing that it is a reflection).
					- During the imaginative phase of the GRS, the predicted senses and volitions are imagined, and cascade through the rest of her mind.
					- As a result, she has a muted form of the response. Perhaps pupils dilating, her breathing quieting, and her jaw relaxing.
					- This cluster of sensations is already recognized as an emotion, that of wonder.
					- These predicted sensations are then wrapped up into a conspecific symbol, which represents something like "<reflected faerie> feels wonder".
					- After several observations of similar situations, the pattern matching of her brain decides to create a new model which gives the reflected faerie its own symbol: SELF.
					- In this situation, this manifests as the symbol "SELF feels wonder".
					- But this symbol is special... it finally allows for the conspecific model to have meaningful outputs during the real phase of the GRS!
					- With this symbol now available, the conspecific model has a meaningful output during each real phase. Specifically, that of `SELF sees blue (REAL)`, `SELF sees faerie (REAL)`, `SELF feels wonder (REAL)`, `SELF feels wind (REAL)`, etc...
				-
				- The GRS is strict about what sorts of modeling it allows during the REAL phase, because it
				  has to be, because that's its purpose. All processing during the REAL phase passes  
				  uninhibited to the faerie's muscles, causing her to act. So a perceptual model can only be  
				  about one thing, the current perception. Volitional models can only be about one thing, the  
				  current action. All planning has to have been done during the IMAGINED phase, now is the  
				  time to act. The conspecific model uses perceptual models as part of its representation.  
				  Since, during its normal use, these are about others' perceptions, they cannot be allowed to take place during the REAL phase, even if the other faerie is present and is making their internal  
				  state as obvious as possible. But without a SELF symbol to use with the model, the rest of  
				  the mind doesn't have a way to interface with the conspecific model at all, it needs that  
				  piece too. That's why the discovery of SELF is such a special moment in a faerie's life  
				  (though of course, she can't be consciously aware of anything before the moment).  
			- # Qualia and The Hard Problem
				- As part of the conspecific model, there's a generalized sense of conspecifics experiencing
				  various things. When the conspecific model runs for SELF during the REAL phase, a wide  
				  range of judgements about the experience of SELF are happening, all of them tagged REAL.  
				  These are what the faeries call **qualia**: the striking sense that there is both a SELF  
				  conspecific having this specific experience AND that this is real and present and vivid.  
				- David Chalmers described the Hard Problem of consciousness as:
				  > ...even when we have explained the performance of all the cognitive and behavioral  
				  functions in the vicinity of experience—perceptual discrimination, categorization, internal  
				  access, verbal report—there may still remain a further unanswered question: Why is the  
				  performance of these functions accompanied by experience?  
				- The faerie's answer is simply that, there's this notion of someone experiencing something,
				  as a basic part of the conspecific model, and that once the SELF symbol is available,  
				  normal sensations are now accompanied by the conspecific model's judgements that SELF is  
				  experiencing all the things the faerie is experiencing, and that this is REAL.  
				- Is that really all there is to it? I think there's actually another and subtler thing going
				  on too. I've written before about 0th person and 1st person logic -- in short, the idea is  
				  that logical truth values can be given two interpretation. One is the standard 0th person  
				  interpretation of them as TRUE and FALSE. The other is to interpret them as relative to a  
				  specific reasoner, as HERE and NOT-HERE. As a basic example of a 1st person logical thing,  
				  consider a simple robot with a photodetector. When the photodetector is lit, the robot can  
				  validly judge `sensor is on` as HERE, and not otherwise. This is distinct from a 0th person  
				  judgement, which has to first specify which sensor it refers to, and this is surprisingly  
				  fraught as examples with identical robots in different parts of the world can illustrate.  
				- What's surprisingly radical about this notion is that any statements about objective
				  reality are 0th person statements. The 1st person logical things are a separate realm,  
				  related, I believe, by an adjoint functor pair (though the details need to be worked out  
				  still). 1st person logic can be applied to arbitrary specific entities, and is about what  
				  those entities experience in the very basic sense that a robot or thermostat experiences, which makes me what Chalmers would call a panprotopsychist What faerie Mary learns as she enters the red room — her 0th person model of the world complete — is a 1st person proposition.  
				- However, while qualia *are* 1st person logical propositions, they're ones of a specific
				  form. One in which there is a conspecific model providing a judgement of a conspecific  
				  having an experience in the intuitive and evolved sense of that word, and that that  
				  judgement is also being marked REAL, which corresponds to a 1st person logical judgement of  
				  HERE. The simple robot does *not* have these. But an entity which models conspecifics and has judgements about what sorts of experiences they are having does have qualia, if there is a sense in which it judges SELF experiences as REAL (though this may not necessarily be associated with the vividness that faerie qualia are associated with).  
				-
			- Three mistakes
				- For a conspecific symbol like "X observes Y", the mind will judge it based on what it knows about X and Y. A query like "Who observes Y" looks for a possible X such that that "X observes Y" is true.
				    
				  "What observes Y" works the same way, since "observes" is itself a conspecific symbol.  
				    
				  If this gets asked about one's own experiences, it is easily answered by "SELF observes Y". But now consider a mind that is trying to understand how it could be composed of parts, i.e. seeking an explanation.  
				    
				  When this question gets asked, it will look for a part of itself that it can imagine the perspective of, call it PART. This will likely have some but not all of the sensory experiences and volitional drives that self has. So it may judge "PART observes Y" for an appropriate PART.  
				    
				  This gets reduced into imagining having PART's experiences (which basically amounts to imagining *not* having all the experiences that *don't* input into PART). This is pretty unsatisfying as an explanation of how a mind is able to observe! But this is the only kind of subpart the faerie's conspecific model can imagine the perspective of! The reduction facilities never were under evolutionary pressure to handle these sorts of cases.  
				    
				  So a faerie will typically come to one of a few conclusions:  
				- That there is a subpart PART which internally watches things play out (cartesian stage, inner homunculus)
				- That some core part of the mind cannot be broken into subparts (eternal soul, Leibniz monad, often compatible with 1).
				- That there is no such thing as "observing" or the "observer" (illusionism, anattā)
				    
				  These all have something to them, but none are quite right as an explanation.  
				    
				  For 1, there certainly are such subparts, but they all contain the whole observation-loop which is the thing to be explained.  
				    
				  For 2, this part of the mind indeed cannot be reduced using its standard reduction process. But it's only because `observes` is a conspecific symbol, which assumes that the answer must be of the form of something which can be empathized with. In other words, it's a bug in the reduction process rather than it being an inherently irreducible part.  
				    
				  For 3, there is a way in which there is no observer: there is no X for which `X observes Y` is explainable by the faerie's native reduction facilities. But again, it's due to the bug in the reduction process rather than there not being an actual observer (after all, SELF is still legitimately an observer, and this symbol can indirectly can be explained (at least for faeries) as I'm doing here right now).  
				    
				  Similar problems occur when trying to examine how things like "feeling" or "wanting" work, since these concepts are also tied to the conspecific model.  
		

- faerie consciousness
	- A
		- Once upon a time, there was a species that became conscious.
		    
		  I'll call them Faeries, so that you'll remember that this story is not based on facts about neuroscience or evolution, but is complete speculation. Whether human consciousness works in a similar way is yet to be seen, but I thought it would be interesting to have any explanation at all for the main facts of consciousness.  
		-
		- My approach is to think through what evolutionary pressures would shape minds into the sort of thing that started saying things like "Wow, this red is just so red!". Evolution can't just make new mind-parts out of nothing! Each new aspect has to have a clear precedent, along with the pressure to shape it in the required way. This is very constraining, which makes it very helpful for thinking about this clearly.
		-
		- When I refer to things that the faerie's mind is doing, these should not be assumed to be at all in her conscious awareness (which would presuppose the very thing I'm trying to explain). I'll try to use the word *process* instead of *thinks* for this to help make this point clear.
		-
		- # Evolution
		- ## Modeling
		- The faerie ancestors had to model their environment. This is a mathematical mandate of the Good Regulator Theorem.
		- These models tend to be compositional. My intuition for this, which I think could be formalized, builds on the intuition from the Good Regulator Theorem — we can slice the feedback loop between the controller and the environment at various points. In particular, if there's a gap where certain representations exist and an action still needs to be computed, then the theorem applies to this gap and the controller needs to learn to model the environment out of these representations.
		- Similarly, you can slice things at the gap where the computations themselves are happening. Once these details begin to lie under the controller's purview, they themselves require modeling.
		- Even starting with the single-celled ancestors, there were transcription networks which served this function. Many transcription factors in these can be thought of as symbols, indicating some sort of information. One factor might come to represent the presence of high temperature, another factor might represent a decision to move in the ventral direction.
		- Faerie neurons evolved in order to efficiently transfer this sort of information across cells once they became multi-cellular. But the new medium proved to be much more versatile, and it was increasingly important to process information effectively as the relevant part of the world started looking bigger and faster. Faerie brains pass symbols much like the transcription factors of old, summaries of models and decisions. But they can be much richer, and can carry contextual information with them.
		- ## Imagination
		-
		- Now as the Faerie ancestors lived, mated, and thrived, they evolved sensory organs to perceive the world around them, and minds to skillfully integrate and act on this information.
		    
		  These minds were shaped to create internal representations – first of their raw perceptions, and then of the things they loved and feared.  
		- As they became more adept, they became capable of updating their representations, and even creating new representations within their own lifetimes.
		- But representations have uses beyond mere representation. In fact, it's incredibly useful to see what it would predict given false information. Used like this, it no longer is a representation, but a **model**.
		- I'll think of a **model** here simply as something which can answer a certain class of questions about something. It doesn't have to be perfect, just some non-trivial relation to reality. Evolutionary selection pressure was brutal enough to optimize these.
		-
		- These imagined outputs of models need to be distinguished from genuine representations, even though it's also important that you use same model for used for both representation and imagination. Models can't process both at the same time, and it would be dangerous to have sensory models busy doing other things for a significant length of time.
		- Ancient faerie ancestors therefore evolved to rapidly alternate between processing real data and imagined data. This is governed by a general signal: the Global Reality Signal (GRS). During the "real" phase of the GRS, models are connected to the present sensory data and present volitional drives. The models do their thing, letting the individual understand its present circumstances, and act accordingly. About 25ms later, the "imagined" phase of the GRS turns on, and models are fed whatever imagined data the mind is interested in. At each point, the status of the GRS is carefully tracked, with relevant state automatically being swapped in sync. This gives the mind an unambiguous reality signifier that can't (easily) be fooled by thinking imagined sensory data is real (as would be the case if "real" was treated as another model subject to mental manipulations).
		- By evolutionary necessity, real outcomes must cause a much stronger response than their equivalent imagined outcomes: much more salient and important. Under normal operating circumstances, there's also never any ambiguity or uncertainty to any part of the mind about whether something is real, or simply a figment of the imagination.
		- ## Symbolic reasoning, and some terminology
		- Models come with various symbols that are associated with them. These symbols can be thought of as part of the interface for the model, the things you use to ask questions, and the way it provides answers. It's up to the upstream and downstream models to learn how to use these effectively.
		- These symbols here lie on the syntactic side of a syntax-semantics distinction, where richer symbols can be combined and manipulated in more diverse ways, corresponding to richer semantic meanings. However, these richer meanings are expensive to compute, especially in their fullness.
		- So faerie brains evolved to be able to do many more operations purely via syntactic operations (especially once some lossiness is accepted), and only convert these into the full semantic model at the end of these operations.
		- When a symbol is **dereferenced**, what happens is that the model that the symbol represents gets invoked. With an important exception, this happens quickly -- in a fraction of the GRS frequency. The models themselves are stateless -- they may improve over time, but that's better thought of as a change to the model than as an internal state its tracking. Whatever part *is* stateful is swapped in sync with the GRS, which allows the mind to continue an imagined chain of thought even as the GRS cycles.
		- The faerie ancestors evolved the capacity for abstraction. I've given different types of abstraction special names.
		- **analogizing** - using an existing model as a starting point for a new model (more efficient than starting from scratch).
		- **generalizing** - creating a new model to be a more efficient model (though typically less precise) of several other models.
		- **conceptualizing** - where a "missing model" can be noticed and fleshed out within the network of existing models.
		- **reducing** - a process which attempts to replicate a given model using a network of simpler and "smaller" models (i.e. do not reference any models which reference the original model - no circular dependencies).
		-
		-
		- # Empathy
		- Alright, let's get back to our faeries. At this point in their evolution, they had the ability to do symbolic reasoning, and abstract thought. So of *course* they represented their conspecifics. Their parents and children, their friends and their lovers. And as they thrived by this ability, evolution happened upon a strange trick which I'll call **empathy**.
		- Representing another being as complicated as yourself is tricky business. Everything of import that a mind is already doing now has to be represented in the same kind of mind. Not just once, but several times over!
		- The standard means of representation can adequately provide low-resolution representations of others. But for higher fidelity, these methods no longer can keep up.
		- What's much easier is to simply imagine *being* that faerie; imagine their experiences, and imagine having their goals. A mind which happened upon this trick would find its representations coming together to generate a response, a response with Foresight into the actual other faerie's actions.
		- So the minds evolved to be good at doing this trick, to the extent that it became one of the most comfortable ways of thinking about something, even if that thing wasn't very much like a faerie mind. To the extent that it was automatically invoked in the presence of loved ones.
		- This notion of empathy does not require nor imply love or sympathy; sadism is also built from this empathetic structure. It also is not the thing you do when you're *consciously* trying to empathize with somebody. Instead, it's more like the thing that makes you wince when you see someone stub their toe.
		- ## What is an empathetic mind like?
		- As a part of this ability, a mind has to keep track of which imagined/inferred sensations went with each mind. It also needs to be able to reason with the empathetic observations made.
		- Therefore, these observations are attached to symbols which look roughly like "X Sees {sensory symbol}", "X Has {volitional symbol}", where X is a conspecific symbol (or a generalization of such).
		- I'll refer to symbols which inherently require the use of empathy somewhere in their dependencies as *empathetic*.
		- The sensory and volitional symbols are older symbols which point to parts of sensory or volitional models.
		- However, the symbol "Sees" is a new empathetic symbol which refers to the empathetic model when the sensory symbol is imagined by a sensory model.
		- (There are of course additional symbols like "hears", "feels (touch sense)", "smells", "tastes" which also are new here, tracking which sensory modality the sensory symbol was imagined in while running the empathetic model.)
		- The volitional symbols are things like "Hunger", "Thirst", "Lust", "Care for X", and "Loneliness", which also are already existing concepts in pre-empathetic minds.
		- However, the symbol "has (urge to)" is a new empathetic symbol which refers to the output of the empathetic model when the volitional symbol is imagined by a volitional model.
		- Let's walk through a brief example:
			- The faerie sees her friend stub her toe.
			- The unconscious processes in her mind recognize this as a situation where empathy would be useful.
			- During the imaginative phase of the GRS, her mind imagines that it is in the same situation as her friend.
			- Her sensory models predict specific sensations resulting from this: a brief but intense pain localized at the toe.
			- Her volitional models predict a specific response from this, a reflexive step back followed by a vocal "OW!". This is all happening using the same models the faerie uses for herself, the only difference being that it is in the imaginative phase of the GRS. Thus, she only goes through a muted version of the response herself: a wince along with a whispered "oof".
		- This response is observed via sensory channels and are then wrapped up into an empathy symbol, which represents something like "She stubbed her toe, and now it hurts quite a bit".
		- If this sight of this event is still present, it also allows the generated symbol to be used during the reality phase of the GRS. "She stubbed her toe, and now it hurts quite a bit (real)".
		    
		  Remember that none of this is necessarily happening consciously for the faerie.  
		    
		  When an empathetic symbol needs to be dereferenced, there is not a small model which her symbolic reasoner can simply load like it usually does. Instead, an entire imaginative phase must be  
		- ## Emotions
		    
		  For minds with strong conceptualization abilities, there is a new class of symbols which look like "X Feels {emotional symbol}". The emotional symbols are also new, and refer to learned concepts that are extremely useful in modeling others. Specifically, *emotional* symbols are symbols which are analogized from sensory symbols modeling various parts of the body.  
		-
		- Here's an example depicting a faerie learning the concept of anger:
		- The faerie sees her friend discover that her food was stolen.
		- The unconscious processes in her mind recognize this as a situation where empathy would be useful.
		- Her mind predicts the sensory state of her friend, and what volitional drives she has, and that she expected to see food.
		- During the imaginative phase of the GRS, the predicted senses and volitions are imagined, and cascade through the rest of her mind.
		- As a result, the faerie has a muted version of the response: her face and head feeling hot, her pulse and breathing increasing, and her eyes/attention focusing sharply.
		- These predicted sensations are then wrapped up into an empathy symbol, which represents something like "she FELT her chest pound and her face turn red".
		- After several observations of similar situations, the pattern matching of her brain decides to create a new model which analogizes that particular combination of senses, and attaches it to predictions of what her friend will do. This model gets assigned a new symbol: ANGER.
		- This allows our faerie's mind to process things like "She is ANGRY because her food is gone, and she is likely to start a fight soon."
		- If the sight of this event is still present, it also allows "She is ANGRY" to be used as an input during the reality phase of the GRS.
		    
		  This is different from concepts already learned via ordinary pattern matching, such as the likely already existing concept of DangerousAnimal, and which of course becomes associated with the new Anger symbol. Without empathetic reasoning, its difficult to predict that an ordinary situation where a faerie is merely observed to be in a place she frequents and with ordinary circumstances (food is often scarce) would have a dramatic outburst.  
		    
		  In general, the emotional symbols were analogized from body-motor symbols, which is why most emotions are associated with specific body parts and states. This is also why faeries use the same word "feel" for both bodily sensations and emotions.  
		- ## Thoughts
		- Faeries found that they quite enjoyed playing complicated social games with each other, awarding such skill with reproductive success. This lead to an evolutionary arms race to develop the empathetic models as much as possible!
		    
		  Further development of empathy introduces symbols for "X Imagines {sensory symbol}", "X thinks {narrative symbol}", "X remembers {episodic symbol}", "X really sees {sensory symbol}".  
		    
		  Let's re-examine the same scenario as above, and see how the new symbols are formed:  
		- The faerie sees her friend discover that her food was stolen.
		- Her mind generates the symbol "X is Angry" (real) as before.
		- The unconscious processes in her mind recognize this as a situation where empathy would be useful.
		- During the imaginative phase of the GRS, the predicted senses and volitions of our faerie being angry are imagined, and cascade through the rest of her mind.
		- As a result, she subvocalizes things like "gotta find out who did it and get it back!". These subvocalizations are then reinterpreted as sensations. (Or it may be that speech generation has a direct connection with auditory senses, in which case subvocalization is unnecessary.)
		- These predicted sensations are then wrapped up into an empathy symbol, which represents something like "She is ANGRY and now Wants to get back at whoever stole it".
		- Steps 3-7 are iterated, generating a chain of empathetic symbols, eventually resulting in predicted speech (or predicted imagined sensory data).
		- After several observations of similar situations, the pattern matching of her brain decides to create a new model which combines that particular combination of senses, and attaches it to predictions of what her friend will say. This model gets assigned a new symbol: THINKS.
		- This allows our faerie's mind to think things like "She is Thinking about who did it"
		- After more observations of such situations, her conceptualization ability recognizes that there is are Thoughts which don't get said, but nevertheless have strong Foresight.
		- After even more observation, she will recognize that these "unsaid thoughts" are the norm.
		    
		  Notice how indirect and drawn-out this process is! It's no wonder faerie children only develop theory-of-mind about a year or two after first learning to talk! (Note though that speech is only necessary for the development verbal thoughts, and that predicted-imagined-sensory-data in a specific sensory modality may be the primary mode of thought for some faeries, i.e. "visual thinkers").  
		- # Reflection
		- ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ 
		  Empathetic minds with strong conceptualization abilities easily noticed a "missing person". Another faerie which seemed involved with all the friends and the lovers. Someone dear to her parents and children. The faerie whose face could be seen in a still pond.  
		-
		- Let's examine what such a realization may have looked like.
		- The faerie sees her reflection in the pond.
		- The unconscious processes in her mind recognize this as a situation where empathy would be useful.
		- Her mind predicts the sensory state of the reflected faerie (recognizing that it is a reflection).
		- During the imaginative phase of the GRS, the predicted senses and volitions are imagined, and cascade through the rest of her mind.
		- As a result, she has a muted form of the response. Perhaps pupils dilating, her breathing quieting, and her jaw relaxing.
		- This cluster of sensations is already recognized as an emotion, that of wonder.
		- These predicted sensations are then wrapped up into an empathy symbol, which represents something like "<reflected faerie> Feels wonder".
		- After several observations of similar situations, the pattern matching of her brain decides to create a new model which gives the reflected faerie its own symbol: SELF.
		- In this situation, this manifests as the symbol "SELF Feels wonder".
		- As the sight of this event is present, it allows this to be used as an input during the reality phase of the GRS: "SELF Feels wonder" (real)
		- After several observations of similar situations, the pattern matching of her brain decides to equivocate "SELF Feels wonder" (real) with "wonder" (real).
		    
		  Once her mind has generalized the above pattern sufficiently, she learns to automatically equivocate every "<observation>" (real) with "SELF Feels <observation>" (real). The automatic application of empathy ensures that the "SELF Feels <observation>" (real) is reliably generated, which ensures that the equivocation doesn't collapse simply into "<observation>" (real). This makes this observation *conscious*!  
		    
		  Note that this does not mean she has the *thought* "I see <observation>" whenever she sees <observation>. It simply feels like the bare *qualia* of <observation> (because that's what *qualia* means, at least for faeries).  
		- ## Are the lights on?
		    
		  But before we get deeper into qualia, we need to look at how the empathetic model accounts for the real and imagined judgements.  
		- After using empathy in several interactions with her friends, the faerie's mind recognizes the empathetic prediction is not always correct: it also matters that the faerie in question is awake and/or alert, and can actually experience the imagined sensations.
		- Her mind therefore creates a new symbol to track this: Really. I.e. "X Really sees red" Like any other symbols, this symbol will be judged (real) or (imagined) in a way which only depends on the current phase of the GRS.
		- This symbol comes with a sense agency associated with it. A deeply sleeping faerie doesn't Really hear your voice, even if you sing right in her ear. A video of a faerie doesn't Really see red, even if it is right in front of her and depicts her reacting accordingly.
		    
		  So the idea of an actual event as perceived by some being ends up being entwined with the idea that the being has agency and experiences; all wrapped up in this 'really' symbol. This has profound consequences on the nature of faerie consciousness, as we shall see.  
		- ## Qualia
		    
		  In general, the phenomena of symbols of the form "SELF <empathetic verb> <observation>" (real) being dereferenced is called *qualia*.  
		    
		  However, there are (in faeries) two levels of qualia, with the latter being richer and perhaps closer to what humans understand the term as.  
		- ### Basic Qualia
		- First, let's understand the empathetic case:
		- The mind decides to investigate "X Sees red" (real), which triggers a mental motion to dereference.
		- This involves setting certain initial values to match X, letting the mind do its thing, and then connecting this to the model for RED with the relevant model outputs.
		- After the dereference, this results in a mental state wherein the mind is generating the symbols "red is seen" (imagined) and "X Sees red" (real). (note that "seen" here is non-empathetic, and in particular distinct from "Sees").
		- As the empathetic model finishes running, the resulting output is something like "red is seen by X" (imagined).
		    
		  Now consider the analogous process in the reflective case:  
		- The mind decides to investigate "Self Seeing red" (real), which triggers a mental motion to dereference Seeing.
		- This involves setting certain initial values to match Self, letting the mind do its thing, and then connecting the response to the model for RED with the relevant model outputs.
		- After the dereference, this results in a mental state wherein the mind is generating the symbols "red is seen" (imagined) and "Self Sees red" (imagined).
		- However, the mind recognizes that it is already in this state, and so it can use its current state to create the required output. This means the output is finished during the real phase of the GRS.
		- So the resulting output is something like "red is seen by Self" (real)
		    
		  Because this symbol is marked real, it has a much more vivid and compelling effect on the mind than the empathetic case.  
		    
		  This symbol dereferences into its constituent models. In this case, that's the actual model of "self sees red", which is the self model with red sensory data. But red sensory data in the self model is always associated with the "self sees red" symbol, and so this symbol appears in the dereferenced symbol as well.  
		    
		  As a result, this gives a sense that qualia are sensory/volitional/emotional information along with an ineffable "something more" to it that resists all attempts at scrutiny.  
		- ### Rich Qualia
		- However, there's also a richer version of qualia which can happen, typically when attention is being focused on the nature of the qualia as an experience itself.
		    
		  First, let's understand the empathetic case:  
		- The mind decides to investigate "X Seeing red" (imagined), which triggers a mental motion to dereference Seeing.
		- This involves setting certain initial values to match X, letting the mind do its thing, and then connecting this to the model for RED with the relevant model outputs.
		- After the dereference, this results in a mental state wherein the mind is generating symbols like "red is seen" (imagined).
		- As the empathetic model finishes running, the resulting output is something like "red is REALLY being seen by X" (imagined). (The empathetic model has learned to convert symbols using present-tense empathetic verbs from imagined to real when quoting them.)
		- The faerie may then have further thoughts along the lines of "wow, so when X looks at something red, she *really* sees red!" and "there's a whole other being actually experiencing redness!"
		    
		  Now consider the analogous process in the reflective case:  
		- The mind decides to investigate "SELF Seeing red" (real), which triggers a mental motion to dereference Seeing.
		- This involves setting certain initial values to match SELF, letting the mind do its thing, and then connecting this to the model for RED with the relevant model outputs.
		- After the dereference, this results in a mental state wherein the mind is generating symbols like "red is seen" (real).
		- However, the mind recognizes that it is already in this state, and so it can use its current state to create the required output. This means the output is finished during the real phase of the GRS.
		- So the resulting output is something like "red is REALLY being seen by SELF" (real)
		- The faerie may then have further thoughts along the lines of "wow, when I look at something red, I *really* see red!" and "there's this whole being that is me that is actually experiencing redness!"
		    
		  For a specific experience, there is a corresponding sense of what it is like to be someone having that experience. Applied to self, this gives rise to a sense of what it is like to be yourself having that experience.  
		    
		  Which gets glossed as a sense of "it being like something" to have an experience.  
		    
		  Empathy developed as a modeling ability which would run during the imaginary phase of the global reality signal. But when (and only when) applied to the self model, does the empathy model run during the reality phase of the global reality signal. So there is a very strong sense that the sense of what it is like to be yourself is *real* and *present*, and its symbols are qualitatively different than the empathetic senses applied to others (or even yourself in imagined circumstances).  
		-
		- ## The Hard Problem
		- > ...even when we have explained the performance of all the cognitive and behavioral functions in the vicinity of experience—perceptual discrimination, categorization, internal access, verbal report—there may still remain a further unanswered question: Why is the performance of these functions accompanied by experience? –David Chalmers
		- Let's put our faerie in a bright red room. Her sensory models process the stimulus of red.
		- First, let's get the ontological status of this out of the way. We can treat the (REAL) tag as an ontological judgement of "Here" in a 1st person (i.e. subjective) logic. This is not a form of knowledge that can be directly considered as an ordinary 0th person logical statement. So we can interpret red (REAL) as meaning that the referent of red is present for her, i.e. that she experiences it. That's not anything particularly special; a simple robot with a photodiode detecting red can be considered to be having an experience in the same way. But it let's us explains the "Mary's Room" aspect: Mary learns a 1st-person statement when she sees red, which is not accessible via 0th-person reasoning.
		- But that's not all that happens! The conspecific model captures this symbol, and repackages it as Self sees red (REAL ACTUAL).
		- To understand the implications of this, let's first consider how our faerie might process her sister seeing red. She gets a symbol Sister sees red (IMAGINED ACTUAL). Like any IMAGINED symbol, it is faint in that its influence on actions or updates is severely muted.
		- Due to the ACTUAL tag, it is accompanied by a sense that someone is experiencing it. That's what the conspecific model is for, right? This might all ultimately result in sentences being generated like "oh yeah, she saw something red".
		- Now, how will her reaction differ for the Self sees red (REAL ACTUAL) symbol? Well for one, she will treat it as a real and vivid thing that she has Experienced (like anything REAL), giving it intrinsically more salience.
		- And again, due to the ACTUAL tag, it is accompanied by a sense that someone is experiencing it. That's why she conceptualizes it as an experience! This is not something that would have happened without the conspecific model. This might result in a sentence like "wow, I'm like... actually seeing red rn!" being generated instead.
		- ## Fixed-point blindness
		- In a faerie mind, it's quite bad to have a strong positive feedback loop, as this overstimulates neurons which can damage or even kill them, or wastes precious time and energy on useless cycles. So minds are evolved to have feedback suppressor mechanisms which shut these loops down before they get out of hand.
		- This effectively creates a blindspot at any attempt to dereference SELF. It can partially be dereferenced; the blindspot is just big enough to cover up the fixed-point.
		    
		  Remember that when an ordinary symbol is dereferenced, it "spins-up" the referenced model again, along with the surrounding context. When an empathetic symbol for another faerie is dereferenced, it sets up the initial conditions, and then lets your mind go through the resulting motions during the imaginary phase of the GRS, which  
		    
		  First, let's understand the empathetic case:  
		- The mind decides to reduce "X" (imagined), which triggers a mental motion to find a network of other symbols which can explain the predictions of X in a non-circular way.
		- This involves setting certain initial values to match X, and letting the mind do its thing. That's what the model *is*, and so poking at the model via perturbations or whatever has to go through all of this to compute its output.
		- The mind already has concepts like Body, Eyes, Mind which can be fit together to create a workable explanation. E.g. "The red light bounces into her eyes, gets interpreted by her retinas, and then processed by her mind, which ends up with her having the experience of red."
		- Even though the "experience of red" part may still seem undiscovered (i.e. the mind doesn't know how to reduce it into other concepts it has), it doesn't seem that mysterious yet since the mind can imagine something like a red light sensor connected to a box that says "I see red" that could potentially explain it.
		    
		  Now the reflective case:  
		- The mind decides to reduce "SELF" (real), which triggers a mental motion to find a network of other symbols which can explain the predictions of SELF in a non-circular way.
		- This involves setting certain initial values to match SELF, and letting the mind do its thing. That's what the model *is*, and so poking at the model via perturbations or whatever has to go through all of this to compute its output.
		- The mind already has concepts like Body, Eyes, Mind which can be fit together to create a potential explanation. E.g. "The red light bounces into my eyes, gets interpreted by my retinas, and then processed by my mind, which ends up with me having the experience of red."
		- However, the mind looks at "red is seen" (real) and compares it to the actual experience of red: "SELF Sees red" (real), and determines that this explanation only explains the former. So it still feels mysterious.
		- If the faerie nonetheless persists, she will run into a cycle in which the mind attempts to reduce SELF over and over again. (Remember that this 'reduce' algorithm isn't being consciously controlled: she won't have the conscious experience of trying to reduce it over and over. Instead, her conscious experience will be more like a single invocation to start the algorithm, perhaps with a strength of intention attached to it.)
		- The feedback suppressors recognize this cycling and kick in. Since this phenomena is fairly rare (normally, a circular dependency in a model is noticed before it gets reduced), and mainly pertinent to low-level mental processing, her empathetic model is unlikely to have developed symbols that would allow her to notice this as a possible mental event. Instead, it will merely feel like her mind went blank or that she lost her train of thought.
		- Repeated efforts to do this process will leave her with the impression that this problem is simply too hard for her, or that the phenomena is *intrinsically* mysterious.
		- And of course, the faerie can generalize this mysteriousness as applying equally well to other faeries she empathizes with.
		    
		  ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ  
		    
		  This causes some strange illusions.  
		    
		  First of all, the seemingly inescapable aura of mystery that appears inherent to consciousness.  
		    
		  Secondly, the faerie, observing the world, and herself a being within it, will not perceive the part of herself observing. She still can infer that some part of her is in fact observing. So without careful thought, she is likely to conclude that the part of her which observes is not of the world.  
		    
		  And similarly, she may have the strong impression that the part of her which does her thinking and feeling is separate from the world in a strange and mysterious way. This impression may persist even when she knows better. When she tries to look at the supposed boundary, the blind spot will be obscuring it, which makes it feel intrinsically mysterious and unknowable.  
		    
		  In order to circumvent this blindspot, a reflective mind is likely to have a separate self model, which I'll call **I**. When a faerie has a thought like "I see red", the "I" refers not to "SELF" but to this I model. The thought "I see red" is really symbolized as something more like "SELF THINKS 'I SEES RED'" (real).  
		    
		  Unlike the SELF symbol, the I symbol can be used within *conscious* thought directly (without needing empathy), and will therefore be the symbol representing how the faerie consciously thinks of herself.  
		- ## Who watches the watcher?
			- For an empathetic symbol like "X observes Y", the mind will judge it based on what it knows about X and Y.
			    
			  And it dereferences into something like "imagine having X's experiences, and then experiencing Y"  
			    
			  A query like "Who observes Y" looks for a possible X such that that "X observes Y" is true.  
			    
			  "What observes Y" works the same way, since "observes" is itself an empathetic symbol.  
			    
			  If this gets asked about one's own experiences, it is easily answered by "I observe Y", where I is the identity model.  
			    
			  But now consider a mind that is trying to understand how it could be composed of parts, i.e. seeking an explanation.  
			    
			  When this question gets asked on a subpart of the self (call it I_1), then it will look for a part of itself that it can imagine the perspective of. This will likely have some but not all of the sensory experiences and volitional drives that self has. So it may judge "I_1 observes Y" for an appropriate I_1.  
			    
			  This gets reduced into imagining having I_1's experiences (which basically amounts to imagining *not* having all the experiences that *don't* input into I_1). This is pretty unsatisfying as an explanation of how a mind is able to observe!  
			    
			  But this is the only kind of subpart the faerie's empathetic model can imagine the perspective of! The reduction facilities never were under evolutionary pressure to handle these sorts of cases.  
			    
			  So a faerie will typically come to one of a few conclusions:  
			- That there is a subpart I_1 which internally watches things play out (cartesian stage, inner homunculus)
			- That some core part of the mind cannot be broken into subparts (eternal soul, Leibniz monad, often compatible with 1).
			- That there is no such thing as "observing" or the "observer" (illusionism, anattā)
			    
			  These all have something to them, but none are quite right as an explanation.  
			    
			  For 1, there certainly are such subparts, but they all contain the whole observation-loop which is the thing to be explained.  
			    
			  For 2, this part of the mind indeed cannot be reduced using its standard reduction process. But it's only because observes is an empathetic symbol, which assumes that the answer must be of the form of something which can be empathized with. In other words, it's a bug in the reduction process rather than it being an inherently irreducible part.  
			    
			  For 3, there is a way in which there is no observer: there is no X for which X observes Y is explainable by the faerie's reduction facilities. But again, it's due to the bug in the reduction process rather than there not being an actual observer (after all, Self is still legitimately an observer, and this symbol can indirectly can be explained (at least for faeries) as I'm doing here right now).  
			    
			  Similar problems occur when trying to examine how things like "feeling" or "wanting" work.  
		- ## Free will
			- The combination of being able to model something, imagine ways for that something to be manipulated, plan for desired manipulations of the something, and finding that those plans unobstructed is instrumentally quite an important property to track. Hence, there is an important symbol associated with this: "X is under control" (real). This symbol isn't using any sort of Self or Identity symbol, it's just a raw sense of control.
			    
			  With the advent of Self, this sense of control can be applied to it. If all the conditions are met (as is typically the case), then her mind may generate the symbol "SELF is under control" (real). This gives rise to a sense of self-control, the sense of being able to choose one's own path.  
			    
			  Suppose a faerie learns that an object's actions are determined. Her planning facilities will (typically correctly) judge that there is nothing she can do to change the outcome. The object will therefore lose the aura of being under her control, if it once had it. Following this, her mind will decide to allocate less energy towards intentions of controlling the object.  
			    
			  The same thing can happen when a faerie learns that she herself can be described as a deterministic process. Her planning facilities may (this time incorrectly) judge that there is nothing she can actually do to change her actions. This can lead to feeling unmotivated.  
			- It's useful to have a concept of when something is under your control while planning. By control, I mean that your planning facilities have a robust path to cause it to change in ways that make planning easier. This concept is naturally important to the conspecific model too: "She controls that. She's the one that can decide whether that happens. It's up to her". Now, it turns out that the self model is under your control in this sense! Unconscious planning facilities have direct influence over your immediate action, and this is a useful thing to be able to change when doing longer-term planning. When applied to self, it therefore causes the same sorts of thoughts: "I control myself. I'm the one that decides what I'll do. Who I'll be is up to me." And these thoughts feel REAL. This explains why we have such a strong sense of Free Will.
		- ## What are faeries conscious of?
		    
		  Can a faerie be conscious of whether a particular neuron is firing? Without an obvious analogue for her to observe in other faeries, she will not develop the requisite empathetic symbol.  
		    
		  While faeries can be conscious of many things, there are differences from faerie to faerie. This is because the empathetic symbols need to be learned. A faerie who is uninterested in what other faeries are visually imagining will not develop detailed symbols for visual imagination, and will therefore have weak or undetailed awareness of her own visual imagination. This does not appear to be how human consciousness works.  
		- ## A space to think
		- The ability of empathy allows for reasoning about a mind's thoughts, feelings, and experiences.
		    
		  Applied to the self representation, it allows for reasoning about your own thoughts, feelings, and experiences.  
		    
		  Until this, there was no such sense, no ability to know your own thoughts.  
		    
		  Introspection is therefore now possible, though it is a somewhat crude sense given the indirection involved. The *only* internal thoughts that faeries are ever consciously aware of are ones for which symbols of this form were developed, which is why faeries find introspection difficult.  
		-
		-
		- Any self awareness a reflective mind has comes from the empathetic senses applied to the self model. So, a faerie will be conscious of symbols output by her empathetic model of herself. No more and no less.
		-
		- We also are able to see what is not under conscious awareness. It's limited to exactly the things that the conspecific model tracks. That's why you don't have any insight into all the stuff your brain is doing to manage your immune system. [1] This puts a severe limit on a faerie's ability to introspect. In order to be consciously aware of a thought, her conspecific model needs to predict what she is thinking. In order for her conspecific model to be aware of her state, and in particular what her most recent thoughts were, it has to rely on sensory data.
		-
		- Now that *symbols* for thoughts, feelings, and experiences exist at all, the various subparts of the faerie's mind can now take them as inputs, further refining their own more specialized models. (These subparts already sent their outputs to the symbolic reasoning part of the brain.) This means that the subparts can communicate with each other to a degree not previously possible, and these communications will automatically be conscious.
		    
		  To facilitate and improve this processing ability, the self model evolved to be able to store a handful of these shared representations temporarily. This is known as working memory.  
		    
		  Furthermore, this constant usage means that your Self model is being invoked almost constantly while you are awake/conscious.  
		    
		  This is why your own feelings are so much more salient than those of others, even very close ones.  
		-
		- The conspecific model needs to aggregate all the information it can that's relevant to predicting conspecifics. What they see, hear, touch, taste, smell; what they think, feel, and value, and quirks in how they process and react to things. And use this information to predict what might be said, thought, or done.
		- The self conspecific gets all of this information associated with it, updated in real time. So it's a singular model which is able to manage symbols of all these types, and make predictions on that basis. And it doesn't require special connections between the various specific parts of the brain to do this, since it has learned how to use these under the abstraction of these being inferred facts about someone else by default.
		-
		- These aspects account for the "global workspace" intuitions of what consciousness is.
		-
		- ## Psychosis
		- During periods of intense social factionalism, certain instincts evolved, triggered by a sudden update of a model of a specific conspecific. For example, upon suddenly realizing your "friend" has been deceiving you about their past and intentions... it's prudent in such an environment to start feeling paranoid about them, and thinking of awful things they might be thinking of doing. Specifically, maybe a symbol like this: X think-says "I'm going to do such-and-such awful thing" (IMAGINED, HYPOTHETICAL) When one's self model changes rapidly in the relevant way, the same instinct triggers, since the self model is a conspecific model. So it generates a feeling of paranoia about yourself ("I'm afraid I might hurt someone"), and also triggers thoughts like Self think-says "Self is going to do such-and-such awful thing" (REAL, HYPOTHETICAL). This therefore feels like you are really having-hearing that thought.
		-
		- ## Psychedelics
		- There is a certain mushroom known to the faeries which interferes with the GRS, causing errors in the reality judgments for some symbols. As far as consciousness goes, it can cause some strange effects. Typically, the majority of symbols are still being judged correctly, with only around 1 in 5 having the wrong judgements. So the faerie can very well be conscious in the ordinary way while having these experiences.
		    
		  The main effect is that these mushrooms cause vivid hallucinations in faeries, as a result of the more ordinary GRS errors. However, there are some strange things that occur regarding consciousness:  
		- "SELF SEES <observation>" (imagined) along with "<observation>" (real) Subjectively, this is similar to seeing someone else observe something; it feels like *you* are somehow not actually seeing it. So the observed events feel as if they are simply present. Faeries often describe this as an event in which their sense of self disappeared.
		- "X SEES <observation>" (real) This feels like you can see through other people's eyes. The faerie might recognize that she can't literally see what they're seeing, but it still somehow feels totally real. Faeries may also infer that this means that X actually is the same as SELF in some way not appreciated before, which generalizes to a sense that all minds are one, that there is a universal consciousness. ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ ㅤ
		- Among the faeries, there is a certain mushroom which has a chemical which disrupts the GRS system, such that some outputs are incorrectly tagged as REAL or IMAGINED. This has some interesting effects: The faerie becomes consciously aware of some imagined things (falsely tagged REAL). The faerie will be prone to having symbols involving self as IMAGINED, leading her to the false realization that her self isn't actually real. The faerie will also be prone to having symbols involving other faeries' experiences get marked as REAL, causing her to consciously experience her predictions of their experiences. So she'll feel like she can literally feel what other faeries are feeling. And since this works for arbitrary faeries, she's likely to conclude that there is a universal ^^consciousness^^.
		-
		-
		-
---
		- It's speculated that sleep is necessary for faeries in order to give the brain a break from this otherwise constant oscillation.
		- Even after developing empathy, faeries retain non-empathetic models of other faeries that are distant from them. It thus can feel like faeries of other lands are not *really* people the same way that the faeries you grew up with are (even if you don't have any animosity towards them). In large cosmopolitan environments, repeated interactions with faeries from distant lands incentivize use of the empathetic model for them (as its initial purpose is to allow for more detailed models of others). This leads to the faerie's mind generalizing to the fact that faeries of all lands are people.
		- Incidentally, this ends up being why faeries are not automatically conscious of things like which muscles they are using.
	- B
		- Once upon a time, there was a species that became conscious. I'll call them Faeries, so that you'll remember that this story is not based on facts about neuroscience or evolution, but is complete speculation. Whether human ^^consciousness^^ works in a similar way is yet to be seen, but I thought it would be interesting to have any explanation at all for the main facts of ^^consciousness^^, which is what I attempt here. My approach is to think through what evolutionary pressures would shape minds into the sort of thing that started saying things like "Wow, this red is just so red!". Evolution can't just make new mind-parts out of nothing! Each new aspect has to have a clear precedent, along with the pressure to shape it in the required way. This is very constraining, which makes it very helpful for thinking about this clearly. Even when I'm trying to account for the vastness of human experience, I find myself surprised at how different other people's internal experiences can seem. So it seems likely you will understand some of these terms differently. In that case, I hope you will try to see past that to the thing that I'm describing. In the following, when I refer to things that the faerie's mind is doing, these should not be assumed to be at all in her conscious awareness (which would presuppose the very thing I'm trying to explain). I'll try to use the word *process* instead of *thinks* for this to help make this point clear. Evolution Modeling The faerie ancestors had to model their environment. This is a mathematical mandate of the Good Regulator Theorem. Even starting with the single-celled ancestors, there were transcription networks which served this function. Many transcription factors in these can be thought of as symbols, indicating some sort of information. One factor might come to represent the presence of high temperature, another factor might represent a decision to move in the ventral direction. Faerie neurons evolved in order to efficiently transfer this sort of information across cells once they became multi-cellular. But the new medium proved to be much more versatile, and it was increasingly important to process information effectively as the world started looking bigger and faster. Faerie brains pass symbols much like the transcription factors of old, summaries of models and decisions. But they can be much richer, and can carry contextual information with them. I'll represent the outputs of these models as symbols, like red. Planning In a rapidly changing and challenging environment, it's necessary to plan actions before taking them. By "planning", I mean the process of imagining various possibilities in order to select the optimal one. Now, imagined outputs of models need to be distinguished from genuine representations, even though the same model is used for both representation and imagination. These models can't process both at the same time, and it would be dangerous to have sensory models busy doing other things for a significant length of time. So these minds evolved to rapidly alternate between processing real data and imagined data. This is governed by a general signal: the Global Reality Signal (GRS). During the "real" phase of the GRS, models are connected to the present sensory data and present volitional drives. The models do their thing, letting the individual understand their present circumstances, and act accordingly. About 25ms later, the "fake" phase of the GRS turns on, and models are fed whatever imagined data the mind is interested in. At each point, the status of the GRS is carefully tracked. This gives the mind an unambiguous reality signifier that can't (easily) be fooled by thinking imagined sensory data is real (as would be the case if "real" was treated as another model subject to mental manipulations). Importantly, this signal is immutable (in normal operation). The metadata always has to be there, and nothing is allowed to change it. Also, this is not what is happening when you consciously imagine something, which is a much more complex type of object (and tagged as REAL, incidentally). Social Modeling In a social environment, the faeries start to need to model their conspecifics very well. There turns out to be a convenient shortcut: the faerie's own brain, but with imagined sense data from the other faerie's perspective. These outputs get tagged with IMAGINED, even though they are about something that is presently happening. As the usefulness of these outputs is validated, special facilities evolve for organizing them and tracking who, and whether the situation is hypothetical or not. This signal is also metadata: ACTUAL or HYPOTHETICAL, though it's more malleable than the sacrosanct reality signal. This means there's a sort of summary model for each conspecific, which includes the information needed to imagine each one, along with the particular way in which the outputs need to be adjusted in order to make the model more accurate. But the REAL outputs get put through the same facilities, which get attributed to a "self" conspecific. Abstraction As their thinking and socializing gets more complex, faeries are pressured to evolve certain abstraction capabilities. I've given different types of abstraction special names. **analogizing** - using an existing model as a starting point for a new model (more efficient than starting from scratch). **generalizing** - creating a new model to be a more efficient model (though typically less precise) of several other models. **conceptualizing** - where a "missing model" can be noticed and fleshed out within the network of existing models. **reducing** - a process which attempts to replicate a given model using a network of simpler and "smaller" models (i.e. do not reference any models which reference the original model - no circular dependencies). Specifically, the ability to notice when something is missing. Not just "oh huh, that thing that was here is gone", but being able to infer the presence of an entity which she has never before seen. Such a faerie may notice that there seems to be a mysterious extra faerie in the tribe. Someone all her friends and family appear to be tracking, and whose actions are socially relevant to her such that it's worth getting a bit preoccupied with this mysterious faerie. And then one night, talking with her sister by a still pond in the moonlight... she looks in the pond—and sees her sister talking to her. Empathy Alright, let's get back to our faeries. At this point in their evolution, they had the ability to do symbolic reasoning, and abstract thought. So of *course* they represented their conspecifics. Their parents and children, their friends and their lovers. And as they thrived by this ability, evolution happened upon a strange trick which I'll call **empathy**. Representing another being as complicated as yourself is tricky business. Everything of import that a mind is already doing now has to be represented in the same kind of mind. Not just once, but several times over! The standard means of representation can adequately provide low-resolution representations of others. But for higher fidelity, these methods no longer can keep up. [racism footnote] What's much easier is to simply imagine *being* that faerie; imagine their experiences, and imagine having their goals. A mind which happened upon this trick would find its representations coming together to generate a response, a response with Foresight into the actual other faerie's actions. So the minds evolved to be good at doing this trick, to the extent that it became one of the most comfortable ways of thinking about something, even if that thing wasn't very much like a faerie mind. To the extent that it was automatically invoked in the presence of loved ones. This notion of empathy does not require or imply love or sympathy; sadism is also built from this empathetic structure. It also is not the thing you do when you're *consciously* trying to empathize with somebody. Instead, it's more like the thing that makes you reflexively wince when you see someone stub their toe. Reflection Thinking about this "self" faerie turns out to be advantageous enough that she begins to imagine it by default. Explanations The Hard Problem ...even when we have explained the performance of all the cognitive and behavioral functions in the vicinity of experience—perceptual discrimination, categorization, internal access, verbal report—there may still remain a further unanswered question: Why is the performance of these functions accompanied by experience? –David Chalmers Let's put our faerie in a bright red room. Her sensory models process the stimulus of red. First, let's get the ontological status of this out of the way. We can treat the (REAL) tag as an ontological judgement of "Here" in a 1st person (i.e. subjective) logic. This is not a form of knowledge that can be directly considered as an ordinary 0th person logical statement. So we can interpret red (REAL) as meaning that the referent of red is present for her, i.e. that she experiences it. That's not anything particularly special; a simple robot with a photodiode detecting red can be considered to be having an experience in the same way. But it let's us explains the "Mary's Room" aspect: Mary learns a 1st-person statement when she sees red, which is not accessible via 0th-person reasoning. But that's not all that happens! The conspecific model captures this symbol, and repackages it as Self sees red (REAL ACTUAL). To understand the implications of this, let's first consider how our faerie might process her sister seeing red. She gets a symbol Sister sees red (IMAGINED ACTUAL). Like any IMAGINED symbol, it is faint in that its influence on actions or updates is severely muted. Due to the ACTUAL tag, it is accompanied by a sense that someone is experiencing it. That's what the conspecific model is for, right? This might all ultimately result in sentences being generated like "oh yeah, she saw something red". Now, how will her reaction differ for the Self sees red (REAL ACTUAL) symbol? Well for one, she will treat it as a real and vivid thing that she has Experienced (like anything REAL), giving it intrinsically more salience. And again, due to the ACTUAL tag, it is accompanied by a sense that someone is experiencing it. That's why she conceptualizes it as an experience! This is not something that would have happened without the conspecific model. This might result in a sentence like "wow, I'm like... actually seeing red rn!" being generated instead. Common Intuitions Free Will It's useful to have a concept of when something is under your control while planning. By control, I mean that your planning facilities have a robust path to cause it to change in ways that make planning easier. This concept is naturally important to the conspecific model too: "She controls that. She's the one that can decide whether that happens. It's up to her". Now, it turns out that the self model is under your control in this sense! Unconscious planning facilities have direct influence over your immediate action, and this is a useful thing to be able to change when doing longer-term planning. When applied to self, it therefore causes the same sorts of thoughts: "I control myself. I'm the one that decides what I'll do. Who I'll be is up to me." And these thoughts feel REAL. This explains why we have such a strong sense of Free Will. Global Workspace The conspecific model needs to aggregate all the information it can that's relevant to predicting conspecifics. What they see, hear, touch, taste, smell; what they think, feel, and value, and quirks in how they process and react to things. And use this information to predict what might be said, thought, or done. The self conspecific gets all of this information associated with it, updated in real time. So it's a singular model which is able to manage symbols of all these types, and make predictions on that basis. And it doesn't require special connections between the various specific parts of the brain to do this, since it has learned how to use these under the abstraction of these being inferred facts about someone else by default. Introspection We also are able to see what is not under conscious awareness. It's limited to exactly the things that the conspecific model tracks. That's why you don't have any insight into all the stuff your brain is doing to manage your immune system. [1] This puts a severe limit on a faerie's ability to introspect. In order to be consciously aware of a thought, her conspecific model needs to predict what she is thinking. In order for her conspecific model to be aware of her state, and in particular what her most recent thoughts were, it has to rely on sensory data. Psychedelics Among the faeries, there is a certain mushroom which has a chemical which disrupts the GRS system, such that some outputs are incorrectly tagged as REAL or IMAGINED. This has some interesting effects: The faerie becomes consciously aware of some imagined things (falsely tagged REAL). The faerie will be prone to having symbols involving self as IMAGINED, leading her to the false realization that her self isn't actually real. The faerie will also be prone to having symbols involving other faeries' experiences get marked as REAL, causing her to consciously experience her predictions of their experiences. So she'll feel like she can literally feel what other faeries are feeling. And since this works for arbitrary faeries, she's likely to conclude that there is a universal ^^consciousness^^. Psychosis During periods of intense social factionalism, certain instincts evolved, triggered by a sudden update of a model of a specific conspecific. For example, upon suddenly realizing your "friend" has been deceiving you about their past and intentions... it's prudent in such an environment to start feeling paranoid about them, and thinking of awful things they might be thinking of doing. Specifically, maybe a symbol like this: X think-says "I'm going to do such-and-such awful thing" (IMAGINED, HYPOTHETICAL) When one's self model changes rapidly in the relevant way, the same instinct triggers, since the self model is a conspecific model. So it generates a feeling of paranoia about yourself ("I'm afraid I might hurt someone"), and also triggers thoughts like Self think-says "Self is going to do such-and-such awful thing" (REAL, HYPOTHETICAL). This therefore feels like you are really having-hearing that thought. Enlightenment IFS and Tulpas Feral Children



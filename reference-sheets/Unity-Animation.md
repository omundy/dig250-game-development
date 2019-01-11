

![unity logo](images/unity-logo-293w.png)

## Reference Sheet - Unity Animation





### Terminology

Term | Definition
--- | ---
Animation Frame | A single moment in time, where properties or different sprites could be displayed.
[Animation Clips](https://docs.unity3d.com/Manual/class-AnimationClip.html) | A single clip, with either a sprite frame by frame animation or changes to properties, viewable on a timeline. These represent isolated pieces of motion, such as Run, Jump, or Crawl, and are controlled by the Animation Controller.
[Animator Controller](https://docs.unity3d.com/Manual/class-AnimatorController.html) | The “brain” or “state machine” where you control which animation clip is playing and the conditions for how transitions between animation clips happen.
[Animation States](https://docs.unity3d.com/Manual/StateMachineBasics.html) | Every character will always be engaged in some kind of action at a given time. The actions available will depend on the type of gameplay but typical actions include things like idling, walking, running, jumping, etc. These actions are referred to as states.
[Animation Transitions](https://docs.unity3d.com/Manual/class-Transition.html) | The switch or blend from one animation to another in the state machine and under what conditions the change should occur.
[Animation Parameters](https://docs.unity3d.com/Manual/AnimationParameters.html) | Variables defined within an Animator Controller that allow script control over the flow of the state machine. For example, if a player makes a character jump, we can use code to set a `grounded` property to false. We can set the state machine to transition to a jump animation in this case.


### Sources
* Unity Manual: [Animation](https://docs.unity3d.com/Manual/AnimationSection.html) and [Unity Scripting Reference](https://docs.unity3d.com/ScriptReference/index.html)
* Chapter 5 in Ferro, Lauren S., and Francesco Sapio. Unity 2017 Game Development. Packt, 2018.
* Chapter 4 in Hocking, Joseph. Unity in Action: Multiplatform Game Development in C # (2nd Edition). Manning, 2018.
* Chapter 2 in Godbold, Ashley, and Simon Jackson. Mastering Unity 2D Game Development (2nd Edition). Packt, 2016. 
* Chapter 3 in Halpern, Jared. Developing 2D Games with Unity. APress, 2019.

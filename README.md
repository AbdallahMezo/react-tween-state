# React animation example

This is an example of touch gestures and animations on React by building a Facebook-like left nav. **Mobile only**.

## Motivations

**Mobile first.** It's where the growth is, and where the web performs the worst.
**JavaScript only.** To get native-quality interactions, you need ultra-fine-grained control that CSS animations don't give you.
**60 frames per second.** No exceptions
**Prefer higher quality interactions to higher compatibility.** Right now I'm only testing on an iPhone 5, but it works OK on a Nexus 7.
**Application code does no optimizations.** React should do them all for you (i.e. batching within a single requestAnimationFrame).
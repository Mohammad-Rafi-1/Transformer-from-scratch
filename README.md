# Transformer-from-scratch

The transformer uses an encoder-decoder architecture. The encoder extracts features from an input sentence, and the decoder uses the features to produce an output sentence (translation).

The core idea behind a transformer model is self-attention—the ability to attend to different positions of the input sequence to compute a representation of that sequence

here key/value/query concept is analogous to retrieval systems. For example, when you search for videos on Youtube, the search engine will map your query (text in the search bar) against a set of keys (video title, description, etc.) associated with candidate videos in their database, then present you the best matched videos (values).(reference stackoverflow)

The attention operation can be thought of as a retrieval process as well

transformer use positional encoding , these positional encoding describes the location or position of an entity in a sequence so that each position is assigned a unique representation.

![Transfromer](https://user-images.githubusercontent.com/97906845/174576716-51f98b6c-a73c-41a3-a5ca-ceb144661a5e.png)

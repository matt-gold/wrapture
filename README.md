# 📦 Introducing Wrapture: A Better Way to Wrap, Track, and Compose Data
In modern applications, data rarely travels alone. It comes with state — is it loading? is it fresh? has it failed before? — and often metadata like timestamps, source info, or even edit history.

Wrapture is a tiny utility for building your own rich, self-aware data wrappers — containers that hold your value and everything that matters around it.

But unlike libraries that hardcode state or structure, Wrapture is fully configurable. You define what the wrapper should track — whether that’s loading state, history, validation errors, function execution status, or anything else. Think of it as a toolkit for making your own smart data types — not just using someone else’s.

🔧 Core features
🧠 Custom wrappers for any kind of data or function — with state, metadata, or other context

🎛️ Configurable behaviors — define what’s tracked and how it's transformed

🔄 Built-in composition/mapping utilities — combine multiple wrappers into one, safely and cleanly

🧵 Support for wrapped functions with any number of arguments — not just values, but callable logic with context

🪞 Proxy or standard mode — choose how your wrapper exposes the underlying value

Wrapture is perfect for async data (tracking loading, success, error, etc.), but it’s just as useful for:

Function calls that carry execution state or analytics context

Forms that track validity, dirty fields, and touched state

Derived or computed values from multiple sources

Domain-specific data types with logic and state embedded

If you're familiar with functional programming, you'll recognize patterns like monads or combinators — but you don’t need to know those terms to use Wrapture. We’ve taken the underlying power and made it practical, typed, and ready for everyday TypeScript code.

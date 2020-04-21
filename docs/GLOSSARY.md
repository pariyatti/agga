# Pariyatti Glossary

Please use this document to define terms specific to the domain of the Pariyatti Mobile App. "Domain" in this context refers to Domain-Driven Design with an explicit focus on [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html). The terms defined in the Glossary should be used and understood by users, designers, developers, and testers _ubiquitously_.

As we come across new terms or adjust old terms, please define and re-define them here. If you are new to the Pariyatti app team, please read this document before contributing.

Words in Title Case are first-class citizens in the end user's vocabulary. Try to keep this list small and obvious.

## In Alphabetical Order:

- **Account**: The "Account" **section** contains the currently logged-in user's account information, such as whether or not they are an old student.

- **artefact**: Any concrete resource from the four main categories: Documents, Images, Audio, Video. We will prefer the terminology "artefact" internally because "resource" is a highly overloaded term.

- **Audio**: This describes any Audio file (`.mp3 .flac etc`). Examples include: a lecture, anapana meditation instructions, group sittings, or Pali pronunciation.

- **card**: A key UI component in the mobile app, items in the "Today" **tab** will be grouped into "cards" similar in physical appearance to a recipe card.

- **Document**: Users can download or purchase documents. Examples of a "Document" include: Book, Essay, Article, Transcript, Excerpt, and Quote.

- **Donate**: The "Donate" **section** contains an online payment form the user may use to make a donation to the Pariyatti 501(c)(3) non-profit organization. This **tab**/**section** may or may not be included in the first version of the app.

- **Image**: Any Image file (`.jpg .png etc`) may form a part of another UI element, Resource, or Page. In some cases, users may want to download an Image directly so they can print off a high-resolution image. Specific cases might include a detailed drawing, an image of a Vipassana Centre, or a photo of historical significance.

- **metadata**: Library metadata is content which describes content. Metadata is used for search and organizing the library but never contains library artefacts/resources directly. Examples include: geographic location, Author, language, file type, audience, topic, and collection.

- **Offerings**: The "Offerings" **section** contains information on Pali Study and Pilgrimages. This **tab**/**section** will be unavailable in the first version of the app.

- **pariyatti**: The Pali word for "theory" in the sense of Dhamma, as taught intellectually, through literature. Also the name of the [501(c)(3) US-based non-profit](https://en.wikipedia.org/wiki/Pariyatti).

- **prototype**: A prototype is an experiment _for the users_, not the developers. A prototype is a process, not an ad-hoc activity. Semantically similar to "spike" but with the intention of keeping the output and iterating on it. A prototype can be thought of as a spike that has graduated to a point where users will get involved in experimentation. Unlike spikes, prototypes usually signal the beginning of a new app/product/project.

- **Resources**: The "Resources" **section** contains searchable books, audio, and videos as both online content and physical media for sale through the [Pariyatti Store](https://store.pariyatti.org/). Internally, Resources will be referred to as "Artefacts" --- this should be the only synonym in the entire system and it only exists to avoid the very-overloaded use of the noun "Resources" within the code.

- **roster**: The Pariyatti team roster consists of Pariyatti staff, long-term volunteers, short-term volunteers, and folks who are available for consultation. The roster is a private document [found here](https://drive.google.com/drive/folders/1RTAw2izD3m9hb79DJE2uu-4qepFby0px).

- **section**: A group of information available through the app by clicking one of the five **tabs** at the bottom of the screen.

- **spike**: A spike is an experiment _for the developers_, not the users. A spike is an activity, not a process. Traditionally an experimental sample of a proposed application, running from the user interface(s) to the back end processing and storage services. Semantically similar to "prototype" but a spike is usually thrown out rather than iterated on once it has proven useful. We might also "spike" experiments with different software frameworks or architecture before the actual development begins but a spike is as likely to happen during active development as it is at the beginning of a project. The end result of a spike is usually a decision by the developer(s) who "spiked" an idea or a report detailing their findings so the team can make a decision and move forward.

- **tab**: The five **sections** of the app ("Today", "Resources", "Offerings", "Account", "Donate") can be navigated to, from the bottom of the app, with clickable UI elements called "tabs".

- **Today**: The "Today" **section**, available from the "Today" **tab** at the bottom of the screen, displays an infinite scrolling UI of bite-sized content presented as **cards**.

- **Video**: Describes any Video file (`.mp4`, a YouTube link, etc). Examples of Videos might be documentaries, video lectures, discourses, video tours, Pali lessons, etc.

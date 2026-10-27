# CampusPulse AI 🎓🤖

An intelligent **College Event & Club Information Bot** built with React, Vite, and an interactive **Retrieval-Augmented Generation (RAG)** architecture for campus life.

CampusPulse AI provides students with verified, source-grounded answers about student clubs, upcoming events, club recruitment status, venue booking guidelines, and campus policies.

---

## 🌟 Key Features

- 💬 **Grounded AI RAG Assistant**:
  - Answers campus queries with cosine similarity retrieval over pre-chunked college documents.
  - Transparent citation badges showing source document filenames, chunk IDs, and similarity scores.
  - Interactive source inspector to view exact passages from university charters and handbooks.

- 🏛️ **Explore Clubs Directory**:
  - Browse student clubs across Tech, Arts, Finance, and Sustainability categories.
  - Live recruitment status tags (**Open** / **Closed**).
  - Built-in modal for membership application forms or waitlist registration.

- 📅 **Interactive Event Calendar**:
  - Filter upcoming campus hackathons, photo walks, and eco fairs.
  - Live seat counters and one-click RSVP confirmation.
  - Detailed modal with event schedules, venues, and agendas.

- 🔍 **Vector Inspector & Similarity Tester**:
  - Educational dashboard displaying vector index statistics (chunks, vocabulary terms, simulated dimensions).
  - Real-time similarity sandbox with adjustable Top-K and score threshold sliders.
  - Re-indexing simulation showing chunking and embedding status transitions.

---

## 🛠️ Tech Stack

- **Framework**: React 18, Vite
- **Styling**: Tailwind CSS, PostCSS, Lucide Icons
- **Typography**: Plus Jakarta Sans
- **Retrieval Engine**: TF-IDF tokenization, stemmer, and cosine similarity vector scoring

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dasaripandu2321/College-event-and-club-information-bot.git
   cd College-event-and-club-information-bot
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

---

## 📁 Project Structure

```
├── public/                 # Static assets
├── src/
│   ├── App.jsx             # Main application shell, knowledge base, RAG engine, & tabs
│   ├── main.jsx            # React root mount
│   └── index.css           # Tailwind directives & global typography
├── index.html              # HTML entry point with metadata and fonts
├── package.json            # Project dependencies & scripts
├── tailwind.config.js      # Tailwind CSS configuration
└── vite.config.js          # Vite configuration
```

---

## 📄 License

This project is open-source under the MIT License.

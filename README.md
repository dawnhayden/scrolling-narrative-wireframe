# scrolling-narrative-wireframe
basic wireframe for experimental narrative website with Mermaid Diagram
```mermaid
graph TD
    A[Hero Section - Video of Dogs Running on the Beach]
    A --> B[Introduction - Parallax Montana Landscape with Narrative Text]
    B --> C[Scene 1: Willie Nelson Concert - Animated Lyrics and Illustrative Overlays]
    C --> D[Scene Transition - Fade to Black]

    D --> E[Beach Scene in Sri Lanka - Illustrations Overlaid on Photos]
    E --> F[Interactive Dialogue - Popup Animations for Dialogue]
    F --> G[Dogs Running on the Beach - Video Loop Emphasis]
    G --> H[Dark Scene with Light Effect - Character at School Desk]

    H --> I[Phone Call Scene - Split Screen with Mommom and Dad]
    I --> J[Background: Fading Images of Tsunami Devastation]
    J --> K[Overlay: Upbeat Audio with Laughter and Dialogue]
    
    K --> L[Bucket of Tea Scene - Red Bucket Fades In]
    L --> M[Audio: Murmurs, Pouring Sounds, Growing Laughter]
    
    M --> N[Final Reflections - Emotional Close of Narrative]
    N --> O[Call to Action - Soft Fade to Invitation to Share/Follow]
    O --> P[Footer - Social Media Links and Contact Info]

    %% Styling for various sections
    classDef heroSection fill:#ddeeff,stroke:#333,stroke-width:2px;
    classDef storySection fill:#e6ffee,stroke:#333,stroke-width:2px;
    classDef interactive fill:#ffedde,stroke:#333,stroke-width:2px;
    classDef suspenseSection fill:#333344,stroke:#666,stroke-width:2px, color:#ffffff;
    classDef phoneCall fill:#fef3c7,stroke:#333,stroke-width:2px;
    classDef teaScene fill:#ffe5e5,stroke:#b33,stroke-width:2px;
    classDef finalSection fill:#cce7ff,stroke:#333,stroke-width:2px;

    class A heroSection;
    class B,C,E,G,I,L storySection;
    class D,H suspenseSection;
    class F interactive;
    class J,K phoneCall;
    class M teaScene;
    class N,O finalSection;
    class P finalSection;

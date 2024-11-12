# scrolling-narrative-wireframe
basic wireframe for experimental narrative website with Mermaid Diagram
```mermaid
graph TD
    A[Hero Section - Video of Dogs Running on the Beach]
    A --> B[Introduction - Parallax Montana Landscape with Narrative Text]
    B --> C[Scene 1: Cowboy Hat at Maggie’s House - Illustrations and Photos]
    C --> D[Willie Nelson Concert - Animated Lyrics and Illustrative Overlays]
    D --> E[Scene Transition - Fade to Black]
    
    E --> F[Decision Scene at Megan’s House - Key Moment Emphasis]
    F --> G[Beach Scene in Sri Lanka - Illustrations Overlaid on Photos]
    G --> H[Interactive Dialogue - Popup Animations for Dialogue]

    H --> I[Dogs Running on the Beach - Video Loop Emphasis]
    I --> J[Bucket of Tea Scene - Red Bucket Fades In]
    J --> K[Audio: Murmurs, Pouring Sounds, Growing Laughter]

    K --> L[Dark Scene with Light Effect - Character at School Desk]
    L --> M[Phone Call Scene - Split Screen with Mommom and Dad]
    M --> N[Background: Fading Images of Tsunami Devastation]
    N --> O[Overlay: Upbeat Audio with Laughter and Dialogue]
    
    O --> P[Final Reflections - Emotional Close of Narrative]
    P --> Q[Call to Action - Soft Fade to Invitation to Share/Follow]
    Q --> R[Footer - Social Media Links and Contact Info]

    %% Styling for various sections
    classDef heroSection fill:#ddeeff,stroke:#333,stroke-width:2px;
    classDef storySection fill:#e6ffee,stroke:#333,stroke-width:2px;
    classDef interactive fill:#ffedde,stroke:#333,stroke-width:2px;
    classDef suspenseSection fill:#333344,stroke:#666,stroke-width:2px, color:#ffffff;
    classDef decisionScene fill:#ffe5c7,stroke:#333,stroke-width:2px;
    classDef phoneCall fill:#fef3c7,stroke:#333,stroke-width:2px;
    classDef teaScene fill:#ffe5e5,stroke:#b33,stroke-width:2px;
    classDef finalSection fill:#cce7ff,stroke:#333,stroke-width:2px;

    class A heroSection;
    class B,C,D,F,H,I storySection;
    class E suspenseSection;
    class G interactive;
    class J teaScene;
    class K,L suspenseSection;
    class M,N,O phoneCall;
    class P,Q finalSection;
    class R finalSection;


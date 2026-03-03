DayFarm Visualizer \- AI Image Generation Prompts  
\=================================================

Reference images location: C:\\Users\\tqfos\\AppData\\Local\\Temp\\dayfarm-pages\\photos\\

Save generated images with the filenames listed below, then paste the folder path back to Claude Code to wire them into the gallery.

WHITE CABINET VARIANTS (3)  
\===========================

Image 1: 05-kitchen-island.jpg  
Save as: 05-kitchen-island-white.jpg

JSON prompt:  
{  
  "task": "image\_edit",  
  "base\_image": "05-kitchen-island.jpg",  
  "edit\_target": "wall cabinets only (upper and lower, NOT the island)",  
  "change": "honey-brown wood \-\> white painted cabinets",  
  "preserve": \["blue-gray island", "granite countertops", "stainless appliances", "tile floor", "walls", "lighting", "backsplash", "white pantry door"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Edit this kitchen photo: Change ONLY the wood wall cabinets (upper and lower) from honey-brown to white painted. Keep the blue-gray island, granite countertops, stainless appliances, tile floor, walls, lighting, backsplash, and pantry door exactly the same.

\---

Image 2: 06-kitchen-galley.jpg  
Save as: 06-kitchen-galley-white.jpg

JSON prompt:  
{  
  "task": "image\_edit",  
  "base\_image": "06-kitchen-galley.jpg",  
  "edit\_target": "all wood cabinets",  
  "change": "honey-brown wood \-\> white painted cabinets",  
  "preserve": \["countertops", "appliances", "backsplash", "flooring", "walls", "lighting"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Edit this kitchen photo: Change ONLY the wood cabinets from honey-brown to white painted. Keep all countertops, appliances, backsplash, flooring, walls, and lighting exactly as they are.

\---

Image 3: 08-master-bath.jpg  
Save as: 08-master-bath-white.jpg

JSON prompt:  
{  
  "task": "image\_edit",  
  "base\_image": "08-master-bath.jpg",  
  "edit\_target": "wood vanity cabinets",  
  "change": "brown/dark wood \-\> white painted cabinets",  
  "preserve": \["countertops", "mirrors", "fixtures", "walls", "flooring", "tub"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Edit this photo: Change ONLY the wood vanity cabinets from brown/dark wood to white painted. Keep countertops, mirrors, fixtures, walls, flooring, and tub exactly as they are.

\===========================  
VIRTUAL STAGING (3)  
\===========================

Image 4: 03-living-room.jpg  
Save as: 03-living-room-staged.jpg

JSON prompt:  
{  
  "task": "virtual\_staging",  
  "base\_image": "03-living-room.jpg",  
  "add": "modern minimal furniture: neutral-toned sofa, accent chair, coffee table, area rug",  
  "style\_guide": "contemporary clean lines, NOT oversized, warm neutral palette",  
  "preserve": \["fireplace", "hardwood flooring", "walls", "windows", "ceiling", "crown molding"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Add modern, minimal furniture to this empty living room: a neutral-toned sofa, accent chair, coffee table, and area rug. Contemporary style, clean lines, not oversized. Keep the fireplace, flooring, walls, and windows exactly as they are.

\---

Image 5: 04-open-concept.jpg  
Save as: 04-open-concept-staged.jpg

JSON prompt:  
{  
  "task": "virtual\_staging",  
  "base\_image": "04-open-concept.jpg",  
  "add": "modern minimal furniture: neutral sofa, dining table with chairs, area rug",  
  "style\_guide": "contemporary clean lines, NOT oversized, warm neutral palette",  
  "preserve": \["all existing architecture", "flooring", "walls", "kitchen"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Add modern, minimal furniture to this open living/dining area: a neutral sofa, dining table with chairs, and area rug. Contemporary clean-line style. Keep all existing architecture, flooring, walls, and kitchen exactly as they are.

\---

Image 6: 07-master-bedroom.jpg  
Save as: 07-master-bedroom-staged.jpg

JSON prompt:  
{  
  "task": "virtual\_staging",  
  "base\_image": "07-master-bedroom.jpg",  
  "add": "modern bedroom furniture: queen/king bed with neutral bedding, two nightstands, area rug",  
  "style\_guide": "contemporary minimal, NOT oversized or gaudy",  
  "preserve": \["crown molding", "walls", "flooring", "windows"\],  
  "style": "photorealistic, match existing lighting and perspective"  
}

Plain text prompt:  
Add modern bedroom furniture to this empty room: a queen/king bed with neutral bedding, two nightstands, and an area rug. Contemporary minimal style. Keep crown molding, walls, flooring, and windows exactly as they are.

\===========================  
CHECKLIST  
\===========================  
\[ \] 05-kitchen-island-white.jpg  
\[ \] 06-kitchen-galley-white.jpg  
\[ \] 08-master-bath-white.jpg  
\[ \] 03-living-room-staged.jpg  
\[ \] 04-open-concept-staged.jpg  
\[ \] 07-master-bedroom-staged.jpg  

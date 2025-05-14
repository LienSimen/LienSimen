```stl
solid welcome_cylindrical

  
  // Letter W
  
  // Front Faces
  facet normal 0 0 1
    outer loop vertex 0.0 1.5 0.2 vertex 0.0 0.0 0.2 vertex 0.2 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.2 1.5 0.2 vertex 0.0 0.0 0.2 vertex 0.2 0.0 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.8 1.5 0.2 vertex 0.8 0.0 0.2 vertex 1.0 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 1.0 1.5 0.2 vertex 0.8 0.0 0.2 vertex 1.0 0.0 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.2 0.0 0.2 vertex 0.4 0.0 0.2 vertex 0.5 0.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.2 0.0 0.2 vertex 0.5 0.5 0.2 vertex 0.2 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.8 0.0 0.2 vertex 0.5 0.5 0.2 vertex 0.6 0.0 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.2 0.2 vertex 0.5 0.5 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 0.0 1.5 0.0 vertex 0.2 1.5 0.0 vertex 0.0 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.2 1.5 0.0 vertex 0.2 0.0 0.0 vertex 0.0 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.8 1.5 0.0 vertex 1.0 1.5 0.0 vertex 0.8 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 1.0 1.5 0.0 vertex 1.0 0.0 0.0 vertex 0.8 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.2 0.0 0.0 vertex 0.5 0.5 0.0 vertex 0.4 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.2 0.0 0.0 vertex 0.2 0.2 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.8 0.0 0.0 vertex 0.6 0.0 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 0.8 0.0 0.0 vertex 0.5 0.5 0.0 vertex 0.8 0.2 0.0 endloop endfacet
  // Side Faces
  // Side facets for W - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 0.0 1.5 0.2 vertex 0.0 0.0 0.0 vertex 0.0 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.0 1.5 0.2 vertex 0.0 1.5 0.0 vertex 0.0 0.0 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.0 0.0 0.2 vertex 0.2 1.5 0.0 vertex 0.2 1.5 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.0 0.0 0.2 vertex 0.0 0.0 0.0 vertex 0.2 1.5 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 0.2 1.5 0.2 vertex 0.0 1.5 0.0 vertex 0.0 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 0.2 1.5 0.2 vertex 0.2 1.5 0.0 vertex 0.0 1.5 0.0 endloop endfacet
  // Side facets for W - Triangle 2
  facet normal -1 0 0
    outer loop vertex 0.2 1.5 0.2 vertex 0.0 0.0 0.0 vertex 0.0 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.2 1.5 0.2 vertex 0.2 1.5 0.0 vertex 0.0 0.0 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.0 0.0 0.2 vertex 0.2 0.0 0.0 vertex 0.2 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.0 0.0 0.2 vertex 0.0 0.0 0.0 vertex 0.2 0.0 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.2 1.5 0.0 vertex 0.2 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.2 0.0 0.0 vertex 0.2 1.5 0.0 endloop endfacet
  // Side facets for W - Triangle 3
  facet normal -1 0 0
    outer loop vertex 0.8 1.5 0.2 vertex 0.8 0.0 0.0 vertex 0.8 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.8 1.5 0.2 vertex 0.8 1.5 0.0 vertex 0.8 0.0 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.8 0.0 0.2 vertex 1.0 1.5 0.0 vertex 1.0 1.5 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.0 0.0 vertex 1.0 1.5 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 1.0 1.5 0.2 vertex 0.8 1.5 0.0 vertex 0.8 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 1.0 1.5 0.2 vertex 1.0 1.5 0.0 vertex 0.8 1.5 0.0 endloop endfacet
  // Side facets for W - Triangle 4
  facet normal -1 0 0
    outer loop vertex 1.0 1.5 0.2 vertex 0.8 0.0 0.0 vertex 0.8 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.0 1.5 0.2 vertex 1.0 1.5 0.0 vertex 0.8 0.0 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.8 0.0 0.2 vertex 1.0 0.0 0.0 vertex 1.0 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.0 0.0 vertex 1.0 0.0 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 1.0 0.0 0.2 vertex 1.0 1.5 0.0 vertex 1.0 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 1.0 0.0 0.2 vertex 1.0 0.0 0.0 vertex 1.0 1.5 0.0 endloop endfacet
  // Side facets for W - Triangle 5
  facet normal 0 -1 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.4 0.0 0.0 vertex 0.4 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.2 0.0 0.0 vertex 0.4 0.0 0.0 endloop endfacet
  facet normal 0.928 -0.371 0
    outer loop vertex 0.4 0.0 0.2 vertex 0.5 0.5 0.0 vertex 0.5 0.5 0.2 endloop endfacet
  facet normal 0.928 -0.371 0
    outer loop vertex 0.4 0.0 0.2 vertex 0.4 0.0 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal -0.832 0.555 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.2 0.0 0.0 vertex 0.2 0.0 0.2 endloop endfacet
  facet normal -0.832 0.555 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.5 0.5 0.0 vertex 0.2 0.0 0.0 endloop endfacet
  // Side facets for W - Triangle 6
  facet normal -0.832 0.555 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.5 0.5 0.0 vertex 0.5 0.5 0.2 endloop endfacet
  facet normal -0.832 0.555 0
    outer loop vertex 0.2 0.0 0.2 vertex 0.2 0.0 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal 0.447 0.894 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.2 0.2 0.0 vertex 0.2 0.2 0.2 endloop endfacet
  facet normal 0.447 0.894 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.5 0.5 0.0 vertex 0.2 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 0.2 0.2 0.2 vertex 0.2 0.0 0.0 vertex 0.2 0.0 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 0.2 0.2 0.2 vertex 0.2 0.2 0.0 vertex 0.2 0.0 0.0 endloop endfacet
  // Side facets for W - Triangle 7
  facet normal 0.832 0.555 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.5 0.5 0.0 vertex 0.5 0.5 0.2 endloop endfacet
  facet normal 0.832 0.555 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.0 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal -0.928 -0.371 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.6 0.0 0.0 vertex 0.6 0.0 0.2 endloop endfacet
  facet normal -0.928 -0.371 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.5 0.5 0.0 vertex 0.6 0.0 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.6 0.0 0.2 vertex 0.8 0.0 0.0 vertex 0.8 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 0.6 0.0 0.2 vertex 0.6 0.0 0.0 vertex 0.8 0.0 0.0 endloop endfacet
  // Side facets for W - Triangle 8
  facet normal 0 1 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.2 0.0 vertex 0.8 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 0.8 0.0 0.2 vertex 0.8 0.0 0.0 vertex 0.8 0.2 0.0 endloop endfacet
  facet normal -0.447 0.894 0
    outer loop vertex 0.8 0.2 0.2 vertex 0.5 0.5 0.0 vertex 0.5 0.5 0.2 endloop endfacet
  facet normal -0.447 0.894 0
    outer loop vertex 0.8 0.2 0.2 vertex 0.8 0.2 0.0 vertex 0.5 0.5 0.0 endloop endfacet
  facet normal 0.832 0.555 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.8 0.0 0.0 vertex 0.8 0.0 0.2 endloop endfacet
  facet normal 0.832 0.555 0
    outer loop vertex 0.5 0.5 0.2 vertex 0.5 0.5 0.0 vertex 0.8 0.0 0.0 endloop endfacet



  // Letter E

  // Front Faces
  facet normal 0 0 1
    outer loop vertex 1.2 0.0 0.2 vertex 2.2 0.0 0.2 vertex 1.2 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 2.2 0.0 0.2 vertex 2.2 0.2 0.2 vertex 1.2 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 1.2 0.2 0.2 vertex 1.4 0.2 0.2 vertex 1.2 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 1.4 0.2 0.2 vertex 1.4 1.3 0.2 vertex 1.2 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 1.2 1.3 0.2 vertex 2.2 1.3 0.2 vertex 1.2 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 2.2 1.3 0.2 vertex 2.2 1.5 0.2 vertex 1.2 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 1.4 0.65 0.2 vertex 2.0 0.65 0.2 vertex 1.4 0.85 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 2.0 0.65 0.2 vertex 2.0 0.85 0.2 vertex 1.4 0.85 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 1.2 0.0 0.0 vertex 1.2 0.2 0.0 vertex 2.2 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 2.2 0.0 0.0 vertex 1.2 0.2 0.0 vertex 2.2 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 1.2 0.2 0.0 vertex 1.2 1.3 0.0 vertex 1.4 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 1.4 0.2 0.0 vertex 1.2 1.3 0.0 vertex 1.4 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 1.2 1.3 0.0 vertex 1.2 1.5 0.0 vertex 2.2 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 2.2 1.3 0.0 vertex 1.2 1.5 0.0 vertex 2.2 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 1.4 0.65 0.0 vertex 1.4 0.85 0.0 vertex 2.0 0.65 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 2.0 0.65 0.0 vertex 1.4 0.85 0.0 vertex 2.0 0.85 0.0 endloop endfacet
  // Side Faces
  // Side facets for E1 - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 1.2 0.0 0.2 vertex 2.2 0.0 0.0 vertex 2.2 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 1.2 0.0 0.2 vertex 1.2 0.0 0.0 vertex 2.2 0.0 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 2.2 0.0 0.2 vertex 1.2 0.2 0.0 vertex 1.2 0.2 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 2.2 0.0 0.2 vertex 2.2 0.0 0.0 vertex 1.2 0.2 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 0.2 0.2 vertex 1.2 0.0 0.0 vertex 1.2 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 0.2 0.2 vertex 1.2 0.2 0.0 vertex 1.2 0.0 0.0 endloop endfacet
  // Side facets for E1 - Triangle 2
  facet normal 1 0 0
    outer loop vertex 2.2 0.0 0.2 vertex 2.2 0.2 0.0 vertex 2.2 0.2 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 2.2 0.0 0.2 vertex 2.2 0.0 0.0 vertex 2.2 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.2 0.2 0.2 vertex 1.2 0.2 0.0 vertex 1.2 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.2 0.2 0.2 vertex 2.2 0.2 0.0 vertex 1.2 0.2 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 1.2 0.2 0.2 vertex 2.2 0.0 0.0 vertex 2.2 0.0 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 1.2 0.2 0.2 vertex 1.2 0.2 0.0 vertex 2.2 0.0 0.0 endloop endfacet
  // Side facets for E1 - Triangle 3
  facet normal 0 1 0
    outer loop vertex 1.2 0.2 0.2 vertex 1.4 0.2 0.0 vertex 1.4 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 1.2 0.2 0.2 vertex 1.2 0.2 0.0 vertex 1.4 0.2 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 1.4 0.2 0.2 vertex 1.2 1.3 0.0 vertex 1.2 1.3 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 1.4 0.2 0.2 vertex 1.4 0.2 0.0 vertex 1.2 1.3 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 1.3 0.2 vertex 1.2 0.2 0.0 vertex 1.2 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 1.3 0.2 vertex 1.2 1.3 0.0 vertex 1.2 0.2 0.0 endloop endfacet
  // Side facets for E1 - Triangle 4
  facet normal 1 0 0
    outer loop vertex 1.4 0.2 0.2 vertex 1.4 1.3 0.0 vertex 1.4 1.3 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 1.4 0.2 0.2 vertex 1.4 0.2 0.0 vertex 1.4 1.3 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 1.4 1.3 0.2 vertex 1.2 1.3 0.0 vertex 1.2 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 1.4 1.3 0.2 vertex 1.4 1.3 0.0 vertex 1.2 1.3 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 1.2 1.3 0.2 vertex 1.4 0.2 0.0 vertex 1.4 0.2 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 1.2 1.3 0.2 vertex 1.2 1.3 0.0 vertex 1.4 0.2 0.0 endloop endfacet
  // Side facets for E1 - Triangle 5
  facet normal 0 -1 0
    outer loop vertex 1.2 1.3 0.2 vertex 2.2 1.3 0.0 vertex 2.2 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 1.2 1.3 0.2 vertex 1.2 1.3 0.0 vertex 2.2 1.3 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 2.2 1.3 0.2 vertex 1.2 1.5 0.0 vertex 1.2 1.5 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 2.2 1.3 0.2 vertex 2.2 1.3 0.0 vertex 1.2 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 1.5 0.2 vertex 1.2 1.3 0.0 vertex 1.2 1.3 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.2 1.5 0.2 vertex 1.2 1.5 0.0 vertex 1.2 1.3 0.0 endloop endfacet
  // Side facets for E1 - Triangle 6
  facet normal 1 0 0
    outer loop vertex 2.2 1.3 0.2 vertex 2.2 1.5 0.0 vertex 2.2 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 2.2 1.3 0.2 vertex 2.2 1.3 0.0 vertex 2.2 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.2 1.5 0.2 vertex 1.2 1.5 0.0 vertex 1.2 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.2 1.5 0.2 vertex 2.2 1.5 0.0 vertex 1.2 1.5 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 1.2 1.5 0.2 vertex 2.2 1.3 0.0 vertex 2.2 1.3 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 1.2 1.5 0.2 vertex 1.2 1.5 0.0 vertex 2.2 1.3 0.0 endloop endfacet
  // Side facets for E1 - Triangle 7
  facet normal 0 -1 0
    outer loop vertex 1.4 0.65 0.2 vertex 2.0 0.65 0.0 vertex 2.0 0.65 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 1.4 0.65 0.2 vertex 1.4 0.65 0.0 vertex 2.0 0.65 0.0 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 2.0 0.65 0.2 vertex 1.4 0.85 0.0 vertex 1.4 0.85 0.2 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 2.0 0.65 0.2 vertex 2.0 0.65 0.0 vertex 1.4 0.85 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.4 0.85 0.2 vertex 1.4 0.65 0.0 vertex 1.4 0.65 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 1.4 0.85 0.2 vertex 1.4 0.85 0.0 vertex 1.4 0.65 0.0 endloop endfacet
  // Side facets for E1 - Triangle 8
  facet normal 1 0 0
    outer loop vertex 2.0 0.65 0.2 vertex 2.0 0.85 0.0 vertex 2.0 0.85 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 2.0 0.65 0.2 vertex 2.0 0.65 0.0 vertex 2.0 0.85 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.0 0.85 0.2 vertex 1.4 0.85 0.0 vertex 1.4 0.85 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.0 0.85 0.2 vertex 2.0 0.85 0.0 vertex 1.4 0.85 0.0 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 1.4 0.85 0.2 vertex 2.0 0.65 0.0 vertex 2.0 0.65 0.2 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 1.4 0.85 0.2 vertex 1.4 0.85 0.0 vertex 2.0 0.65 0.0 endloop endfacet



  // Letter L

  // Front Faces
  facet normal 0 0 1
    outer loop vertex 2.4 0.0 0.2 vertex 3.4 0.0 0.2 vertex 2.4 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.4 0.0 0.2 vertex 3.4 0.2 0.2 vertex 2.4 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 2.4 0.2 0.2 vertex 2.6 0.2 0.2 vertex 2.4 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 2.6 0.2 0.2 vertex 2.6 1.5 0.2 vertex 2.4 1.5 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 2.4 0.0 0.0 vertex 2.4 0.2 0.0 vertex 3.4 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.4 0.0 0.0 vertex 2.4 0.2 0.0 vertex 3.4 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 2.4 0.2 0.0 vertex 2.4 1.5 0.0 vertex 2.6 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 2.6 0.2 0.0 vertex 2.4 1.5 0.0 vertex 2.6 1.5 0.0 endloop endfacet
  // Side Faces
  // Side facets for L - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 2.4 0.0 0.2 vertex 3.4 0.0 0.0 vertex 3.4 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 2.4 0.0 0.2 vertex 2.4 0.0 0.0 vertex 3.4 0.0 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 3.4 0.0 0.2 vertex 2.4 0.2 0.0 vertex 2.4 0.2 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 3.4 0.0 0.2 vertex 3.4 0.0 0.0 vertex 2.4 0.2 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 2.4 0.2 0.2 vertex 2.4 0.0 0.0 vertex 2.4 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 2.4 0.2 0.2 vertex 2.4 0.2 0.0 vertex 2.4 0.0 0.0 endloop endfacet
  // Side facets for L - Triangle 2
  facet normal 1 0 0
    outer loop vertex 3.4 0.0 0.2 vertex 3.4 0.2 0.0 vertex 3.4 0.2 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 3.4 0.0 0.2 vertex 3.4 0.0 0.0 vertex 3.4 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 3.4 0.2 0.2 vertex 2.4 0.2 0.0 vertex 2.4 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 3.4 0.2 0.2 vertex 3.4 0.2 0.0 vertex 2.4 0.2 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 2.4 0.2 0.2 vertex 3.4 0.0 0.0 vertex 3.4 0.0 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 2.4 0.2 0.2 vertex 2.4 0.2 0.0 vertex 3.4 0.0 0.0 endloop endfacet
  // Side facets for L - Triangle 3
  facet normal 0 1 0
    outer loop vertex 2.4 0.2 0.2 vertex 2.6 0.2 0.0 vertex 2.6 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.4 0.2 0.2 vertex 2.4 0.2 0.0 vertex 2.6 0.2 0.0 endloop endfacet
  facet normal 0.989 -0.151 0
    outer loop vertex 2.6 0.2 0.2 vertex 2.4 1.5 0.0 vertex 2.4 1.5 0.2 endloop endfacet
  facet normal 0.989 -0.151 0
    outer loop vertex 2.6 0.2 0.2 vertex 2.6 0.2 0.0 vertex 2.4 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 2.4 1.5 0.2 vertex 2.4 0.2 0.0 vertex 2.4 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 2.4 1.5 0.2 vertex 2.4 1.5 0.0 vertex 2.4 0.2 0.0 endloop endfacet
  // Side facets for L - Triangle 4
  facet normal 1 0 0
    outer loop vertex 2.6 0.2 0.2 vertex 2.6 1.5 0.0 vertex 2.6 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 2.6 0.2 0.2 vertex 2.6 0.2 0.0 vertex 2.6 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.6 1.5 0.2 vertex 2.4 1.5 0.0 vertex 2.4 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 2.6 1.5 0.2 vertex 2.6 1.5 0.0 vertex 2.4 1.5 0.0 endloop endfacet
  facet normal 0.989 -0.151 0
    outer loop vertex 2.4 1.5 0.2 vertex 2.6 0.2 0.0 vertex 2.6 0.2 0.2 endloop endfacet
  facet normal 0.989 -0.151 0
    outer loop vertex 2.4 1.5 0.2 vertex 2.4 1.5 0.0 vertex 2.6 0.2 0.0 endloop endfacet



  // Letter C

  // Front Faces
  facet normal 0 0 1
    outer loop vertex 3.6 0.0 0.2 vertex 4.6 0.0 0.2 vertex 4.6 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.6 0.0 0.2 vertex 4.6 0.2 0.2 vertex 3.6 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.6 0.2 0.2 vertex 3.8 0.2 0.2 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.8 0.2 0.2 vertex 3.8 1.3 0.2 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.6 1.3 0.2 vertex 4.6 1.3 0.2 vertex 4.6 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 3.6 1.3 0.2 vertex 4.6 1.5 0.2 vertex 3.6 1.5 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 3.6 0.0 0.0 vertex 4.6 0.2 0.0 vertex 4.6 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.6 0.0 0.0 vertex 3.6 0.2 0.0 vertex 4.6 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.6 0.2 0.0 vertex 3.6 1.3 0.0 vertex 3.8 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.8 0.2 0.0 vertex 3.6 1.3 0.0 vertex 3.8 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.6 1.3 0.0 vertex 4.6 1.5 0.0 vertex 4.6 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 3.6 1.3 0.0 vertex 3.6 1.5 0.0 vertex 4.6 1.5 0.0 endloop endfacet
  // Side Faces
  // Side facets for C - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 3.6 0.0 0.2 vertex 4.6 0.0 0.0 vertex 4.6 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 3.6 0.0 0.2 vertex 3.6 0.0 0.0 vertex 4.6 0.0 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 4.6 0.0 0.2 vertex 4.6 0.2 0.0 vertex 4.6 0.2 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 4.6 0.0 0.2 vertex 4.6 0.0 0.0 vertex 4.6 0.2 0.0 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 4.6 0.2 0.2 vertex 3.6 0.0 0.0 vertex 3.6 0.0 0.2 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 4.6 0.2 0.2 vertex 4.6 0.2 0.0 vertex 3.6 0.0 0.0 endloop endfacet
  // Side facets for C - Triangle 2
  facet normal 0.196 0.981 0
    outer loop vertex 3.6 0.0 0.2 vertex 4.6 0.2 0.0 vertex 4.6 0.2 0.2 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 3.6 0.0 0.2 vertex 3.6 0.0 0.0 vertex 4.6 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 4.6 0.2 0.2 vertex 3.6 0.2 0.0 vertex 3.6 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 4.6 0.2 0.2 vertex 4.6 0.2 0.0 vertex 3.6 0.2 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 0.2 0.2 vertex 3.6 0.0 0.0 vertex 3.6 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 0.2 0.2 vertex 3.6 0.2 0.0 vertex 3.6 0.0 0.0 endloop endfacet
  // Side facets for C - Triangle 3
  facet normal 0 1 0
    outer loop vertex 3.6 0.2 0.2 vertex 3.8 0.2 0.0 vertex 3.8 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 3.6 0.2 0.2 vertex 3.6 0.2 0.0 vertex 3.8 0.2 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 3.8 0.2 0.2 vertex 3.6 1.3 0.0 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 3.8 0.2 0.2 vertex 3.8 0.2 0.0 vertex 3.6 1.3 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.6 0.2 0.0 vertex 3.6 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.6 1.3 0.0 vertex 3.6 0.2 0.0 endloop endfacet
  // Side facets for C - Triangle 4
  facet normal 1 0 0
    outer loop vertex 3.8 0.2 0.2 vertex 3.8 1.3 0.0 vertex 3.8 1.3 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 3.8 0.2 0.2 vertex 3.8 0.2 0.0 vertex 3.8 1.3 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 3.8 1.3 0.2 vertex 3.6 1.3 0.0 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 3.8 1.3 0.2 vertex 3.8 1.3 0.0 vertex 3.6 1.3 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.8 0.2 0.0 vertex 3.8 0.2 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.6 1.3 0.0 vertex 3.8 0.2 0.0 endloop endfacet
  // Side facets for C - Triangle 5
  facet normal 0 -1 0
    outer loop vertex 3.6 1.3 0.2 vertex 4.6 1.3 0.0 vertex 4.6 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.6 1.3 0.0 vertex 4.6 1.3 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 4.6 1.3 0.2 vertex 4.6 1.5 0.0 vertex 4.6 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 4.6 1.3 0.2 vertex 4.6 1.3 0.0 vertex 4.6 1.5 0.0 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 4.6 1.5 0.2 vertex 3.6 1.3 0.0 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 4.6 1.5 0.2 vertex 4.6 1.5 0.0 vertex 3.6 1.3 0.0 endloop endfacet
  // Side facets for C - Triangle 6
  facet normal 0.196 0.981 0
    outer loop vertex 3.6 1.3 0.2 vertex 4.6 1.5 0.0 vertex 4.6 1.5 0.2 endloop endfacet
  facet normal 0.196 0.981 0
    outer loop vertex 3.6 1.3 0.2 vertex 3.6 1.3 0.0 vertex 4.6 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 4.6 1.5 0.2 vertex 3.6 1.5 0.0 vertex 3.6 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 4.6 1.5 0.2 vertex 4.6 1.5 0.0 vertex 3.6 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 1.5 0.2 vertex 3.6 1.3 0.0 vertex 3.6 1.3 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 3.6 1.5 0.2 vertex 3.6 1.5 0.0 vertex 3.6 1.3 0.0 endloop endfacet


  // Letter O

  // Front Faces
  facet normal 0 0 1
    outer loop vertex 4.8 0.0 0.2 vertex 5.8 0.0 0.2 vertex 4.8 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 5.8 0.0 0.2 vertex 5.8 0.2 0.2 vertex 4.8 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 4.8 1.3 0.2 vertex 5.8 1.3 0.2 vertex 4.8 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 5.8 1.3 0.2 vertex 5.8 1.5 0.2 vertex 4.8 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 4.8 0.2 0.2 vertex 5.0 0.2 0.2 vertex 4.8 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 5.0 0.2 0.2 vertex 5.0 1.3 0.2 vertex 4.8 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 5.6 0.2 0.2 vertex 5.8 0.2 0.2 vertex 5.6 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 5.8 0.2 0.2 vertex 5.8 1.3 0.2 vertex 5.6 1.3 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 4.8 0.0 0.0 vertex 4.8 0.2 0.0 vertex 5.8 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 5.8 0.0 0.0 vertex 4.8 0.2 0.0 vertex 5.8 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 4.8 1.3 0.0 vertex 4.8 1.5 0.0 vertex 5.8 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 5.8 1.3 0.0 vertex 4.8 1.5 0.0 vertex 5.8 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 4.8 0.2 0.0 vertex 4.8 1.3 0.0 vertex 5.0 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 5.0 0.2 0.0 vertex 4.8 1.3 0.0 vertex 5.0 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 5.6 0.2 0.0 vertex 5.6 1.3 0.0 vertex 5.8 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 5.8 0.2 0.0 vertex 5.6 1.3 0.0 vertex 5.8 1.3 0.0 endloop endfacet
  // Side Faces
  // Side facets for O - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 4.8 0.0 0.2 vertex 5.8 0.0 0.0 vertex 5.8 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 4.8 0.0 0.2 vertex 4.8 0.0 0.0 vertex 5.8 0.0 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 5.8 0.0 0.2 vertex 4.8 0.2 0.0 vertex 4.8 0.2 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 5.8 0.0 0.2 vertex 5.8 0.0 0.0 vertex 4.8 0.2 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 0.2 0.2 vertex 4.8 0.0 0.0 vertex 4.8 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 0.2 0.2 vertex 4.8 0.2 0.0 vertex 4.8 0.0 0.0 endloop endfacet
  // Side facets for O - Triangle 2
  facet normal 1 0 0
    outer loop vertex 5.8 0.0 0.2 vertex 5.8 0.2 0.0 vertex 5.8 0.2 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 5.8 0.0 0.2 vertex 5.8 0.0 0.0 vertex 5.8 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 5.8 0.2 0.2 vertex 4.8 0.2 0.0 vertex 4.8 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 5.8 0.2 0.2 vertex 5.8 0.2 0.0 vertex 4.8 0.2 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 4.8 0.2 0.2 vertex 5.8 0.0 0.0 vertex 5.8 0.0 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 4.8 0.2 0.2 vertex 4.8 0.2 0.0 vertex 5.8 0.0 0.0 endloop endfacet
  // Side facets for O - Triangle 3
  facet normal 0 -1 0
    outer loop vertex 4.8 1.3 0.2 vertex 5.8 1.3 0.0 vertex 5.8 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 4.8 1.3 0.2 vertex 4.8 1.3 0.0 vertex 5.8 1.3 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 5.8 1.3 0.2 vertex 4.8 1.5 0.0 vertex 4.8 1.5 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 5.8 1.3 0.2 vertex 5.8 1.3 0.0 vertex 4.8 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 1.5 0.2 vertex 4.8 1.3 0.0 vertex 4.8 1.3 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 1.5 0.2 vertex 4.8 1.5 0.0 vertex 4.8 1.3 0.0 endloop endfacet
  // Side facets for O - Triangle 4
  facet normal 1 0 0
    outer loop vertex 5.8 1.3 0.2 vertex 5.8 1.5 0.0 vertex 5.8 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 5.8 1.3 0.2 vertex 5.8 1.3 0.0 vertex 5.8 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 5.8 1.5 0.2 vertex 4.8 1.5 0.0 vertex 4.8 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 5.8 1.5 0.2 vertex 5.8 1.5 0.0 vertex 4.8 1.5 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 4.8 1.5 0.2 vertex 5.8 1.3 0.0 vertex 5.8 1.3 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 4.8 1.5 0.2 vertex 4.8 1.5 0.0 vertex 5.8 1.3 0.0 endloop endfacet
  // Side facets for O - Triangle 5
  facet normal 0 1 0
    outer loop vertex 4.8 0.2 0.2 vertex 5.0 0.2 0.0 vertex 5.0 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 4.8 0.2 0.2 vertex 4.8 0.2 0.0 vertex 5.0 0.2 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.0 0.2 0.2 vertex 4.8 1.3 0.0 vertex 4.8 1.3 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.0 0.2 0.2 vertex 5.0 0.2 0.0 vertex 4.8 1.3 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 1.3 0.2 vertex 4.8 0.2 0.0 vertex 4.8 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 4.8 1.3 0.2 vertex 4.8 1.3 0.0 vertex 4.8 0.2 0.0 endloop endfacet
  // Side facets for O - Triangle 6
  facet normal 1 0 0
    outer loop vertex 5.0 0.2 0.2 vertex 5.0 1.3 0.0 vertex 5.0 1.3 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 5.0 0.2 0.2 vertex 5.0 0.2 0.0 vertex 5.0 1.3 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 5.0 1.3 0.2 vertex 4.8 1.3 0.0 vertex 4.8 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 5.0 1.3 0.2 vertex 5.0 1.3 0.0 vertex 4.8 1.3 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 4.8 1.3 0.2 vertex 5.0 0.2 0.0 vertex 5.0 0.2 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 4.8 1.3 0.2 vertex 4.8 1.3 0.0 vertex 5.0 0.2 0.0 endloop endfacet
  // Side facets for O - Triangle 7
  facet normal 0 1 0
    outer loop vertex 5.6 0.2 0.2 vertex 5.8 0.2 0.0 vertex 5.8 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 5.6 0.2 0.2 vertex 5.6 0.2 0.0 vertex 5.8 0.2 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.8 0.2 0.2 vertex 5.6 1.3 0.0 vertex 5.6 1.3 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.8 0.2 0.2 vertex 5.8 0.2 0.0 vertex 5.6 1.3 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 5.6 1.3 0.2 vertex 5.6 0.2 0.0 vertex 5.6 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 5.6 1.3 0.2 vertex 5.6 1.3 0.0 vertex 5.6 0.2 0.0 endloop endfacet
  // Side facets for O - Triangle 8
  facet normal 1 0 0
    outer loop vertex 5.8 0.2 0.2 vertex 5.8 1.3 0.0 vertex 5.8 1.3 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 5.8 0.2 0.2 vertex 5.8 0.2 0.0 vertex 5.8 1.3 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 5.8 1.3 0.2 vertex 5.6 1.3 0.0 vertex 5.6 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 5.8 1.3 0.2 vertex 5.8 1.3 0.0 vertex 5.6 1.3 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.6 1.3 0.2 vertex 5.8 0.2 0.0 vertex 5.8 0.2 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 5.6 1.3 0.2 vertex 5.6 1.3 0.0 vertex 5.8 0.2 0.0 endloop endfacet


  // Letter M

  // Front Faces
  facet normal 0 0 1
    outer loop vertex 6.0 0.0 0.2 vertex 6.2 0.0 0.2 vertex 6.0 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.2 0.0 0.2 vertex 6.2 1.5 0.2 vertex 6.0 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.8 0.0 0.2 vertex 7.0 0.0 0.2 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 7.0 0.0 0.2 vertex 7.0 1.5 0.2 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.2 1.5 0.2 vertex 6.5 1.0 0.2 vertex 6.4 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.2 1.5 0.2 vertex 6.2 1.3 0.2 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.8 1.5 0.2 vertex 6.6 1.5 0.2 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 6.8 1.5 0.2 vertex 6.5 1.0 0.2 vertex 6.8 1.3 0.2 endloop endfacet
  // Back Faces
  facet normal 0 0 -1
    outer loop vertex 6.0 0.0 0.0 vertex 6.0 1.5 0.0 vertex 6.2 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.2 0.0 0.0 vertex 6.0 1.5 0.0 vertex 6.2 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.8 0.0 0.0 vertex 6.8 1.5 0.0 vertex 7.0 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 7.0 0.0 0.0 vertex 6.8 1.5 0.0 vertex 7.0 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.2 1.5 0.0 vertex 6.4 1.5 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.2 1.5 0.0 vertex 6.5 1.0 0.0 vertex 6.2 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.8 1.5 0.0 vertex 6.5 1.0 0.0 vertex 6.6 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 6.8 1.5 0.0 vertex 6.8 1.3 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  // Side Faces
  // Side facets for M - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 6.0 0.0 0.2 vertex 6.2 0.0 0.0 vertex 6.2 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 6.0 0.0 0.2 vertex 6.0 0.0 0.0 vertex 6.2 0.0 0.0 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.2 0.0 0.2 vertex 6.0 1.5 0.0 vertex 6.0 1.5 0.2 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.2 0.0 0.2 vertex 6.2 0.0 0.0 vertex 6.0 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 6.0 1.5 0.2 vertex 6.0 0.0 0.0 vertex 6.0 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 6.0 1.5 0.2 vertex 6.0 1.5 0.0 vertex 6.0 0.0 0.0 endloop endfacet
  // Side facets for M - Triangle 2
  facet normal 1 0 0
    outer loop vertex 6.2 0.0 0.2 vertex 6.2 1.5 0.0 vertex 6.2 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 6.2 0.0 0.2 vertex 6.2 0.0 0.0 vertex 6.2 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.0 1.5 0.0 vertex 6.0 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.2 1.5 0.0 vertex 6.0 1.5 0.0 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.0 1.5 0.2 vertex 6.2 0.0 0.0 vertex 6.2 0.0 0.2 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.0 1.5 0.2 vertex 6.0 1.5 0.0 vertex 6.2 0.0 0.0 endloop endfacet
  // Side facets for M - Triangle 3
  facet normal 0 -1 0
    outer loop vertex 6.8 0.0 0.2 vertex 7.0 0.0 0.0 vertex 7.0 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 6.8 0.0 0.2 vertex 6.8 0.0 0.0 vertex 7.0 0.0 0.0 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 7.0 0.0 0.2 vertex 6.8 1.5 0.0 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 7.0 0.0 0.2 vertex 7.0 0.0 0.0 vertex 6.8 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.8 0.0 0.0 vertex 6.8 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.8 1.5 0.0 vertex 6.8 0.0 0.0 endloop endfacet
  // Side facets for M - Triangle 4
  facet normal 1 0 0
    outer loop vertex 7.0 0.0 0.2 vertex 7.0 1.5 0.0 vertex 7.0 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 7.0 0.0 0.2 vertex 7.0 0.0 0.0 vertex 7.0 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 7.0 1.5 0.2 vertex 6.8 1.5 0.0 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 7.0 1.5 0.2 vertex 7.0 1.5 0.0 vertex 6.8 1.5 0.0 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.8 1.5 0.2 vertex 7.0 0.0 0.0 vertex 7.0 0.0 0.2 endloop endfacet
  facet normal 0.989 -0.131 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.8 1.5 0.0 vertex 7.0 0.0 0.0 endloop endfacet
  // Side facets for M - Triangle 5
  facet normal 0.894 0.447 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.5 1.0 0.0 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal 0.894 0.447 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.2 1.5 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  facet normal -0.894 0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.4 1.5 0.0 vertex 6.4 1.5 0.2 endloop endfacet
  facet normal -0.894 0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.5 1.0 0.0 vertex 6.4 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 6.4 1.5 0.2 vertex 6.2 1.5 0.0 vertex 6.2 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 6.4 1.5 0.2 vertex 6.4 1.5 0.0 vertex 6.2 1.5 0.0 endloop endfacet
  // Side facets for M - Triangle 6
  facet normal -1 0 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.2 1.3 0.0 vertex 6.2 1.3 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 6.2 1.5 0.2 vertex 6.2 1.5 0.0 vertex 6.2 1.3 0.0 endloop endfacet
  facet normal 0.707 0.707 0
    outer loop vertex 6.2 1.3 0.2 vertex 6.5 1.0 0.0 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal 0.707 0.707 0
    outer loop vertex 6.2 1.3 0.2 vertex 6.2 1.3 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  facet normal 0.894 0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.2 1.5 0.0 vertex 6.2 1.5 0.2 endloop endfacet
  facet normal 0.894 0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.5 1.0 0.0 vertex 6.2 1.5 0.0 endloop endfacet
  // Side facets for M - Triangle 7
  facet normal 0 1 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.6 1.5 0.0 vertex 6.6 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.8 1.5 0.0 vertex 6.6 1.5 0.0 endloop endfacet
  facet normal 0.894 -0.447 0
    outer loop vertex 6.6 1.5 0.2 vertex 6.5 1.0 0.0 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal 0.894 -0.447 0
    outer loop vertex 6.6 1.5 0.2 vertex 6.6 1.5 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  facet normal -0.894 -0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.8 1.5 0.0 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal -0.894 -0.447 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.5 1.0 0.0 vertex 6.8 1.5 0.0 endloop endfacet
  // Side facets for M - Triangle 8
  facet normal -0.894 -0.447 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.5 1.0 0.0 vertex 6.5 1.0 0.2 endloop endfacet
  facet normal -0.894 -0.447 0
    outer loop vertex 6.8 1.5 0.2 vertex 6.8 1.5 0.0 vertex 6.5 1.0 0.0 endloop endfacet
  facet normal -0.707 0.707 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.8 1.3 0.0 vertex 6.8 1.3 0.2 endloop endfacet
  facet normal -0.707 0.707 0
    outer loop vertex 6.5 1.0 0.2 vertex 6.5 1.0 0.0 vertex 6.8 1.3 0.0 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 6.8 1.3 0.2 vertex 6.8 1.5 0.0 vertex 6.8 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 6.8 1.3 0.2 vertex 6.8 1.3 0.0 vertex 6.8 1.5 0.0 endloop endfacet


  // Letter E

  // Front Faces (Z=0.2)
  facet normal 0 0 1
    outer loop vertex 7.2 0.0 0.2 vertex 8.2 0.0 0.2 vertex 7.2 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 8.2 0.0 0.2 vertex 8.2 0.2 0.2 vertex 7.2 0.2 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 7.2 0.2 0.2 vertex 7.4 0.2 0.2 vertex 7.2 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 7.4 0.2 0.2 vertex 7.4 1.3 0.2 vertex 7.2 1.3 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 7.2 1.3 0.2 vertex 8.2 1.3 0.2 vertex 7.2 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 8.2 1.3 0.2 vertex 8.2 1.5 0.2 vertex 7.2 1.5 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 7.4 0.65 0.2 vertex 8.0 0.65 0.2 vertex 7.4 0.85 0.2 endloop endfacet
  facet normal 0 0 1
    outer loop vertex 8.0 0.65 0.2 vertex 8.0 0.85 0.2 vertex 7.4 0.85 0.2 endloop endfacet

  // Back Faces (Z=0)
  facet normal 0 0 -1
    outer loop vertex 7.2 0.0 0.0 vertex 7.2 0.2 0.0 vertex 8.2 0.0 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 8.2 0.0 0.0 vertex 7.2 0.2 0.0 vertex 8.2 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 7.2 0.2 0.0 vertex 7.2 1.3 0.0 vertex 7.4 0.2 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 7.4 0.2 0.0 vertex 7.2 1.3 0.0 vertex 7.4 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 7.2 1.3 0.0 vertex 7.2 1.5 0.0 vertex 8.2 1.3 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 8.2 1.3 0.0 vertex 7.2 1.5 0.0 vertex 8.2 1.5 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 7.4 0.65 0.0 vertex 7.4 0.85 0.0 vertex 8.0 0.65 0.0 endloop endfacet
  facet normal 0 0 -1
    outer loop vertex 8.0 0.65 0.0 vertex 7.4 0.85 0.0 vertex 8.0 0.85 0.0 endloop endfacet

  // Side Facets
  // Side facets for E2 - Triangle 1
  facet normal 0 -1 0
    outer loop vertex 7.2 0.0 0.2 vertex 8.2 0.0 0.0 vertex 8.2 0.0 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 7.2 0.0 0.2 vertex 7.2 0.0 0.0 vertex 8.2 0.0 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 8.2 0.0 0.2 vertex 7.2 0.2 0.0 vertex 7.2 0.2 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 8.2 0.0 0.2 vertex 8.2 0.0 0.0 vertex 7.2 0.2 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 0.2 0.2 vertex 7.2 0.0 0.0 vertex 7.2 0.0 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 0.2 0.2 vertex 7.2 0.2 0.0 vertex 7.2 0.0 0.0 endloop endfacet
  // Side facets for E2 - Triangle 2
  facet normal 1 0 0
    outer loop vertex 8.2 0.0 0.2 vertex 8.2 0.2 0.0 vertex 8.2 0.2 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 8.2 0.0 0.2 vertex 8.2 0.0 0.0 vertex 8.2 0.2 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.2 0.2 0.2 vertex 7.2 0.2 0.0 vertex 7.2 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.2 0.2 0.2 vertex 8.2 0.2 0.0 vertex 7.2 0.2 0.0 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 7.2 0.2 0.2 vertex 8.2 0.0 0.0 vertex 8.2 0.0 0.2 endloop endfacet
  facet normal -0.196 -0.981 0
    outer loop vertex 7.2 0.2 0.2 vertex 7.2 0.2 0.0 vertex 8.2 0.0 0.0 endloop endfacet
  // Side facets for E2 - Triangle 3
  facet normal 0 1 0
    outer loop vertex 7.2 0.2 0.2 vertex 7.4 0.2 0.0 vertex 7.4 0.2 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 7.2 0.2 0.2 vertex 7.2 0.2 0.0 vertex 7.4 0.2 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 7.4 0.2 0.2 vertex 7.2 1.3 0.0 vertex 7.2 1.3 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 7.4 0.2 0.2 vertex 7.4 0.2 0.0 vertex 7.2 1.3 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 1.3 0.2 vertex 7.2 0.2 0.0 vertex 7.2 0.2 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 1.3 0.2 vertex 7.2 1.3 0.0 vertex 7.2 0.2 0.0 endloop endfacet
  // Side facets for E2 - Triangle 4
  facet normal 1 0 0
    outer loop vertex 7.4 0.2 0.2 vertex 7.4 1.3 0.0 vertex 7.4 1.3 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 7.4 0.2 0.2 vertex 7.4 0.2 0.0 vertex 7.4 1.3 0.0 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 7.4 1.3 0.2 vertex 7.2 1.3 0.0 vertex 7.2 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 7.4 1.3 0.2 vertex 7.4 1.3 0.0 vertex 7.2 1.3 0.0 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 7.2 1.3 0.2 vertex 7.4 0.2 0.0 vertex 7.4 0.2 0.2 endloop endfacet
  facet normal 0.984 -0.179 0
    outer loop vertex 7.2 1.3 0.2 vertex 7.2 1.3 0.0 vertex 7.4 0.2 0.0 endloop endfacet
  // Side facets for E2 - Triangle 5
  facet normal 0 -1 0
    outer loop vertex 7.2 1.3 0.2 vertex 8.2 1.3 0.0 vertex 8.2 1.3 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 7.2 1.3 0.2 vertex 7.2 1.3 0.0 vertex 8.2 1.3 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 8.2 1.3 0.2 vertex 7.2 1.5 0.0 vertex 7.2 1.5 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 8.2 1.3 0.2 vertex 8.2 1.3 0.0 vertex 7.2 1.5 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 1.5 0.2 vertex 7.2 1.3 0.0 vertex 7.2 1.3 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.2 1.5 0.2 vertex 7.2 1.5 0.0 vertex 7.2 1.3 0.0 endloop endfacet
  // Side facets for E2 - Triangle 6
  facet normal 1 0 0
    outer loop vertex 8.2 1.3 0.2 vertex 8.2 1.5 0.0 vertex 8.2 1.5 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 8.2 1.3 0.2 vertex 8.2 1.3 0.0 vertex 8.2 1.5 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.2 1.5 0.2 vertex 7.2 1.5 0.0 vertex 7.2 1.5 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.2 1.5 0.2 vertex 8.2 1.5 0.0 vertex 7.2 1.5 0.0 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 7.2 1.5 0.2 vertex 8.2 1.3 0.0 vertex 8.2 1.3 0.2 endloop endfacet
  facet normal -0.196 0.981 0
    outer loop vertex 7.2 1.5 0.2 vertex 7.2 1.5 0.0 vertex 8.2 1.3 0.0 endloop endfacet
  // Side facets for E2 - Triangle 7
  facet normal 0 -1 0
    outer loop vertex 7.4 0.65 0.2 vertex 8.0 0.65 0.0 vertex 8.0 0.65 0.2 endloop endfacet
  facet normal 0 -1 0
    outer loop vertex 7.4 0.65 0.2 vertex 7.4 0.65 0.0 vertex 8.0 0.65 0.0 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 8.0 0.65 0.2 vertex 7.4 0.85 0.0 vertex 7.4 0.85 0.2 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 8.0 0.65 0.2 vertex 8.0 0.65 0.0 vertex 7.4 0.85 0.0 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.4 0.85 0.2 vertex 7.4 0.65 0.0 vertex 7.4 0.65 0.2 endloop endfacet
  facet normal -1 0 0
    outer loop vertex 7.4 0.85 0.2 vertex 7.4 0.85 0.0 vertex 7.4 0.65 0.0 endloop endfacet
  // Side facets for E2 - Triangle 8
  facet normal 1 0 0
    outer loop vertex 8.0 0.65 0.2 vertex 8.0 0.85 0.0 vertex 8.0 0.85 0.2 endloop endfacet
  facet normal 1 0 0
    outer loop vertex 8.0 0.65 0.2 vertex 8.0 0.65 0.0 vertex 8.0 0.85 0.0 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.0 0.85 0.2 vertex 7.4 0.85 0.0 vertex 7.4 0.85 0.2 endloop endfacet
  facet normal 0 1 0
    outer loop vertex 8.0 0.85 0.2 vertex 8.0 0.85 0.0 vertex 7.4 0.85 0.0 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 7.4 0.85 0.2 vertex 8.0 0.65 0.0 vertex 8.0 0.65 0.2 endloop endfacet
  facet normal -0.316 -0.949 0
    outer loop vertex 7.4 0.85 0.2 vertex 7.4 0.85 0.0 vertex 8.0 0.65 0.0 endloop endfacet


endsolid welcome_cylindrical
```


### Welcome

Currently working on Backend using C#. Coding is hard, and when it gets confusing I try to tell myself there is only setting variables, writing to variables and conditional branching. The rest is syntax sugar. 


# Projects

### P2P Chat app
Good lesson in network and security and why server-client is prefered as its safer with a trusted middle man. 

### WoW Server
Always having fun creating different [WoW servers](https://github.com/cmangos). Exploring the databases, creating new spells, items, npcs etc. I feel its the best way to get comfortable with programs such as Docker, (MY)SQL and XAMPP in a playground where im not afraid do things wrong.

### WoW Bot
For educational purposes. It plays on my single player server where it can interact with other bots.

It uses OCR(Optical character recognition) for data extraction, and image recognition for terrain avoidance and npc detection. Both horribly inefficient compared to other methods, but its fun to tackle ways to improve it. And it fascinates me how we can take multiple snapshots of numbers, letters, NPCs and obstacles every second, translate it to actionable data, and use it for real-time decisions. Now thanks to cuda us casuals can have fun with image recognition training and OCR with our gaming GPUs.

### AH Sniper Addon

Made an addon that snipes auctions very fast. Woke me up to the power of creating a personalized addon that dont have to account for anything that would slow it down.


How to reach me: Can reach me on Discord: liensimen or via [Email](mailto:Simenli123@hotmail.com)

<div>
  <picture>
   <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" title="Python">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" title="C#">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" title="JavaScript">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" title="HTML5">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" title="CSS">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" title="Bootstrap">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" title="MySQL">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white" alt="Jira" title="Jira">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" title="jQuery">
  </picture>
   <picture>
   <img src="https://img.shields.io/badge/Sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" title="SQLite">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node JS" title="Node JS">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" title="Docker">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" alt="Postman" title="Postman">
  </picture>
  <picture>
   <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white" alt="Swagger" title="Swagger">
  </picture>
 </div>

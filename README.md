{
  "character_id": "CHR_ChunX01",
  "display_name": "춘X-01",
  "model": {
    "fbx": "CHR_ChunX01.fbx",
    "gltf": "CHR_ChunX01.glb",
    "textures": [
      "MAT_Skin_BaseColor.png",
      "MAT_Armor_Metallic.png",
      "MAT_Cloth_Normal.png"
    ],
    "root_bone": "BND_Root",
    "scale": 1.0
  },
  "skeleton_map": {
    "head": "BND_Head",
    "spine": [
      "BND_Spine01",
      "BND_Spine02",
      "BND_Chest"
    ],
    "left_eye": "BND_Eye_L",
    "right_eye": "BND_Eye_R",
    "left_hand": [
      "BND_UpperArm_L",
      "BND_LowerArm_L",
      "BND_Hand_L"
    ],
    "right_hand": [
      "BND_UpperArm_R",
      "BND_LowerArm_R",
      "BND_Hand_R"
    ],
    "left_leg": [
      "BND_Thigh_L",
      "BND_Calf_L",
      "BND_Foot_L"
    ],
    "right_leg": [
      "BND_Thigh_R",
      "BND_Calf_R",
      "BND_Foot_R"
    ]
  },
  "blendshapes": {
    "smile": "BS_Smile",
    "tear": "BS_Tear",
    "angry": "BS_Angry",
    "surprised": "BS_Surprised",
    "neutral": "BS_Neutral"
  },
  "animations": [
    {
      "name": "IDLE",
      "file": "animations/IDLE.fbx",
      "loop": true
    },
    {
      "name": "RUN",
      "file": "animations/RUN.fbx",
      "loop": true
    },
    {
      "name": "ATTACK",
      "file": "animations/ATTACK.fbx",
      "loop": false
    },
    {
      "name": "EMOTION_Smile",
      "file": "animations/EMOTION_Smile.fbx",
      "loop": false
    },
    {
      "name": "EMOTION_Tear",
      "file": "animations/EMOTION_Tear.fbx",
      "loop": false
    }
  ],
  "effects": {
    "core_glow": "FX_EnergyCore_Glow",
    "eye_glow_L": "FX_EyeGlow_L",
    "eye_glow_R": "FX_EyeGlow_R"
  },
  "metadata": {
    "genre": "SF 판소리",
    "style": "Pixar 3D + 하이퍼 리얼",
    "created_by": "brienz AI Studio",
    "version": "1.0.0"
  }
}

# Text-to-3D-asset-generation
Generate realistic 3D assets from text using Stable Diffusion, MiDaS, and Open3D – great for game development and prototyping.

🚀 Features
Text → Image with Stable Diffusion
Image → Depth with MiDaS
Depth → 3D Mesh using Open3D (multi-view fused)
Interactive 3D preview (pythreejs)
Turntable animation (GIF)
Exports .obj for Unity, Blender, Unreal

🔧 How to Use
Open in Google Colab
Set runtime to GPU
Run all cells
Enter your text prompt (e.g., "a sci-fi robot helmet")
View generated image, depth, 3D mesh, and animation

🗂️ Outputs
generated.png – AI image
depth.png – Depth map
fused_mesh.obj – 3D asset
turntable.gif – Mesh animation

🧪 Requirements
Installed via Colab:
bash
Copy
Edit
torch, diffusers, transformers, opencv, open3d, pythreejs, trimesh

📤 Export
Use fused_mesh.obj in Unity, Blender, etc.

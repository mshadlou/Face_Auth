# Face_Auth
Here is an example of using pre-trained model in C# software development. <br>

I'm going to explain a bit about using a pre-training model in C#.  To use a pre-trained model, we can find ONNX model in ONNX Model Zoo or we would train a model in TensorFlow/torch etc and converting it to ONNX. Then we can use Microsoft ML library of OnnxRuntime to apply the model on real world problems. <br>

In following example, the face recognition and landmark detection are carried out. <br>
Dependencies:<br>
<ul>
  <li>OpenCvSharp4</li>
  <li>OpenCvSharp4.Extensions</li>
  <li>OpenCvSharp4.runtime.win</li>
  <li>Microsoft.ML.OnnxRuntime</li>
  <li>UMapx</li>
</ul> 

To view a demo of the software for face recognition and landmark detection, you may check the youtube view at <a href="https://www.youtube.com/watch?v=R_2_lHvdoIs">YouTube video</a>




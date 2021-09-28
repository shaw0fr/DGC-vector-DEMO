### Abstract
Recently, more and more zero-shot voice conversion algorithms have been proposed. As a fundamental part of zero-shot voice conversion, speaker embeddings are the key to improve the speaker similarity of the converted speech. In this paper, we study the impact of speaker embeddings on zero-shot voice conversion performance. To represent the characteristics of target speaker better and improve the speaker similarity in zero-shot voice conversion, we propose a novel speaker representation method in this paper. Our method combines the advantages of D-vector and global style token (GST) based speaker representation. Objective and subjective evaluations show that the proposed method achieves a decent performance on zero-shot voice conversion and improves the speaker similarity significantly over D-vector and GST based speaker embedding.
### DEMO (seen-to-seen voice conversion)

| **Source** | **Target** | **Our Method** | **DG-vector** | **G-vector** | **D-vector** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <audio src="demo/seen/source/p246-real-1.wav" controls preload></audio> | <audio src="demo/seen/p237/p237.wav" controls preload></audio> | <audio src="demo/seen/p237/gdc/model_gst_re_d_c-p246-p237-con-1.wav" controls preload></audio> |<audio src="demo/seen/p237/gd/model_gst_re_d-p246-p237-con-1.wav" controls preload></audio> |<audio src="demo/seen/p237/g/model_gst_re-p246-p237-con-1.wav" controls preload></audio> |<audio src="demo/seen/p237/d/model-p246-p237-con-1.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/seen/source/p234-real-5.wav" controls preload></audio> | <audio src="demo/seen/p240/p240.wav" controls preload></audio> | <audio src="demo/seen/p240/gdc/model_gst_re_d_c-p234-p240-con-5.wav" controls preload></audio> |<audio src="demo/seen/p240/gd/model_gst_re_d-p234-p240-con-5.wav" controls preload></audio> |<audio src="demo/seen/p240/g/model_gst_re-p234-p240-con-5.wav" controls preload></audio> |<audio src="demo/seen/p240/d/model-p234-p240-con-5.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/seen/source/p340-real-5.wav" controls preload></audio> | <audio src="demo/seen/p275/p275.wav" controls preload></audio> | <audio src="demo/seen/p275/gdc/model_gst_re_d_c-p340-p275-con-5.wav" controls preload></audio> |<audio src="demo/seen/p275/gd/model_gst_re_d-p340-p275-con-5.wav" controls preload></audio> |<audio src="demo/seen/p275/g/model_gst_re-p340-p275-con-5.wav" controls preload></audio> |<audio src="demo/seen/p275/d/model-p340-p275-con-5.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/seen/source/p260-real-5.wav" controls preload></audio> | <audio src="demo/seen/p318/p318.wav" controls preload></audio> | <audio src="demo/seen/p318/gdc/model_gst_re_d_c-p260-p318-con-5.wav" controls preload></audio> |<audio src="demo/seen/p318/gd/model_gst_re_d-p260-p318-con-5.wav" controls preload></audio> |<audio src="demo/seen/p318/g/model_gst_re-p260-p318-con-5.wav" controls preload></audio> |<audio src="demo/seen/p318/d/model-p260-p318-con-5.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |



### DEMO (zero-shot voice conversion)

| **Source** | **Target** | **Our Method** | **DG-vector** | **G-vector** | **D-vector** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <audio src="demo/unseen/source/SEM2-real-1.wav" controls preload></audio> | <audio src="demo/unseen/TEM1/TEM1.wav" controls preload></audio> | <audio src="demo/unseen/TEM1/gdc/model_gst_re_d_c-SEM2-TEM1-con-1.wav" controls preload></audio> |<audio src="demo/unseen/TEM1/gd/model_gst_re_d-SEM2-TEM1-con-1.wav" controls preload></audio> |<audio src="demo/unseen/TEM1/g/model_gst_re-SEM2-TEM1-con-1.wav" controls preload></audio> |<audio src="demo/unseen/TEM1/d/model-SEM2-TEM1-con-1.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/unseen/source/SEF1-real-3.wav" controls preload></audio> | <audio src="demo/unseen/TEF1/TEF1.wav" controls preload></audio> | <audio src="demo/unseen/TEF1/gdc/model_gst_re_d_c-SEF1-TEF1-con-3.wav" controls preload></audio> |<audio src="demo/unseen/TEF1/gd/model_gst_re_d-SEF1-TEF1-con-3.wav" controls preload></audio> |<audio src="demo/unseen/TEF1/g/model_gst_re-SEF1-TEF1-con-3.wav" controls preload></audio> |<audio src="demo/unseen/TEF1/d/model-SEF1-TEF1-con-3.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/unseen/source/SEM1-real-5.wav" controls preload></audio> | <audio src="demo/unseen/TEF2/TEF2.wav" controls preload></audio> | <audio src="demo/unseen/TEF2/gdc/model_gst_re_d_c-SEM1-TEF2-con-5.wav" controls preload></audio> |<audio src="demo/unseen/TEF2/gd/model_gst_re_d-SEM1-TEF2-con-5.wav" controls preload></audio> |<audio src="demo/unseen/TEF2/g/model_gst_re-SEM1-TEF2-con-5.wav" controls preload></audio> |<audio src="demo/unseen/TEF2/d/model-SEM1-TEF2-con-5.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |
| <audio src="demo/unseen/source/SEF2-real-4.wav" controls preload></audio> | <audio src="demo/unseen/TEM2/TEM2.wav" controls preload></audio> | <audio src="demo/unseen/TEM2/gdc/model_gst_re_d_c-SEF2-TEM2-con-4.wav" controls preload></audio> |<audio src="demo/unseen/TEM2/gd/model_gst_re_d-SEF2-TEM2-con-4.wav" controls preload></audio> |<audio src="demo/unseen/TEM2/g/model_gst_re-SEF2-TEM2-con-4.wav" controls preload></audio> |<audio src="demo/unseen/TEM2/d/model-SEF2-TEM2-con-4.wav" controls preload></audio> |
| --- | --- | --- | --- | --- | --- |

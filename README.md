# cat-vs-dog-vit-project
Using the pretrained Vision Transformer (ViT) Model, get the following output result:
Pretrained		Vit-b16		Vit-b32		Vit-l16		Vit-l32	
Epoch		acc	loss	acc	loss	acc	loss	acc	loss
1		0.9798	0.0569	0.9647	0.0911	0.9839	0.0434	0.9669	0.0854
2		0.9808	0.0532	0.9642	0.0929	0.9847	0.0414	0.9678	0.0844
3		0.9808	0.0522	0.9631	0.0942	0.9841	0.0436	0.9691	0.0779
4		0.9814	0.0506	0.9601	0.0976	0.9837	0.0445	0.9718	0.0732
5		0.9822	0.0474	0.9648	0.0911	0.9846	0.0432	0.9693	0.0803
6		0.9806	0.0516	0.9603	0.1004	0.9836	0.0447	0.97	0.0773
7		0.9819	0.0491	0.9602	0.0964	0.9833	0.0466	0.9701	0.078
8		0.9808	0.0517	0.9618	0.0969	0.9842	0.0449	0.9717	0.0764
9		0.9812	0.0494	0.9625	0.0943	0.9846	0.044	0.9704	0.078
10		0.9843	0.0437	0.9629	0.0923	0.9842	0.0418	0.9689	0.0812
11		0.9808	0.0495	0.9601	0.0966	0.9834	0.045	0.9693	0.0787
12		0.9798	0.0517	0.9592	0.0973	0.9833	0.0454	0.9674	0.0812
13		0.982	0.0506	0.96	0.1004	0.9855	0.0403	0.9692	0.0805
14		0.9801	0.051	0.9648	0.1011	0.9843	0.0427	0.9702	0.0774
15		0.982	0.0458	0.9601	0.1042	0.9834	0.045	0.9701	0.0779
Average		0.981233333	0.050293333	0.96192	0.096453333	0.984053333	0.043766667	0.96948	0.079186667
![image](https://github.com/Crepopcorn/cat-vs-dog-vit-project/assets/112138670/fa5f45f9-ec00-461d-b758-3dd7998f9f7e)

Accuracy	Vit-l16>Vit-b16>Vit-l32>Vit-b32
	
	Large model of vision transformer has better accuracy than base model (same image patch size)
	Vision Transformer with image patch size of 16 more accurate than with with image patch size of 32
	
Loss	Vit-l16<Vit-b16<Vit-l32<Vit-b32
	
	Large model of vision transformer has less loss than base model (same image patch size)
	Vision Transformer with image patch size of 16 less loss than with with image patch size of 32
	
	Thus, to achieve better result, use large model with fewer image patch size
![image](https://github.com/Crepopcorn/cat-vs-dog-vit-project/assets/112138670/1897fc9e-a833-4f40-a16d-e3bfc0a9964d)

STAMP DETECTION VIA SEMANTIC SEGMENTATION
-----------------------------------------

This project performs automatic stamp detection from document images using:
- A classical filter-based pipeline (color thresholding + masking)
- A U-Net-based deep learning segmentation model (semantic)

- Stamp_operations_notebook.ipynb: Code U-Net pipelines
- model.pth: Trained U-Net weights
- Stamp_detection_report.pdf: Final report
- requirements.txt: List of dependencies

1. Install dependencies:
   pip install -r requirements.txt
2. Open Stamp_operations_notebook.ipynb
3. Run all cells. It will:
   - Use 'test_data/' as input
   - Save classical outputs in 'test_predictions/'
   - Use train/valid/test folders for U-Net inference

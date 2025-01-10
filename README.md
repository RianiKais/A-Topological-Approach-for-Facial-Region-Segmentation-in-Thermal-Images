# A-Topological-Approach-for-Facial-Region-Segmentation-in-Thermal-Images
The use of thermal images as a non-contact modality has expanded drastically in recent years, including applications such as biometrics, detection of specific human behaviors, and extraction of physiological signals. For instance, using thermal images to monitor physiological signals was found to provide better information compared to RGB images, especially in situations where using physical contact sensors is not a possibility. In this paper, we present a novel topological approach that can segment the cheeks and forehead of a human face in a thermal image, with the key benefit that explicit prior information about the cheeks and forehead is unneeded. Our approach leverages topological properties present in a thermal image to provide a non-rectangular bounding curve for the cheeks and forehead, which we compare against a dataset of 1000 thermal images that were manually annotated for this task. By generating a Vietoris-Rips complex on a thermal image filtered by the Canny edge detector, our approach can segment the cheeks and forehead with recall scores as high as 90.4% and 78.4%, respectively.

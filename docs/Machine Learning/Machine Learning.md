# Machine Learning Services

## Rekognition
- Image and video analysis of your application
- Features
	- Identify labels (objects, concepts, people, scenes, and activities) and text
	- Detect inappropriate content
	- Provide highly accurate facial analysis, face comparison, and face search capabilities
- Common use cases:
	- Searchable image and video library
	- Face liveliness detection
	- Face-based user verification
	- Facial detection and analysis
	- Facial search
	- Unsafe content detection
	- Celebrity recognition
	- Text detection
	- Custom labels

### Resources
- [AWS Documentation](https://docs.aws.amazon.com/rekognition/)

## Transcribe
- Automatic conversion of speech to text
- Uses cases:
	- Filter content
	- Analyze content on multi-channel audio
	- Partition the speed of individual speakers
- Available features
	- (Multi-) Language identification
	- Call summarization
	- Real-time category events
	- Real-time issue detection
	- Speaker sentiment
	- Identifying PII
	- Redacting audio/transcript
	- Vocabulary filtering
	- Subtitles

### Resources
- [AWS Documentation](https://docs.aws.amazon.com/transcribe/latest/dg/what-is.html)

## Polly
- Converts text into lifelike speech.
- Features
	- Support multiple languages
	- Variety of lifelike voices
	- Cache and replay Polly generated speech at no additional cost
- Benefits
	- High quality
	- Low latency
	- Support for a large portfolio of languages and voices
	- Cost-effective
	- Cloud-based solution

### Resources
- [AWS Documentation](https://docs.aws.amazon.com/polly/)

## Translate
- Text translation service
- Features
	- Can translate unstructured text documents
	- Works with multiple languages
- Use cases
	- Enable multilingual user experience
	- Process and manage company's incoming data
	- Language-independent processing with other services
		- Extract named entities, sentiment, and key phrases using Amazon Comprehend
		- Make subtitles and live captioning with Amazon Transcribe
		- Speak translated content with Polly

### Resources
- [AWS Documentation](https://docs.aws.amazon.com/translate/latest/dg/what-is.html)

## Lex
- Conversational interface using both voice and text
- Powers Alexa
- Define the conversation flow and Lex will handle dialogue and response handling
- Benefits
	- Simplicity
	- Seamless deployment and scaling
	- Cost-effectiveness
		- Charged only for the text or speech requests made

### Resource
- [AWS Documentation](https://docs.aws.amazon.com/lex/latest/dg/what-is.html)

## Comprehend
- NLP service to extract insights about the contents of documents
- It develops insights by recognizing the entities, key phrases, language, sentiments, and other common elements in a document. 
- Use Amazon Comprehend to create new products based on understanding the structure of documents.
- It can detect PII in either English or Spanish documents
	- Both locate and redact options are available
	- Can be deployed as a real-time service or as a batch job

### Comprehend Medical
- Detects and returns useful information in unstructured clinical text such as physician's notes, discharge summaries, test results, and case notes
- Use cases
	- Patient case management and outcome
		- Doctors and healthcare providers can manage and easily access medical information that doesn’t fit into traditional forms. Patients can report their health concerns in a narrative with more information than standard formats. By analyzing case notes, providers can identify candidates for early screening of medical conditions before the condition becomes more difficult and expensive to treat.
	- Medical billing and healthcare revenue cycle management
- Benefits
	- Easy integration
	- Accuracy
	- Scalability 
	- Integrate with other AWS services
	- Low cost

### Resources
- [AWS Comprehend Documentation](https://docs.aws.amazon.com/comprehend/latest/dg/what-is.html)
- [AWS Comprehend Medical Documentation](https://docs.aws.amazon.com/comprehend-medical/latest/dev/comprehendmedical-welcome.html)

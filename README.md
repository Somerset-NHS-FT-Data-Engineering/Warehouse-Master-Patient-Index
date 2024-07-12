# Warehouse-Master-Patient-Index

Welcome to the official GitHub repository for the Somerset NHS Foundation Trust Warehouse Master Patient Index (WMPI).

This repo aims to describe the algorithm used as part of the matching process within the SomersetFT’s WMPI solution.

## Background
The Trust has many clinical systems, most of which hold their own, independent patient datasets. These can be structured very differently depending on how the application works but all store the same basic demographic information. 

Within our warehouse environment we wanted to create a solution that:

- Provides a single repository of patient demographic data from systems across the trust
- Identifies common patient records, both across systems and in a single system (duplicates)
- Complies with data governance expectations. Particularly surrounding the linking patient records
- Is scalable and can process the ever-increasing number of systems and patient records

At the heart of this sits a matching algorithm that uses a specific subset of core demographic data items to _match_ all patient records within the repository.

It’s this matching algorithm that we hope to showcase within this GitHub repository.

## Matching Algorithm

## License

## Acknowledgments

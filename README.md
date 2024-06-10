# Mintlayer Pool and Delegation Aggregator 

This project aggregates daily data from the Mintlayer API related to pool and delegation activities. The aggregated data is saved as CSV files in the `snapshots` directory. Each snapshot contains the total staked value per address for that day.

## Snapshots

### Daily Total Staked Value

Snapshots are taken daily and record the total staked value for each address. The CSV files are formatted as follows:

```
DAY,address,amount
```

#### Example

```csv
2023-06-07,mtc1q8w2vqwkqpmnyev6a2ve42q2vt76t9gx4g6t6w3g,12345.67
2023-06-07,mtc1q8d3p7vm9ksswxzedaqx09z3sftk3zelzcq3gh6j,23456.78
```

### Observation Period and Atomiq Token Distribution

At the end of the published observation period, we will calculate the average staked value for each address based on the daily snapshots. Atomiq tokens will be distributed according to the calculated averages as per the distribution plan.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Contact

For questions or feedback, please contact [help@atomiqdefi.com](mailto:help@atomiqdefi.com).

